# Using vcpkg as C++ dependency manager

## Install vcpkg

Follow steps [here](https://vcpkg.io/en/getting-started).

The bootstrap script will create binary in the vcpkg repo folder. I have added
symbolic link the binary to `/usr/bin` as well.

## Initialize project

```
vcpkg new --application
```

## Add dependency

Let us add `fmt` formatting library as an example:

```
vcpkg add port fmt
```

## Set up and build

Follow instructions [here](https://learn.microsoft.com/en-us/vcpkg/get_started/get-started?pivots=shell-cmd).
