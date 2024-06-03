# Ziglings

Welcome to Ziglings! This project contains a series of tiny
broken programs (and one nasty surprise).  By fixing them, you'll
learn how to read and write [Zig](https://ziglang.org/) code.

![Ziglings](images/ziglings.jpg "Ziglings")

Those broken programs need your help! (You'll also save the
planet from evil aliens and help some friendly elephants stick
together, which is very sweet of you.)

This project was directly inspired by the brilliant and fun
[rustlings](https://github.com/rust-lang/rustlings)
project for the [Rust](https://www.rust-lang.org/) language.
Indirect inspiration comes from [Ruby Koans](http://rubykoans.com/)
and the Little LISPer/Little Schemer series of books.

## Progress
- [X] 001\_hello.zig
- [X] 002\_std.zig
- [X] 003\_assignment.zig
- [X] 004\_arrays.zig
- [X] 005\_arrays2.zig
- [X] 006\_strings.zig
- [X] 007\_strings2.zig
- [X] 008\_quiz.zig
- [X] 009\_if.zig
- [X] 010\_if2.zig
- [X] 011\_while.zig
- [X] 012\_while2.zig
- [X] 013\_while3.zig
- [X] 014\_while4.zig
- [X] 015\_for.zig
- [X] 016\_for2.zig
- [X] 017\_quiz2.zig
- [X] 018\_functions.zig
- [X] 019\_functions2.zig
- [X] 020\_quiz3.zig
- [X] 021\_errors.zig
- [X] 022\_errors2.zig
- [X] 023\_errors3.zig
- [X] 024\_errors4.zig
- [X] 025\_errors5.zig
- [X] 026\_hello2.zig
- [X] 027\_defer.zig
- [X] 028\_defer2.zig
- [X] 029\_errdefer.zig
- [X] 030\_switch.zig
- [X] 031\_switch2.zig
- [X] 032\_unreachable.zig
- [X] 033\_iferror.zig
- [X] 034\_quiz4.zig
- [X] 035\_enums.zig
- [X] 036\_enums2.zig
- [X] 037\_structs.zig
- [X] 038\_structs2.zig
- [X] 039\_pointers.zig
- [X] 040\_pointers2.zig
- [X] 041\_pointers3.zig
- [X] 042\_pointers4.zig
- [X] 043\_pointers5.zig
- [X] 044\_quiz5.zig
- [X] 045\_optionals.zig
- [X] 046\_optionals2.zig
- [X] 047\_methods.zig
- [X] 048\_methods2.zig
- [X] 049\_quiz6.zig
- [X] 050\_no\_value.zig
- [X] 051\_values.zig
- [X] 052\_slices.zig
- [X] 053\_slices2.zig
- [X] 054\_manypointers.zig
- [X] 055\_unions.zig
- [X] 056\_unions2.zig
- [X] 057\_unions3.zig
- [X] 058\_quiz7.zig
- [X] 059\_integers.zig
- [X] 060\_floats.zig
- [X] 061\_coercions.zig
- [X] 062\_loop\_expressions.zig
- [X] 063\_labels.zig
- [ ] 064\_builtins.zig
- [ ] 065\_builtins2.zig
- [ ] 066\_comptime.zig
- [ ] 067\_comptime2.zig
- [ ] 068\_comptime3.zig
- [ ] 069\_comptime4.zig
- [ ] 070\_comptime5.zig
- [ ] 071\_comptime6.zig
- [ ] 072\_comptime7.zig
- [ ] 073\_comptime8.zig
- [ ] 074\_comptime9.zig
- [ ] 075\_quiz8.zig
- [ ] 076\_sentinels.zig
- [ ] 077\_sentinels2.zig
- [ ] 078\_sentinels3.zig
- [ ] 079\_quoted\_identifiers.zig
- [ ] 080\_anonymous\_structs.zig
- [ ] 081\_anonymous\_structs2.zig
- [ ] 082\_anonymous\_structs3.zig
- [ ] 083\_anonymous\_lists.zig
- [ ] 084\_async.zig
- [ ] 085\_async2.zig
- [ ] 086\_async3.zig
- [ ] 087\_async4.zig
- [ ] 088\_async5.zig
- [ ] 089\_async6.zig
- [ ] 090\_async7.zig
- [ ] 091\_async8.zig
- [ ] 092\_interfaces.zig
- [ ] 093\_hello\_c.zig
- [ ] 094\_c\_math.zig
- [ ] 095\_for3.zig
- [ ] 096\_memory\_allocation.zig
- [ ] 097\_bit\_manipulation.zig
- [ ] 098\_bit\_manipulation2.zig
- [ ] 099\_formatting.zig
- [ ] 100\_for4.zig
- [ ] 101\_for5.zig
- [ ] 102\_testing.zig
- [ ] 103\_tokenization.zig
- [ ] 104\_threading.zig
- [ ] 105\_threading2.zig
- [ ] 106\_files.zig
- [ ] 107\_files2.zig
- [ ] 999\_the\_end.zig

## Intended Audience

This will probably be difficult if you've _never_ programmed
before.  But no specific programming experience is required. And
in particular, you are _not_ expected to have any prior
experience with "systems programming" or a "systems" level
language such as C.

Each exercise is self-contained and self-explained. However,
you're encouraged to also check out these Zig language resources
for more detail:

* https://ziglang.org/learn/
* https://ziglearn.org/
* https://ziglang.org/documentation/master/
* [Zig in Depth! (video series)](https://www.youtube.com/watch?v=MMtvGA1YhW4&list=PLtB7CL7EG7pCw7Xy1SQC53Gl8pI7aDg9t&pp=iAQB)

Also, the [Zig community](https://github.com/ziglang/zig/wiki/Community)
is incredibly friendly and helpful!

## Getting Started

Install a [development build](https://ziglang.org/download/) of
the Zig compiler.  (See the "master" section of the downloads
page.)

Verify the installation and build number of `zig` like so:

```
$ zig version
0.13.0-dev.xxxx+xxxxxxxxx
```

Clone this repository with Git:

```
$ git clone https://ziglings.org
$ cd ziglings.org
```

Then run `zig build` and follow the instructions to begin!

```
$ zig build
```

Note: The output of Ziglings is the unaltered output from the Zig
compiler. Part of the purpose of Ziglings is to acclimate you to
reading these.

## A Note About Versions

**Hint:** To check out Ziglings for a stable release of Zig, you can use
the appropriate tag. 

The Zig language is under very active development. In order to be
current, Ziglings tracks **development** builds of the Zig
compiler rather than versioned **release** builds. The last
stable release was `0.12.0`, but Ziglings needs a dev build with
pre-release version "0.13.0" and a build number at least as high
as that shown in the example version check above.

It is likely that you'll download a build which is _greater_ than
the minimum.

Once you have a build of the Zig compiler that works with
Ziglings, they'll continue to work together. But keep in mind
that if you update one, you may need to also update the other.


### Version Changes

Version-0.12.0-dev.3518
* *2024-03-21* zig 0.12.0-dev.3518 - change to @fieldParentPtr - see [#19470](https://github.com/ziglang/zig/pull/19470)
* *2024-03-21* zig 0.12.0-dev.3397 - rename std.os to std.posix - see [#5019](https://github.com/ziglang/zig/issues/5019)
* *2024-03-14* zig 0.12.0-dev.3302 - changes in `std.fmt` - floating-point formatting implementation - see [#19229](https://github.com/ziglang/zig/pull/19229)
* *2024-02-05* zig 0.12.0-dev.2618 - changes in `build system` - from `Step.zig_exe` to `Step.graph.zig_exe` - see [#18778](https://github.com/ziglang/zig/issues/18778)
* *2024-01-05* zig 0.12.0-dev.2043 - rename of `std.Build.FileSource` to `std.Build.LazyPath` - see [#16353](https://github.com/ziglang/zig/issues/16353)
* *2023-10-24* zig 0.12.0-dev.1243 - changes in `std.ChildProcess`: renamed exec to run - see [#5853](https://github.com/ziglang/zig/issues/5853)
* *2023-06-26* zig 0.11.0-dev.4246 - changes in compile step (now it can be null)
* *2023-06-26* zig 0.11.0-dev.3853 - removal of destination type from all cast builtins
* *2023-06-20* zig 0.11.0-dev.3747 - `@enumToInt` is now `@intFromEnum` and `@intToFloat` is now `@floatFromInt`
* *2023-05-25* zig 0.11.0-dev.3295 - `std.debug.TTY` is now `std.io.tty`
* *2023-04-30* zig 0.11.0-dev.2704 - use of the new `std.Build.ExecutableOptions.link_libc` field
* *2023-04-12* zig 0.11.0-dev.2560 - changes in `std.Build` - remove run() and install()
* *2023-04-07* zig 0.11.0-dev.2401 - fixes of the new build system - see [#212](https://github.com/ratfactor/ziglings/pull/212)
* *2023-02-21* zig 0.11.0-dev.2157 - changes in `build system` - new: parallel processing of the build steps
* *2023-02-21* zig 0.11.0-dev.1711 - changes in `for loops` - new: Multi-Object For-Loops + Struct-of-Arrays
* *2023-02-12* zig 0.11.0-dev.1638 - changes in `std.Build` cache_root now returns a directory struct
* *2023-02-04* zig 0.11.0-dev.1568 - changes in `std.Build` (combine `std.build` and `std.build.Builder` into `std.Build`)
* *2023-01-14* zig 0.11.0-dev.1302 - changes in `@addWithOverflow` (now returns a tuple) and `@typeInfo`; temporary disabled async functionality
* *2022-09-09* zig 0.10.0-dev.3978 - change in `NativeTargetInfo.detect` in build
* *2022-09-06* zig 0.10.0-dev.3880 - Ex 074 correctly fails again: comptime array len
* *2022-08-29* zig 0.10.0-dev.3685 - `@typeName()` output change, stage1 req. for async
* *2022-07-31* zig 0.10.0-dev.3385 - std lib string `fmt()` option changes
* *2022-03-19* zig 0.10.0-dev.1427 - method for getting sentinel of type changed
* *2021-12-20* zig 0.9.0-dev.2025 - `c_void` is now `anyopaque`
* *2021-06-14* zig 0.9.0-dev.137  - std.build.Id `.Custom` is now `.custom`
* *2021-04-21* zig 0.8.0-dev.1983 - std.fmt.format() `any` format string required
* *2021-02-12* zig 0.8.0-dev.1065 - std.fmt.format() `s` (string) format string required

## Advanced Usage

It can be handy to check just a single exercise:

```
zig build -Dn=19
```

You can also run without checking for correctness:

```
zig build -Dn=19 test
```

Or skip the build system entirely and interact directly with the
compiler if you're into that sort of thing:

```
zig run exercises/001_hello.zig
```

Calling all wizards: To prepare an executable for debugging,
install it to zig-cache/bin with:

```
zig build -Dn=19 install
```

To get a list of all possible options, run:

```
zig build -Dn=19 -l

  install          Install 019_functions2.zig to prefix path
  uninstall        Uninstall 019_functions2.zig from prefix path
  test             Run 019_functions2.zig without checking output
  ...
```

## What's Covered

The primary goal for Ziglings is to cover the core Zig language.

It would be nice to cover the Standard Library as well, but this
is currently challenging because the stdlib is evolving even
faster than the core language (and that's saying something!).
Not only would stdlib coverage change very rapidly, some
exercises might even cease to be relevant entirely.

Having said that, there are some stdlib features that are
probably here to stay or are so important to understand that they
are worth the extra effort to keep current.

Conspicuously absent from Ziglings are a lot of string
manipulation exercises. This is because Zig itself largely avoids
dealing with strings. Hopefully there will be an obvious way to
address this in the future. The Ziglings crew loves strings!

Zig Core Language

* [x] Hello world (main needs to be public)
* [x] Importing standard library
* [x] Assignment
* [x] Arrays
* [x] Strings
* [x] If
* [x] While
* [x] For
* [x] Functions
* [x] Errors (error/try/catch/if-else-err)
* [x] Defer (and errdefer)
* [x] Switch
* [x] Unreachable
* [x] Enums
* [x] Structs
* [x] Pointers
* [x] Optionals
* [x] Struct methods
* [x] Slices
* [x] Many-item pointers
* [x] Unions
* [x] Numeric types (integers, floats)
* [x] Labelled blocks and loops
* [x] Loops as expressions
* [x] Builtins
* [x] Inline loops
* [x] Comptime
* [x] Sentinel termination
* [x] Quoted identifiers @""
* [x] Anonymous structs/tuples/lists
* [ ] Async <--- ironically awaiting upstream Zig updates
* [X] Interfaces
* [X] Bit manipulation
* [X] Working with C
* [X] Threading

Zig Standard Library

* [X] String formatting
* [X] Testing
* [X] Tokenization
* [X] File handling

## Contributing

Contributions are very welcome! I'm writing this to teach myself
and to create the learning resource I wished for. There will be
tons of room for improvement:

* Wording of explanations
* Idiomatic usage of Zig
* Additional exercises

Please see [CONTRIBUTING](https://codeberg.org/ziglings/exercises/src/branch/main/CONTRIBUTING.md)
in this repo for the full details.
