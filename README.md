# Jest Timers Repro

I copied this code [from Jest's documentation](https://jestjs.io/docs/timer-mocks) to try and debug an issue I'm having with Jest's timer mocks. I was expecting that this example from the docs would work fine, but it actually fails because in the test, `setTimeout` is a standard function, not a mock.
