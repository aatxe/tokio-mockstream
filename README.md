# tokio-mockstream [![Build Status](https://travis-ci.org/aatxe/tokio-mockstream.svg?branch=master)](https://travis-ci.org/aatxe/tokio-mockstream) [![Crates.io](https://img.shields.io/crates/v/tokio-mockstream.svg)](https://crates.io/crates/tokio-mockstream) [![Built with Spacemacs](https://cdn.rawgit.com/syl20bnr/spacemacs/442d025779da2f62fc86c2082703697714db6514/assets/spacemacs-badge.svg)](http://spacemacs.org) #

A fake stream for testing network applications backed by buffers.

# Usage

```toml
[dependencies]
tokio-mockstream = "1.0"
```

Next, add this to your crate:

```rust
extern crate tokio_mockstream;

use tokio_mockstream::MockStream;
```

The general idea is to treat `MockStream` as you would `TcpStream`. You can find documentation online at [docs.rs](https://docs.rs/tokio-mockstream/).

# License

`tokio-mockstream` is primarily distributed under the terms of both the MIT license
and the Apache License (Version 2.0).

See LICENSE-APACHE, and LICENSE-MIT for details.
