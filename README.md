# EnergyMon Rust Wrappers

The `energymon` crate provides some abstractions over the `energymon-sys`
crate, available at
[https://github.com/energymon/energymon-sys](https://github.com/energymon/energymon-sys).

## Dependencies

The `energymon` crate depends on the `energymon-sys` crate.

Additionally, you should have the native `energymon` libraries installed to the
system.

The latest `EnergyMon` C libraries can be found at
[https://github.com/energymon/energymon](https://github.com/energymon/energymon).

## Usage
Add `energymon` as a dependency in `Cargo.toml`:

```toml
[dependencies.energymon]
git = "https://github.com/energymon/energymon-rust.git"
```

## Project Source

Find this and related project sources at the [energymon organization on GitHub](https://github.com/energymon).  
This project originates at: https://github.com/energymon/energymon-rust

Bug reports and pull requests for new implementations, bug fixes, and enhancements are welcome.

## License

Licensed under either of

 * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in the work by you, as defined in the Apache-2.0
license, shall be dual licensed as above, without any additional terms or
conditions.
