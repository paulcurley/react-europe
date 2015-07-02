
##Flux over the Wire

Flux is most often used to implement shared state within a single window. But done properly, this architecture can be used to implement real-time, multi-user shared state between many users of the same web applications. Using HTTP requests to dispatch stores, and Websocket to broadcast updates, Flux over the Wire has the potential to trivialize several hard problems. While the idea of using Websockets to back Flux is rather straightforward, doing it in a way that scales up to tens of thousands of concurrent viewers can prove challenging. In addition, Flux over the Wire offers an interface which considerably eases server-side rendering, as it completely abstracts data fetching and data syncing from the React views that tap into its stores and dispatch its actions.

###Elie Rotenberg 

note all state is local
flux
component > action > dispatcher > store > compo .......
state safley shared beteen mutiple components via actions 
symmetrical flux [compoent > actin intent > flux stores > store update]


flux can be impleemnted with any communcation
 * callbacks/promises
 * streams/event emmiters
 * generators
 * webworker
 * websockets

 nexus flux repo

 react nexus supoert subscription batching
 react nexus streamlines datafetching and serverside rendering
