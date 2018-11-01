# Rust异步编程

- [Getting Started](getting_started/chapter.md)
  - [Why Async?](getting_started/why_async.md)
  - [`async`/`await!` Primer](getting_started/async_await_primer.md)
  - [Applied: HTTP Server](getting_started/http_server_example.md)
- [Under the Hood: Executing `Future`s and Tasks](execution/chapter.md)
  - [The `Future` Trait](execution/future.md)
  - [Task Wakeups with `LocalWaker` and `Waker`](execution/wakeups.md)
    - [Applied: Build a Timer](execution/wakeups.md)
  - [Applied: Build an Executor](execution/executor.md)
- [`async`/`await`](...)
  - [What and Why](...)
  - [`async` Blocks, Closures, and Functions](...)
  - [Cancellation and Timeouts](...)
  - [Applied: XXX](...)
- [Pinning](pinning/chapter.md)
- [Streams](...)
  - [Patterns: Iteration and Concurrency](...)
- [Executing Multiple Futures at a Time](...)
  - [`select!` and `join!`](...)
  - [Spawning](...)
  - [`FuturesUnordered`](...)
- [I/O](...)
  - [`AsyncRead` and `AsyncWrite`](...)
- [Asynchronous Design Patterns: Solutions and Suggestions](...)
  - [Modeling Servers and the Request/Response Pattern](...)
  - [Managing Shared State](...)
- [The Ecosystem: Tokio and More](...)
  - Lots, lots more?...