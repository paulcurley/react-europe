#Isomorphic Flux

Flux provides a good framework for building rich client applications, but did you know you can reuse the flux architecture for server rendering? In this talk, I'll walk you through an isomorphic Flux architecture to give you the holy grail of frontend development. With this architecture you'll be able to reuse all of your application code on the server and client without worrying about server-side concurrency issues that you may see with stock Flux. Once the concepts have been explained, I will introduce the open source libraries that we have open sourced and are powering many of Yahoo's high-traffic web applications.

##Michael Ridgway

@theridgway

###flux shared on client and server


libs to use
view - react - client
router - react router
datafetching - superagent
business logic - flux


Flux libs
    fluxible
    flummox
    alt
    marty.js
    redux


issues
    data deps are not easily known - graphql might solve?
    react server rendering slow - react 0.14 and futher release might fix
    hot reloading doesn;t work in srouce - soltuion on the way

