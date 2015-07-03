#Going Mobile with React

React.js is changing the way developers think about mobile app development, especially with the recent announcement of React Native. However, in many ways hybrid (web + mobile) app development is here to stay for a large number of mobile apps. Everyone's heard "you can't build a native experience in a web view". We disagree. You just have to know the right tricks. And when you do, the web becomes an incredibly powerful platform for delivering amazing user experience using the technology you know. At Thinkmill in Sydney, over the course of developing several commercial apps, we've experienced the power of using ReactJS for mobile apps built on web technology, and developed a framework we call TouchstoneJS (which Tom Occhino called "the best looking and feeling implementation of this that I've seen" during the Q&A session at React Conf) to share this capability with developers around the world. In this talk I'll share what we've learned and how we've approached the unique challenges of mobile web apps - with tools that are useful to all developers building touch interfaces with React, as well as a walkthrough of our development process and framework. I'll also talk about what you can do with the web platform that you can't with native apps, and even React Native.

##Jed Watson


Touchstone

When to avoid webviews
    if you are facebook or twiter, larrge timlines
    data intesive
    processor internsive
    compleantions in iu

cordova has android plugin to bundle latest browser within you app - find out name


tools for building mobile
    react
    touch
        react-tappable - resolve lots of web -> native touch abstractions
        webkit overflow scroll: touch - dont try reinvent
    layout
        react-container - flexbox implementation with other tools and fixes
        css 
            webkit-stick for headers
            text-rendering, etc, etc
            transforms 
            disable pointer events
    nav & controls

    touchstone
        reimplements react router for mobile
        looking to implement current react-router
        view managers comes with serveral controls out of box
        release with cordova



thinkmill.com.au

    
