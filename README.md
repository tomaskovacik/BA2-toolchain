# Build instructions

## Requirements

* clang (`sudo apt install clang`)
* autoconf (`sudo apt install autoconf`)
* libpython3 (`sudo apt install libpython3-dev`)
* libftdi (`sudo apt install libftdi-dev`)

## Build

```
mkdir -p /opt/toolchains/ba-elf
CC=clang ./Build.sh /opt/toolchains/ba-elf
export PATH=/opt/toolchains/ba-elf/bin:$PATH
```

Add the last line to your `.bashrc` or wherever you set your `PATH`, to enable the use of the toolchain in the future.
