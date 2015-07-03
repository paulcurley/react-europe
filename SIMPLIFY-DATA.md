#Simplifying the data layer

At Twitter, teams have starting adopting React because it’s enabled UI engineers to forget about time when writing rendering code. And we've started exploring similar simplifications in the data layer, embracing the UI’s role as part of a distributed system. First, we'll share how user experience choices are a primary influence on how we design the data layer, especially for teams developing new products with full-stack capabilities. Working with data from multiple backend services has powerful benefits, and shapes the problem space for UI engineering. Next, we'll look at how React and Flux approaches can help in our problem scenarios. Yet even after the advances in React’s component model, the data layer is still an important source of complexity as an app grows and changes over time. Finally, we'll look at new approaches we’ve been exploring, and how designs like decoupling 'recording facts' from 'computing views of those facts' have influenced UI engineering. These designs nudge teams towards simplicity when creating impactful user-facing improvements like real-time updates, optimistic commits, and graceful handling of network outages.

##Kevin Robinson

@krob

Simplifying
colab across stack 
    answers works of lambda architecture
push effect to edge
    components delare needs
    lib code interprets
    lib code reconciles
    share across components
    new component spin up process as needed

data layer spuerpowers - OM & mutability


embrace the log


stores being used as reducers good implementation
