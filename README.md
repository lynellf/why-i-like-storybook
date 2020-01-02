# Why I LIke Storybook
A premise as to why Storybook is super awesome

I wish I knew of this at my old job
====
At my old job... 
1. We used content management systems to build everything from apps to static sites
2. Not a great developer experience.
3. The process was always; the designer designs, the dev models the back-end, and then plug in the ui
4. The UI should only be contingent upon the design, not the back-end
5. But... we had to do it this way. Because? 
6. Even worse was adding changes, or new features to the UI and test.
7. Hey, I just added a modal on homesite/section-x/item-y/items.
8. I have to <compile code, restart server, etc.> in order to view a change which is completely independent of any real data
9. And that's the "thing". 
10. What UI couldn't exist or run without very speficic data? I can't think of many.

Did we need Storybook to solve this time issue?
====
1. In the 'past', there may be some cases where I'd put together a static html document based on the mock design
2. But... dropping in the html files into an actual template engine afterward was always hit-or-miss
3. There was no real convienent way of spinning up a dev-server solely for the template engine itself and build mocks with fake data
4. And we still had the issue of needing to rebuild/compile our assets each time we made a change.
5. Lastly, we fell into the trap of building UI's that weren't very modular in nature, even though they could have been.
6. We focused too much on getting the current project done and not seeing the 'bigger picture'
7. We had basic boilerplate templates and UI 'components', but went unused 99% of the time.
8. Generally, there was no way to centralize the UI components in a way that made the development process fun or convenient

Storybook: One stone, many birds
====
1. So, in the above points, there's one big issue that irked me like none other.
2. The time it takes to wait for assets to compile and then test them on the actual site/app itself. Man...
3. If I could add up the amount of time I took waiting for assets to compile and jump the view/page I was working on last year?
4. Yes, storybook can allow us to ...
  * View and develop a collection of UI elements, free of any "back-end"
  * Provide flexible dependency injection, or mock-data to 'stress-test' our elements
5. But the reduction or near elimination of the latency between developing and deploying a component cannot be understated.

One benefit began to bubble-up
====
1. Developing UI elements in isolation began to outline the data flow in a way
