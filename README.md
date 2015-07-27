# Flight Toolbox

### What is this?

A jumping off point for Flight mixins, where we'll manage official mixin development and provide resources on how to use them to the full.

### What's the current state of the toolbox?

Currently we have four official mixins, all hosted under the FlightJS org on GitHub. Please [submit an issue](https://github.com/flightjs/flight-toolbox/issues/new) if you think you have one to be added.

- [with-child-components](https://github.com/flightjs/flight-with-child-components) for nesting components, making sure that a component and its children are torn down together.
- [with-state](https://github.com/flightjs/flight-with-state) for storing and reacting to change in a component's internal state.
- [with-batch](https://github.com/flightjs/flight-with-batch) for efficiently batching function calls into animation frames, particularly useful for coalescing DOM updates.
- [with-resources](https://github.com/flightjs/flight-with-resources) for sharing named resources between components.
- [with-observable-state](https://github.com/flightjs/flight-with-observable-state) for exposing the state created by [with-state](https://github.com/flightjs/flight-with-state) as an observable sequence (using RxJS)
- [with-observe](https://github.com/flightjs/flight-with-observe) helps manage subscribe/dispose of observables (using RxJS) within the context of component lifecycle.

### What's in development?

We have mixins at various stages of development. Please see individual repository issues to contribute  code or documentation.

- [with-event-proxy](https://github.com/flightjs/flight-with-event-proxy) for proxying events and transforming event data. This is intended to replace the event proxy features which have been [removed from core in Flight 2](https://github.com/flightjs/flight/commit/1f3203db12a51f514d4e81f5ff169df43187157b).
