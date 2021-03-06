# Readings: Redux - Asynchronous Actions

* By default, Redux’s actions are dispatched synchronously, which is a problem for any non-trivial app that needs to communicate with an external API or perform side effects. Redux also allows for middleware that sits between an action being dispatched and the action reaching the reducers.

* There are two very popular middleware libraries that allow for side effects and asynchronous actions: Redux Thunk and Redux Saga.

## How granular should your reducers be?

* A Redux app really only has one reducer function: the "root reducer" function that you will pass to createStore. That one root reducer function is responsible for handling all of the actions that are dispatched, and calculating what the entire new state result should be every time.

## Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched

* Each time an action is dispatched, every connected component will be notified, and as a result all of the selectors used by those connected components must be re-evaluated, and no matter what we pass to dispatch, it is still a single action, and many reducers can react to a single actions, a single reducer can react to multiple actions.

## Name a strategy for preventing the above

* Redux Thunk middleware allows you to write action creators that return a function instead of an action. The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met.

## Document the following Vocabulary Terms

* store: A store is a state container which holds the application's state. Redux can have only a single store in the application.

* combined reducers: The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function to createStore.