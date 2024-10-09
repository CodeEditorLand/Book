# Installation

You can install `swc` via

```
npm i -D swc
```

or

```
yarn add --dev swc
```

This will download prebuilt binary instead of building swc if possible.
Currently prebuilt binaries are provided only for `mac (x64)` / `linux (x86_64)`
and for some of node js versions (6, 8, 10, 11).

To use swc in other environment, you should install nightly version of
[rust](https://www.rust-lang.org/) first. It can be done with

```
curl https://sh.rustup.rs -sSf | sh -s -- --default-toolchain=nightly
```

If you are using windows, please go to [rustup.rs](https://rustup.rs).

After installing rust, you can install swc via npm / yarn.
