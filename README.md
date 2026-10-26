# PulseCast

Real-time messaging library and interactive message-flow visualizer built with ASP.NET Core SignalR and Angular.

## Vision

PulseCast helps developers understand how real-time messages travel from a publisher to connected clients through an interactive, event-driven visualizer.

## Planned Features

- Admin-triggered real-time message broadcasting
- Live visualization of message flow
- Code explorer linked to actual runtime events
- Connected client monitoring
- Message payload and event inspection
- Delivery acknowledgements and latency tracking
- Reusable .NET messaging library
- Automated testing and CI

## Technology Stack

- ASP.NET Core
- SignalR
- Angular
- TypeScript
- C#
- PostgreSQL (planned)

## Engineering Principles

- Visualized events must correspond to actual application events.
- Published, received, acknowledged, and failed messages must be distinguished.
- Features should be implemented in small, tested increments.
- The reusable library should remain separate from the demonstration application.

## Project Status

Early development. Features will be implemented and verified incrementally.

PulseCast is an experimental developer tool and is not yet intended for production use.
