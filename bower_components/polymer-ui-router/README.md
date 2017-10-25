# \<polymer-ui-router\>

## UI Router wrapper for Polymer 1.x/2.x

https://ui-router.github.io/

UI-Router is one of most popular routing solutions, 
with ports for angular 1.x, 2.x+ and react - now also available for Polymer.

UI-Router provides state based routing. Each feature of an application is defined as a state. One state is active at any time, and UI-Router manages the transitions between the states.

Each state describes the URL, the UI (a view or views), data prerequisites, and other logical prerequisites (such as authentication) for a feature. Before activating a state, UI-Router first fetches any prerequisites (asynchronously), and then activates the view(s) and updates the URL.

UI-Router states are hierarchical; states can be nested inside other states, forming a tree.
Child states may inherit data and behavior (such as authentication) from their parent states.

Some features of UI Router:

* Hierarchical states both abstract and components based
* States can be resolve *(including async)* and activate based on set prerequisites 
* Multiple views per state
* Views can be nested inside other views
* Transition and lifecycle API's



## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. 

Install bower and npm dependencies.

Then run `polymer serve` to serve your application locally.

Run `yarn bundle` to to build ui-router core for dev.
