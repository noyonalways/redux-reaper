<h1 align='center'>Introduction to Redux</h1>

## Topics

1. What is Redux?
2. Inner workings of Redux
3. Initial Project Setup
4. Initialize store and slice
5. Basic Counter with Redux
6. Payload and TypeSafe redux
7. JavaScript Mutation and Function Currying
8. Devtools, Middlwares and custom middlwares
9. RTK Query overview
10. Module recap and homework.

## References:

## Table of Contents:

- [What is Redux](#what-is-redux)
  - [Predictable](#predictable)
  - [Centralize](#centralize)
  - [Debuggable](#debuggable)
  - [Flexible](#flexible)
- [Inner workings of Redux](#inner-workings-of-redux)
  - [Terminology](#terminology)

# What is Redux

Redux is a predictable state container for JavaScript Applications

### Predictable

- Single source of truth
- Immutable Behavior
- Usage of Pure Function
- Object as Action
- Unidirectional flow

### Centralize

- Centralize State

### Debuggable

- Gives a Dev-tool

### Flexible

- Independent UI Framework
- Middleware Support

# Inner workings of Redux

### Terminology

- **Action:** Action taken by user. Each action has a corresponding reducer function
- **Dispatch:** Sending the action object to the store. Dispatching an action triggers the corresponding reducer to update the state
- **Payload:** Optional data that is attached to an action. It carries any additional information that needs to be sent along with the action to update the state
- **Reducer:** A reducer is a pure function that takes the current state and an action as inputs and returns a new state. It defines how the application’s state changes in response to different actions
- **Store:** The store holds the state of the application. The store is responsible for dispatching actions, maintaining the state, and notifying subscribers about state changes
