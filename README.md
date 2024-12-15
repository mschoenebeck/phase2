# phase2 (0.3.0) #

This library is an update of [ebfull/phase2](https://github.com/ebfull/phase2) for compatibility with [bellman](https://crates.io/crates/bellman) `0.14`. The original library only supports arithmetic circuits based on bellman `0.1`.

You need to download the phase 1 (aka. 'Powers of Tau') parameter files in order to start a phase 2 MPC. The 'Powers of Tau' files are available via torrent at this magnet link: `magnet:?xt=urn:btih:c3f316242ff3f4c2ec5f8cbfc27ae2ca2b599146&dn=powersoftau&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce`

New benchmarks (bellman `0.14`):
```
Average proving time: 0.350451457 seconds
Average verifying time: 0.02944406 seconds
```

Old benchmarks (bellman `0.1`):
```
Average proving time: 1.023841092 seconds
Average verifying time: 0.164473211 seconds
```

## [Documentation](https://docs.rs/phase2/)
## [![Crates.io](https://img.shields.io/crates/v/phase2.svg)](https://crates.io/crates/phase2)

## Security Warnings

This library does not make any guarantees about constant-time operations, memory access patterns, or resistance to side-channel attacks.

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
