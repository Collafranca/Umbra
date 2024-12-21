<p align="center">
  <img src="./banner.png" alt="Umbra Disassembler Banner" width="500px" height=auto>
</p>

<h1 align="center">Umbra Disassembler & Decompiler</h1>

This project is a result of countless hours of hard work and development. We ask that you do not claim this project as your own, and give credit where it is due.

> **Note:** This project is licensed under the GNU General Public License v3.0.

If you'd like to compile your script, please refer to the `/compile` directory.

## Debug Mode

Turning on the `DEBUG` flag will slow down the decompilation process significantly.
- **Performance Impact:** 0.000406s -> 0.002075s, around 5x slower

The `DEBUG` flag is meant for development purposes only. Turn off before using in production.

## Issues

- Makes everything a proto even if it isn't
  
- ~~Does not show jump targets (e.g., if code has `goto [5]` but only has 3 instructions, it doesn't show `::5::` and its dism)~~ (Fixed)
-> May cause some complications though

- Decompile is broken/really bad/unfinished
- No type checking
- Does not handle variables kindly

Please contribute and fix these bugs and more that you may find
