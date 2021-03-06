---
title: kotlinx-coroutines
layout: api
---

# kotlinx.coroutines reference documentation

Library support for Kotlin coroutines. This reference is a companion to 
[Guide to kotlinx.coroutines by example](https://github.com/Kotlin/kotlinx.coroutines/blob/master/coroutines-guide.md).

## Modules

| Name                                                                 | Description                                      |
| ----------------------------------------------------------           | ------------------------------------------------ |
| [kotlinx-coroutines-core](kotlinx-coroutines-core)                   | Core primitives to work with coroutines          |
| [kotlinx-coroutines-debug](kotlinx-coroutines-debug)                 | Debugging utilities for coroutines               |
| [kotlinx-coroutines-test](kotlinx-coroutines-test)                   | Test primitives for coroutines, `Main` dispatcher injection         |
| [kotlinx-coroutines-reactive](kotlinx-coroutines-reactive)           | Utilities for [Reactive Streams](https://www.reactive-streams.org) |
| [kotlinx-coroutines-reactor](kotlinx-coroutines-reactor)             | Utilities for [Reactor](https://projectreactor.io) |
| [kotlinx-coroutines-rx2](kotlinx-coroutines-rx2)                     | Utilities for [RxJava 2.x](https://github.com/ReactiveX/RxJava) |
| [kotlinx-coroutines-android](kotlinx-coroutines-android)             | `Main` dispatcher for Android applications |
| [kotlinx-coroutines-javafx](kotlinx-coroutines-javafx)               | `JavaFx` dispatcher for JavaFX UI applications |
| [kotlinx-coroutines-swing](kotlinx-coroutines-swing)                 | `Swing` dispatcher for Swing UI applications |
| [kotlinx-coroutines-jdk8](kotlinx-coroutines-jdk8)                   | Integration with JDK8 `CompletableFuture` (Android API level 24) |
| [kotlinx-coroutines-guava](kotlinx-coroutines-guava)                 | Integration with Guava [ListenableFuture](https://github.com/google/guava/wiki/ListenableFutureExplained) |
| [kotlinx-coroutines-slf4j](kotlinx-coroutines-slf4j)                 | Integration with SLF4J [MDC](https://logback.qos.ch/manual/mdc.html) |
| [kotlinx-coroutines-play-services](kotlinx-coroutines-play-services) | Integration with Google Play Services [Tasks API](https://developers.google.com/android/guides/tasks) |

## Examples

* [example-frontend-js](example-frontend-js/index.html) -- frontend application written in Kotlin/JS
that uses coroutines to implement animations in imperative style.
