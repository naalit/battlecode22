# [Compilers] Battlecode 2022 Players

This is the main repository for all the code I wrote for Battlecode 2022. It's written in [ByteC](https://github.com/tolziplohu/bytec), which looks for the most part like Rust-lite.

## Structure

- `bytec` - this is the directory that all ByteC source files go in; it would be called `src`, but that must be the output directory because it's hardcoded into the Battlecode engine.
    - `common` - these modules are shared between bots
    - `bytemaster` - this is the newest bot and the most interesting
    - `bytecoder` - this is the bot I used up until sprint 2, it doesn't actually compile anymore because the Paths API changed
- `src` - output Java files must go in this directory to be seen by the Battlecode client, there's no actual code here
