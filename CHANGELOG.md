# Change Log

## [0.2.5](https://github.com/inaka/erlang-katana/tree/0.2.5) (2015-04-13)

[Full Changelog](https://github.com/inaka/erlang-katana/compare/0.2.4...0.2.5)

**Fixed bugs:**

- ktn\_date:now\_human\_readable should pad [\#39](https://github.com/inaka/erlang-katana/issues/39)

**Merged pull requests:**

- Version bump [\#42](https://github.com/inaka/erlang-katana/pull/42) ([igaray](https://github.com/igaray))

- Test utilities for REST APIs [\#41](https://github.com/inaka/erlang-katana/pull/41) ([igaray](https://github.com/igaray))

- \[\#39\] Add padding to month and day in human readable date format [\#40](https://github.com/inaka/erlang-katana/pull/40) ([jfacorro](https://github.com/jfacorro))

- \[\#35\] Update changelog. [\#38](https://github.com/inaka/erlang-katana/pull/38) ([jfacorro](https://github.com/jfacorro))

## [0.2.4](https://github.com/inaka/erlang-katana/tree/0.2.4) (2015-03-20)

[Full Changelog](https://github.com/inaka/erlang-katana/compare/0.2.3...0.2.4)

**Closed issues:**

- Move `types` in `spec` node from `content` to `node\_attrs`  [\#35](https://github.com/inaka/erlang-katana/issues/35)

- Bump version to 0.2.3 [\#32](https://github.com/inaka/erlang-katana/issues/32)

**Merged pull requests:**

- \[\#35\] Bump version. [\#37](https://github.com/inaka/erlang-katana/pull/37) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#35\] Moved `types` to `node\_attrs`. [\#36](https://github.com/inaka/erlang-katana/pull/36) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#32\] Updated changelog. [\#34](https://github.com/inaka/erlang-katana/pull/34) ([jfacorro](https://github.com/jfacorro))

## [0.2.3](https://github.com/inaka/erlang-katana/tree/0.2.3) (2015-03-19)

[Full Changelog](https://github.com/inaka/erlang-katana/compare/0.2.2...0.2.3)

**Implemented enhancements:**

- Add a ktn\_code:consult/1 function that behaves the same as file:consult/1 but for strings and binaries  [\#24](https://github.com/inaka/erlang-katana/issues/24)

**Fixed bugs:**

- ktn\_code:consult/1 can't handle "{'.'}.\n" [\#26](https://github.com/inaka/erlang-katana/issues/26)

**Closed issues:**

- ktn\_code: separate attrs that are values from the ones that are nodes [\#30](https://github.com/inaka/erlang-katana/issues/30)

- Add ktn\_code:beam\_to\_string/1 [\#28](https://github.com/inaka/erlang-katana/issues/28)

**Merged pull requests:**

- \[\#32\] Version bump. Added change log. [\#33](https://github.com/inaka/erlang-katana/pull/33) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#30\] Separate attrs that are nodes form the ones that are not [\#31](https://github.com/inaka/erlang-katana/pull/31) ([jfacorro](https://github.com/jfacorro))

- \[Closes \#28\] Beam to string. [\#29](https://github.com/inaka/erlang-katana/pull/29) ([jfacorro](https://github.com/jfacorro))

## [0.2.2](https://github.com/inaka/erlang-katana/tree/0.2.2) (2015-02-13)

[Full Changelog](https://github.com/inaka/erlang-katana/compare/0.2.1...0.2.2)

**Merged pull requests:**

- \[\#26\] Fixed bug. [\#27](https://github.com/inaka/erlang-katana/pull/27) ([jfacorro](https://github.com/jfacorro))

## [0.2.1](https://github.com/inaka/erlang-katana/tree/0.2.1) (2015-02-13)

[Full Changelog](https://github.com/inaka/erlang-katana/compare/0.2.0...0.2.1)

**Fixed bugs:**

- user\_default conflicts [\#19](https://github.com/inaka/erlang-katana/issues/19)

**Closed issues:**

- Add ktn\_binary:join/2 [\#21](https://github.com/inaka/erlang-katana/issues/21)

**Merged pull requests:**

- \[\#24\] Added ktn\_code:consult/1 and moved split\_when/2 to ktn\_lists. [\#25](https://github.com/inaka/erlang-katana/pull/25) ([jfacorro](https://github.com/jfacorro))

- added ktn\_lists:delete\_first/2 [\#23](https://github.com/inaka/erlang-katana/pull/23) ([amilkr](https://github.com/amilkr))

- ktn\_binary:join/2 [\#22](https://github.com/inaka/erlang-katana/pull/22) ([amilkr](https://github.com/amilkr))

- \[Closes \#19\] Renamed user\_default.erl to avoid conflict [\#20](https://github.com/inaka/erlang-katana/pull/20) ([igaray](https://github.com/igaray))

- Update from upstream [\#18](https://github.com/inaka/erlang-katana/pull/18) ([elbrujohalcon](https://github.com/elbrujohalcon))

## [0.2.0](https://github.com/inaka/erlang-katana/tree/0.2.0) (2014-10-22)

[Full Changelog](https://github.com/inaka/erlang-katana/compare/0.1.0...0.2.0)

**Implemented enhancements:**

- Add current functionality from elvis\_code to ktn\_code [\#16](https://github.com/inaka/erlang-katana/issues/16)

**Merged pull requests:**

- \[Closes \#16\] Added parsing code form elvis\_code [\#17](https://github.com/inaka/erlang-katana/pull/17) ([jfacorro](https://github.com/jfacorro))

- New stuff from @unbalancedparentheses [\#14](https://github.com/inaka/erlang-katana/pull/14) ([elbrujohalcon](https://github.com/elbrujohalcon))

## [0.1.0](https://github.com/inaka/erlang-katana/tree/0.1.0) (2014-09-01)

**Implemented enhancements:**

- Rename modules from katana to ktn [\#3](https://github.com/inaka/erlang-katana/issues/3)

**Fixed bugs:**

- Make katana releasable [\#8](https://github.com/inaka/erlang-katana/issues/8)

- Syntax error in katana.app.src [\#5](https://github.com/inaka/erlang-katana/issues/5)

**Closed issues:**

- Create katana\_maps for maps utility functions [\#1](https://github.com/inaka/erlang-katana/issues/1)

**Merged pull requests:**

- Igaray.recipe [\#13](https://github.com/inaka/erlang-katana/pull/13) ([igaray](https://github.com/igaray))

- Igaray.recipe [\#12](https://github.com/inaka/erlang-katana/pull/12) ([igaray](https://github.com/igaray))

- Created ktn\_numbers module. [\#10](https://github.com/inaka/erlang-katana/pull/10) ([jfacorro](https://github.com/jfacorro))

- \[\#8\] Make katana releasable. [\#9](https://github.com/inaka/erlang-katana/pull/9) ([jfacorro](https://github.com/jfacorro))

- Added Microsends and resolved name bug [\#7](https://github.com/inaka/erlang-katana/pull/7) ([unbalancedparentheses](https://github.com/unbalancedparentheses))

- \[\#5\] Fixed syntax error. [\#6](https://github.com/inaka/erlang-katana/pull/6) ([jfacorro](https://github.com/jfacorro))

- \[\#3\] Renamed modules. [\#4](https://github.com/inaka/erlang-katana/pull/4) ([jfacorro](https://github.com/jfacorro))

- \[\#1\] get/\[2,3\] nested maps.  [\#2](https://github.com/inaka/erlang-katana/pull/2) ([jfacorro](https://github.com/jfacorro))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*