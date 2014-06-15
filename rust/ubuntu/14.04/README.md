# Building Rust from Source

Make sure you have the following dependencies installed:
* g++ 4.7 or clang++ 3.x
* python 2.6 or later (but not 3.x)
* perl 5.0 or later
* GNU make 3.81 or later
* curl
* git

## Getting the Source

### From Git
```
git clone https://github.com/mozilla/rust.git
cd rust
```

### From Nightly Build
```
curl -O http://static.rust-lang.org/dist/rust-nightly.tar.gz
tar -xzf rust-nightly.tar.gz
cd rust-nightly
```

## Installing
```
./configure
make && sudo make install
```
