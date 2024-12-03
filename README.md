A gstreamer plugin utilizing [moq-rs](https://github.com/kixelated/moq-rs).

# Usage
Check out the `dev/pub` script for an example pipeline.

```bash
./dev/pub
```

By default this uses a localhost relay.
You can change the ENV args if you want to make it watchable on production instead:

```bash
ADDR=relay.quic.video NAME=something ./dev/pub
```

# License

Licensed under either:

-   Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
-   MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)
