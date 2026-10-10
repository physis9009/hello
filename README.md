# hello

A small Rust HTTP server built with `std`, with a basic thread pool.

## Run

```sh
cargo run
```

Open `http://127.0.0.1:7878`. The server handles two requests and then shuts down.

- `/` serves `hello.html`.
- `/sleep` serves the same page after a five-second delay.
- Other paths serve `404.html`.