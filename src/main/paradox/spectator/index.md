@@@ index

* [Registry](registry.md)
* [Counters](counters.md)
* [Timers](timers.md)
* [Distribution Summaries](dist-summaries.md)
* [Gauges](gauges.md)
* [Clock](clock.md)
* [Testing](testing.md)
* [Netflix Integration](netflix.md)
* [Conventions](conventions.md)
* [Servo](servo.md)

@@@

# Spectator

Simple library for instrumenting code to record dimensional time series. If
you are new to the library it is highly recommended to read the pages in the
*Getting Started* section on the sidebar.

At a minimum you will need to:

1. Depend on the api library. It is in maven central, for gradle the dependency
   would be `com.netflix.spectator:spectator-api:0.62.0`.
2. Instrument some code, see the usage guides for [counters](intro/counter.md),
   [timers](intro/timer.md), and [gauges](intro/gauge.md).
3. Pick a registry to bind to when initializing the application. See the sidebar
   for a list of available registries.


