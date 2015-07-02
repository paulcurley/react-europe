
###inline styles  - micheal chan
* react will let you lean css, but deal with browser inconsitancies?!?
* style is not CSS
    don't call it css, its styles in JS.
* state changes are ui changes

* componenets should be reused and not repurposed
    small frags are repurposed, not reused in css
bring state fully into JS, lack of css/style breaks behaviour
use className to toggle
inject styles with style object with conditions
css only deals with global styling not state (selelcted) style

####COST 
Have to refator state styles to js, minimal

###capability

variables - import global and reuses
pseudo-classes via array length/modulas/etc
pseudo elements - treat just another element in component
hover styles - less in css, complex with mouseenter/out events & responsive condtion
Radium solves hover issue along side responsive conditionss

grab bag
colors fns sass - 
    Color.js - allows lighten darken etc

layout
    bootstrap etc are great for layout
    dont put classes in component, wrap in a div above with lib classes

###distrubuted components
react-soundplayer - well written example

still quiestions about how teams work with this
questions on perf still to be answered







