# Easy-XXHash64

[![dependency status](https://deps.rs/repo/github/arma3modorganizer/easy_xxhash64/status.svg)](https://deps.rs/repo/github/arma3modorganizer/easy_xxhash64)
[![Travis CI](https://travis-ci.org/arma3modorganizer/easy_xxhash64.svg?branch=master)](https://travis-ci.org/arma3modorganizer/easy_xxhash64)
[![Build status](https://ci.appveyor.com/api/projects/status/d39clo2lta1qbv08?svg=true)](https://ci.appveyor.com/project/Scarjit/easy_xxhash64)
[![Crates.io](https://img.shields.io/crates/v/easy_xxhash64)](https://crates.io/crates/easy_xxhash64)
[![License MIT](https://img.shields.io/badge/license-Apache-blue.svg)](https://github.com/arma3modorganizer/easy_xxhash64/blob/master/LICENSE)
[![Coverage Status](https://coveralls.io/repos/github/arma3modorganizer/easy_xxhash64/badge.svg?branch=master)](https://coveralls.io/github/arma3modorganizer/easy_xxhash64?branch=master)

Easy to use crypto libary for xxHash64, based on [rust-fasthash](https://github.com/flier/rust-fasthash)
## Usage
 - file_hash.rs provides the following api's:
   - hash_path : `&str -> Result<u64, CryptoError)`.
     - Wraps IOError into CryptoError.
   - hash_byte_vec provides `Vec<u8> -> u64`.
 
 ## Licenses
 ### [EasyXXHash64](https://github.com/arma3modorganizer/EasyXXHash64)
EasyXXHash64 is developed under [Apache 2.0 License](https://github.com/arma3modorganizer/EasyXXHash64/LICENSE).