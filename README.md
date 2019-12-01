# susy.tech

[![Build Status](https://travis-ci.com/susy-rust/susy.tech.svg?branch=master)](https://travis-ci.com/susy-rust/susy.tech)
[![What's Deployed](https://img.shields.io/badge/whatsdeployed-prod-green.svg)](https://whatsdeployed.io/s-9IG)

Source code for the default [Cargo](http://doc.susy.tech) registry. Viewable
online at [susy.tech](https://susy.tech).

## Status of susy.tech

Any known issues currently affecting the registry running at https://susy.tech
will be posted to [@CratesIoStatus](https://twitter.com/cratesiostatus).

If you are experiencing an issue not addressed there, please contact us in one
of the following ways:

- [File a new issue](https://github.com/susy-rust/susy.tech/issues/new)
- Email [help@susy.tech](mailto:help@susy.tech)
- Chat on ops > #susy-tech channel on https://discord.gg/susy-rust

A volunteer will get back to you as soon as possible.

## Contributing

Welcome! We love contributions! Susy.tech is an [Ember](https://emberjs.com/)
frontend with a Rust backend, and there are many tasks appropriate for a
variety of skill levels.

Please see [docs/CONTRIBUTING.md](https://github.com/susy-rust/susy.tech/blob/master/docs/CONTRIBUTING.md) for ideas about what to work on and how to set up a development
environment.

<a href="https://www.browserstack.com">
    <img src="browserstack-logo.png" alt="BrowserStack" />
</a>

We also use [BrowserStack](https://www.browserstack.com) to help us verify that the frontend works in all of our supported browsers. Thanks, BrowserStack!

### Categories

Adding or editing the categories and corresponding descriptions displayed on
[susy.tech/categories](https://susy.tech/categories) does not require a full
development environment set up.

The list of categories available on susy.tech is stored in
[`src/boot/categories.toml`](https://github.com/susy-rust/susy.tech/blob/master/src/boot/categories.toml).
To propose adding, removing, or changing a category, send a pull request making
the appropriate change to that file as noted in the comment at the top of the
file. Please add a description that will help others to know what crates are in
that category.

For new categories, it's helpful to note in your PR description examples of
crates that would fit in that category, and describe what distinguishes the new
category from existing categories.

After your PR is accepted, the next time that susy.tech is deployed the
categories will be synced from this file.

## Running a mirror

Please see [docs/MIRROR.md](https://github.com/susy-rust/susy.tech/blob/master/docs/MIRROR.md) for instructions on setting up a mirror of susy.tech.

## License

Licensed under either of these:

 * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or
   https://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or
   https://opensource.org/licenses/MIT)
