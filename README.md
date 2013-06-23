Knockout in the engine room:
===========================
by <a href="http://twitter.com/mikegeyser" target="_blank">@mikegeyser</a>
for <a href="http://jsinsa.com/" target-"_blank">JSinSA 2013</a>
Saturday, 29th June 2013

KnockoutJS, like many javascript MVVM frameworks, comes across superficially as magical-unicorn-sprinkles that make single page applications a breeze - fast, sexy, slick UX. It follows the trend in many modern web frameworks to taunt you with low hanging fruit, hoping to ensnare you with ease of access and shiny features that can make you look good on the cheap. But anyone who has been burnt by long term consequences of the ten-minute-demo video, or the try-it-live demo website cultivates a measure of cynicism regarding what lies beneath. What makes it tick? What goes on in the engine room? 

This talk will dig through the core tenets of knockout, taking a look at the raw building blocks of the framework and interrogate what options you have at your disposal when the out-of-the-box tools let you down. It will look at the details array manipulation, debugging and tuning computed observables vs. subscriptions, and writing custom binding handlers.

## Work through the examples: ##

The master branch contains the final version of everything, but please feel free to follow through the commit history (if that's your thing) or move between the branches as follows:

### Part 1: Subscriptions basics ###
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/1-1">Step 1: Beginning</a>
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/1-2">Step 2: View model</a>
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/1-3">Step 3: Subscription behaviour</a>
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/1-4">Step 4: Binding as a subscription</a>
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/1-5">Step 5: Computed as a subscription</a>
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/1-6">Step 6: Dependency chain</a>

### Part 2: Array handling ###
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/2-1">Step 1: Beginning</a>
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/2-2">Step 2: Foreach template binding</a>
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/2-3">Step 3: Naive array manipulation</a>
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/2-4">Step 4: Cost of naivete</a>
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/2-5">Step 5: Controlling subscription notification</a>

### Part 3: Custom binding handler ###
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/3-1">Step 1: Beginning</a>
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/3-2">Step 2: Non-trivial template markup</a>
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/3-3">Step 3: Computed result set</a>
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/3-4">Step 4: Custom binding handler</a>
- <a href="https://github.com/mikegeyser/knockout-in-the-engine-room/tree/3-5">Step 5: Infinite scroll</a>
