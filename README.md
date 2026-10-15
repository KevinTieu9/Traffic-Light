# Traffic Light

**Author:** Kevin Tieu

## Overview

A red-yellow-green traffic light implemented as a finite state machine in Java, with JUnit tests that verify state transitions and timing behavior.

## What the Program Does

`TrafficLight` holds the current color and advances on a timer or on an explicit signal. Tests check that the light moves red → green → yellow → red and that timing rules are respected.

## Files

| File | Description |
|------|-------------|
| `TrafficLight.java` | State machine |
| `Main.java` | Driver |
| `TrafficLightTest.java` | JUnit tests |

## Techniques

- Finite state machine
- JUnit testing
- State transitions

## Build and Test

```bash
mvn test
```
