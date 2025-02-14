# Change log

All notable changes to this project will be documented in this file. The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org).

## [v8.4.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v8.4.0) (2022-07-21)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/v8.3.0...v8.4.0)

### Added

- deferrable epp function simplifying deferred templates [\#1253](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1253) ([binford2k](https://github.com/binford2k))

## [v8.3.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v8.3.0) (2022-07-11)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/v8.2.0...v8.3.0)

### Added

- pdksync - \(GH-cat-12\) Add Support for Redhat 9 [\#1247](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1247) ([david22swan](https://github.com/david22swan))
- Convert `ensure_packages` to new API and refactor [\#1244](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1244) ([alexjfisher](https://github.com/alexjfisher))

### Fixed

- \(MODULES-2892\) Handle missing file in file\_line [\#1251](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1251) ([silug](https://github.com/silug))
- Simplify stdlib::manage [\#1250](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1250) ([jcpunk](https://github.com/jcpunk))
- Unbreak `rake strings:generate:reference` [\#1239](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1239) ([smortex](https://github.com/smortex))
- loadjson: do not send http\_basic\_authentication if not needed [\#1208](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1208) ([chaen](https://github.com/chaen))

## [v8.2.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v8.2.0) (2022-05-16)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/v8.1.0...v8.2.0)

### Added

- Add `xml_encode` function [\#1236](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1236) ([alexjfisher](https://github.com/alexjfisher))
- \(MODULES-4976\) Add windows escaping functions [\#1235](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1235) ([smortex](https://github.com/smortex))
- MODULES-11309 : convert a string to a resource [\#1233](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1233) ([jcpunk](https://github.com/jcpunk))
- pdksync - \(FM-8922\) - Add Support for Windows 2022 [\#1222](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1222) ([david22swan](https://github.com/david22swan))
- \(MODULES-11196\) Add support for AIX 7.2 [\#1220](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1220) ([david22swan](https://github.com/david22swan))
- pdksync - \(IAC-1753\) - Add Support for AlmaLinux 8 [\#1216](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1216) ([david22swan](https://github.com/david22swan))

### Fixed

- Update load\_module\_metadata.rb to correct capitalisation in strings documentartion [\#1241](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1241) ([davidsandilands](https://github.com/davidsandilands))
- Modernize escape functions [\#1238](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1238) ([smortex](https://github.com/smortex))
- Convert data to Pcore before serialisation in to\_ruby/to\_python [\#1237](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1237) ([smortex](https://github.com/smortex))
- \(maint\) Update str2saltedpbkdf2.rb to use the correct salt length [\#1232](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1232) ([AriaXLi](https://github.com/AriaXLi))
- Fix `to_yaml` `options` parameter [\#1231](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1231) ([alexjfisher](https://github.com/alexjfisher))
- pdksync - \(GH-iac-334\) Remove Support for Ubuntu 14.04/16.04 [\#1224](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1224) ([david22swan](https://github.com/david22swan))
- pdksync - \(IAC-1787\) Remove Support for CentOS 6 [\#1219](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1219) ([david22swan](https://github.com/david22swan))
- Fix serialization of undef in to\_python\(\) [\#1205](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1205) ([smortex](https://github.com/smortex))

## [v8.1.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v8.1.0) (2021-10-04)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/v8.0.0...v8.1.0)

### Added

- pdksync - \(IAC-1751\) - Add Support for Rocky 8 [\#1214](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1214) ([david22swan](https://github.com/david22swan))
- stdlib::ensure: Add support for package resource [\#1213](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1213) ([david-caro](https://github.com/david-caro))
- Added to\_toml function [\#1209](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1209) ([nmaludy](https://github.com/nmaludy))

### Fixed

- \[MODULES-11195\] Add lint-ignore for pattern length [\#1212](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1212) ([carabasdaniel](https://github.com/carabasdaniel))
- pdksync - \(IAC-1598\) - Remove Support for Debian 8 [\#1210](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1210) ([david22swan](https://github.com/david22swan))
- os\_version\_gte: fix version comparison logic [\#1207](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1207) ([kenyon](https://github.com/kenyon))
- max, lstrip: fix deprecated message [\#1204](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1204) ([b4ldr](https://github.com/b4ldr))
- \(MODULES-11126\) Replacing URI.escape with URI::DEFAULT\_PARSER [\#1195](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1195) ([valleedelisle](https://github.com/valleedelisle))

## [v8.0.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v8.0.0) (2021-08-24)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/v7.1.0...v8.0.0)

### Changed

- Flip installed and present in Function ensure\_packages [\#1196](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1196) ([cocker-cc](https://github.com/cocker-cc))

### Added

- New function to\_python\(\) / to\_ruby\(\) [\#1200](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1200) ([smortex](https://github.com/smortex))
- pdksync - \(IAC-1709\) - Add Support for Debian 11 [\#1199](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1199) ([david22swan](https://github.com/david22swan))
- Stdlib::Http::Method: Add new type for http methods [\#1192](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1192) ([b4ldr](https://github.com/b4ldr))

### Fixed

- \(MODULES-11099\) Make merge parameter data types actually backwards compatible [\#1191](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1191) ([SimonPe](https://github.com/SimonPe))

## [v7.1.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v7.1.0) (2021-05-17)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/v7.0.1...v7.1.0)

### Added

- pw\_hash: add support for bcrypt variants [\#1173](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1173) ([kjetilho](https://github.com/kjetilho))

## [v7.0.1](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v7.0.1) (2021-04-12)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/v7.0.0...v7.0.1)

### Fixed

- Fix typo in validate\_ipv6\_address function [\#1176](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1176) ([nbarrientos](https://github.com/nbarrientos))

## [v7.0.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v7.0.0) (2021-03-01)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/v6.6.0...v7.0.0)

### Changed

- pdksync - Remove Puppet 5 from testing and bump minimal version to 6.0.0 [\#1164](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1164) ([carabasdaniel](https://github.com/carabasdaniel))

### Added

- Stdlib::Email type [\#1160](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1160) ([b4ldr](https://github.com/b4ldr))

### Fixed

- \(bugfix\) Setting stricter email validation [\#1163](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1163) ([pmcmaw](https://github.com/pmcmaw))
- \(IAC-1414\) Throw error in range\(\) function when step size invalid [\#1161](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1161) ([sanfrancrisko](https://github.com/sanfrancrisko))

## [v6.6.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v6.6.0) (2021-02-02)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/v6.5.0...v6.6.0)

### Added

- stdlib::ensure: new fuction to cast ensure values [\#1150](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1150) ([b4ldr](https://github.com/b4ldr))
- \(feat\) Add support for Puppet 7 [\#1144](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1144) ([daianamezdrea](https://github.com/daianamezdrea))
- Allow options injection for to\_yaml [\#1137](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1137) ([baurmatt](https://github.com/baurmatt))
- Allow start/end checks on empty strings [\#1135](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1135) ([jvrsantacruz](https://github.com/jvrsantacruz))
- Stdlib::HttpStatus: add type for HTTP status codes as per rfc2616 [\#1132](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1132) ([b4ldr](https://github.com/b4ldr))

### Fixed

- \(IAC-1375\) fix unit tests for pe\_version fact, when using later facte… [\#1155](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1155) ([tphoney](https://github.com/tphoney))
- seeded\_rand: update funtion to ensure it returns an int not String [\#1139](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1139) ([b4ldr](https://github.com/b4ldr))

## [v6.5.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v6.5.0) (2020-09-30)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/v6.4.0...v6.5.0)

### Added

- Add parsehocon\(\) function [\#1130](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1130) ([reidmv](https://github.com/reidmv))
- Add new types for Stdlib::Ensure::File [\#1129](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1129) ([b4ldr](https://github.com/b4ldr))
- Add additional types Stdlib::Port::Dynamic,Ephemeral,Registered,User} [\#1128](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1128) ([b4ldr](https://github.com/b4ldr))
- Stdlib::Datasize: This CR adds a new data size type alias [\#1126](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1126) ([b4ldr](https://github.com/b4ldr))

## [v6.4.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v6.4.0) (2020-08-20)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/v6.3.0...v6.4.0)

### Added

- pdksync - \(IAC-973\) - Update travis/appveyor to run on new default branch `main` [\#1117](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1117) ([david22swan](https://github.com/david22swan))
- \(IAC-746\) - Add ubuntu 20.04 support [\#1110](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1110) ([david22swan](https://github.com/david22swan))

### Fixed

- \[MODULES-10781\] Fix defined type defined\_with\_params\(\) [\#1122](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1122) ([trevor-vaughan](https://github.com/trevor-vaughan))
- \[MODULES-10729\] defined\_with\_params - unnamed type [\#1115](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1115) ([trevor-vaughan](https://github.com/trevor-vaughan))

## [v6.3.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v6.3.0) (2020-04-16)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/v6.2.0...v6.3.0)

### Added

- Add start\_with function [\#1086](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1086) ([baurmatt](https://github.com/baurmatt))
- stdlib::end\_with: create String.end\_with function [\#1084](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1084) ([b4ldr](https://github.com/b4ldr))
- Adding str2saltedpbkdf2 function [\#1040](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1040) ([genebean](https://github.com/genebean))

### Fixed

- \(MODULES-10623\) explicitly top-scope calls to JSON methods [\#1101](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1101) ([tkishel](https://github.com/tkishel))
- \[IAC-547\] Remove strftime from stdlib as it has already been replaced by the puppet agent since 4.8.0 [\#1097](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1097) ([carabasdaniel](https://github.com/carabasdaniel))
- Add correct namespace for start\_with function [\#1095](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1095) ([baurmatt](https://github.com/baurmatt))
- intersection: show types in exception due to invalid arguments [\#1077](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1077) ([runejuhl](https://github.com/runejuhl))
- Make type aliases stricter [\#1066](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1066) ([pegasd](https://github.com/pegasd))

## [v6.2.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v6.2.0) (2019-12-10)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/v6.1.0...v6.2.0)

### Added

- \(FM-8696\) - Addition of Support for CentOS 8 [\#1065](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1065) ([david22swan](https://github.com/david22swan))
- Add support for additional options to to\_json\_pretty [\#1055](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1055) ([runejuhl](https://github.com/runejuhl))

### Fixed

- Fix PE detection \(for the moment\) [\#1049](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1049) ([trevor-vaughan](https://github.com/trevor-vaughan))

## [v6.1.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v6.1.0) (2019-09-20)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/v6.0.0...v6.1.0)

### Added

- \(MODULES-9915\) Add type aliases for cloud object store uris [\#1048](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1048) ([hooten](https://github.com/hooten))
- FM-8411 - add support for debian10 [\#1045](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1045) ([lionce](https://github.com/lionce))
- \(FM-8230\) Convert testing to litmus [\#1031](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1031) ([eimlav](https://github.com/eimlav))
- \(FM-8160\) Add Windows Server 2019 support [\#1025](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1025) ([eimlav](https://github.com/eimlav))
- \(FM-8048\) Add RedHat 8 support [\#1022](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1022) ([eimlav](https://github.com/eimlav))
- \(MODULES-9049\) Add type alias for 'yes' and 'no'. [\#1017](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1017) ([ghoneycutt](https://github.com/ghoneycutt))
- add Stdlib::Syslogfacility type [\#1005](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1005) ([bastelfreak](https://github.com/bastelfreak))

### Fixed

- fix lib/puppet/parser/functions/fqdn\_rand\_string.rb:21: syntax error [\#1029](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1029) ([pulecp](https://github.com/pulecp))
- Limit the maximum array size produced by range\(\). [\#1023](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1023) ([mbaynton](https://github.com/mbaynton))

## [v6.0.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/v6.0.0) (2019-05-10)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/5.2.0...v6.0.0)

### Changed

- pdksync - \(MODULES-8444\) - Raise lower Puppet bound [\#1011](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1011) ([david22swan](https://github.com/david22swan))
- \(MODULES-8760\) Add iterative feature to merge\(\) function [\#1008](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1008) ([hlindberg](https://github.com/hlindberg))

### Added

- Add a stdlib::ip\_in\_range\(\) function [\#1003](https://github.com/puppetlabs/puppetlabs-stdlib/pull/1003) ([iglov](https://github.com/iglov))

## [5.2.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/5.2.0) (2019-01-17)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/5.1.0...5.2.0)

### Added

- \(MODULES-8404\) - Relax `Stdlib::Filesource` type [\#981](https://github.com/puppetlabs/puppetlabs-stdlib/pull/981) ([alexjfisher](https://github.com/alexjfisher))
- Creates new type Stdlib::IP::Address::V6::CIDR [\#980](https://github.com/puppetlabs/puppetlabs-stdlib/pull/980) ([timhughes](https://github.com/timhughes))
- \(MODULES-8137\) - Addition of support for SLES 15 [\#978](https://github.com/puppetlabs/puppetlabs-stdlib/pull/978) ([david22swan](https://github.com/david22swan))
- \(MODULES-8322\) Consider IPs with /0 as valid [\#975](https://github.com/puppetlabs/puppetlabs-stdlib/pull/975) ([simondeziel](https://github.com/simondeziel))
- Add a function to compare the OS version [\#972](https://github.com/puppetlabs/puppetlabs-stdlib/pull/972) ([ekohl](https://github.com/ekohl))
- \(MODULES-8273\) - Make unquoted classes useable [\#971](https://github.com/puppetlabs/puppetlabs-stdlib/pull/971) ([baurmatt](https://github.com/baurmatt))
- add Function extname\(\) [\#949](https://github.com/puppetlabs/puppetlabs-stdlib/pull/949) ([cocker-cc](https://github.com/cocker-cc))
- \(MODULES-7024\) Add 20-octet MAC addresses [\#905](https://github.com/puppetlabs/puppetlabs-stdlib/pull/905) ([ananace](https://github.com/ananace))

### Fixed

- pdksync - \(FM-7655\) Fix rubygems-update for ruby \< 2.3 [\#979](https://github.com/puppetlabs/puppetlabs-stdlib/pull/979) ([tphoney](https://github.com/tphoney))
- fix ensure\_packages duplicate checking [\#969](https://github.com/puppetlabs/puppetlabs-stdlib/pull/969) ([netzvieh](https://github.com/netzvieh))

## [5.1.0](https://github.com/puppetlabs/puppetlabs-stdlib/tree/5.1.0) (2018-09-28)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-stdlib/compare/5.0.0...5.1.0)

### Added

- pdksync - \(MODULES-6805\) metadata.json shows support for puppet 6 [\#958](https://github.com/puppetlabs/puppetlabs-stdlib/pull/958) ([tphoney](https://github.com/tphoney))
- \(maint\) Convert from mocking with mocha to rspec-mocks [\#948](https://github.com/puppetlabs/puppetlabs-stdlib/pull/948) ([rodjek](https://github.com/rodjek))

### Fixed

- \(FM-7388\) - Fixing unit tests for puppet 4, 5 and 6 [\#962](https://github.com/puppetlabs/puppetlabs-stdlib/pull/962) ([tphoney](https://github.com/tphoney))
- Fix `pick` function docs [\#955](https://github.com/puppetlabs/puppetlabs-stdlib/pull/955) ([alexjfisher](https://github.com/alexjfisher))
- \(MODULES-7768\) Handle nil in delete\_undef\_values\(\) function [\#954](https://github.com/puppetlabs/puppetlabs-stdlib/pull/954) ([hlindberg](https://github.com/hlindberg))
- Update docs for 'concat' to be correct [\#950](https://github.com/puppetlabs/puppetlabs-stdlib/pull/950) ([rhowe-gds](https://github.com/rhowe-gds))

## 5.0.0
### Summary
This is a major release which removes support for the Scientific 5 and Debian 7 OS, as well as a removal of the `Stdlib::(Ipv4|IPv6|Ip_address)` data types in favour of `Stdlib::IP::*`. 

**In addition it contains a substantial piece of work centered around updating functions that have now been migrated into Puppet itself. Please note that this will be the last major release to support Puppet 2 and Puppet 3 and that they will soon be removed.**

#### Fixed
- Docs URLs corrected.
- Docs clarified that `Stdlib::Unixpath` only matches absolute paths.
- `dirname()` now fails when passed an empty string.
- `basename()` documentation clarified.
- Corrected documentation of `count()` wrt matches and empty string.
- Corrected example in `getparam()` and added note about equivalent in puppet.
- Fixed URL to use 'latest' instead of '5.5' for `Hash.new` function.

#### Added
- Support added for symbolic file nodes.
- `loadjson()` and `loadyml()` now compatible with HTTPS files.
- `loadjson()` and `loadyml()` now compatible with HTTP basic auth files.
- `any2array` now returns and empty array when given an empty string.
- Support has now been added for Ubuntu 18.04.
- `seeded_rand_string()` function has been added.

#### Changed
- PDK update `1.5.0` has been applied.
- `size()` function deprecated for Puppet 6 and above.
- `wrt` functions moved to Puppet as of Puppet 6.
- `sprintf_hash` has had notification put in place to show that as of Puppet 4.10.10 it's functionality is supported by the puppet core.
- Added note that `abs()` is in puppet since 6.0.0.
- Added information to `base64` function about Binary data type.
- Added note to `camelcase()` that function is now in puppet.
- Added note to `capitalize()` that function is now in puppet.
- Added note to `ceiling()` that function is now in puppet.
- Added note to `chomp()` that function is now in puppet.
- Added note to `chop()` that function is now in puppet.
- Added note how to do equivalence of `clamp()` function in puppet 6.
- Added note that `concat()` can be done with + since puppet 4.0.0.
- Added note to `convert_base()` how to do this with puppet core.
- Added equivalent puppet core way of doing `count()`.
- Added docs for equivalent puppet language for `delete_regexp()`.
- Added docs for equivalent language constructs for `delete_at()`.
- Added puppet 4 equivalent for `delete_undef()` function.
- Added equivalent puppet language for `delete_values()`.
- Updated `delete()` function with docs about equivalent language.
- Added docs that - between arrays is the same as `difference()`.
- Added note to `downcase()` that function is now in puppet.
- Added note to `empty()` that function is now in puppet.
- Added note to `flatten()` that function is now in puppet.
- Added note to `floor()` that function is now in puppet.
- Added note to `get_module_path()` that puppet has similar function.
- Amended documentation for `getvar()`.
- Add note to `grep()` that `filter()` in puppet does the same.
- Updated `has_key()` with equivalent puppet lang expresion.
- Updated the `hash()` function to show equivalent expression.
- Added note about more formatting options with `String()` in puppet.
- Added note to `join()` that it is in puppet since 5.4.0.
- Added note to `keys()` that it is in puppet since 5.4.0.
- Added note to `lstrip()`, `rstrip()`, `strip()` and `upcase()` that they are in puppet since 6.0.0.
- Updated `member()` with equivalent language expression example.
- Updated `merge()` with puppt language equivalent example.
- Updated `min()` and `max()` with note that they are in puppet.
- Updated `num2bool()` with information that Boolean can convert.
- Updated `prefix()` function with equivalent operation in puppet.
- Updated `range()` with information that Integer can be used.
- Updated `reject()` with equivalent filter() call.
- Added note to `reverse()` that the `reverse_each()` Puppet function does the same as it.
- Added note to `round()` that it has moved to puppet in 6.0.0.
- Added note to `size()` that `length()` is in puppet since 5.4.0.
- Added note to `sort()` that is has moved to Puppet in 6.0.0.
- Updated `str2bool()` with a note that Boolean can handle conversion.
- Added note to `strftime()` that it moved to puppet in 4.8.0.
- Added note to `suffix()` that the same can be done with `map()`.
- Updated `time()` to mention Timespan and Timestamp data types.
- Added note to `values_at()` for equivalent slice operation in language.
- Added note to `values()` that it moved to puppet in 5.5.0.
- Corrected docs for `keys()` - in puppet since 5.5.0.
- Added note to `length()` that function moved to puppet.
- Updated README.md with deprecations for functions moved to puppet.
- Updated documentation of `values_at()`.
- Updated README with note from `time()` about data types for time.
- Updated README for `strintf_hash()` (supported by builtin sprintf).
- Updated README with deprecation of `hash()` function (use data type).
- Updated README `suffix` with equiv example for `map`.
- Updated README with `reject` equivalent call to `filter`.
- Updated README with `range` equiv use of type system + `each`.
- Updated README with `prefix` equiv func using `map`.
- Updated README for `num2bool` with info about Boolean type.
- Updated README `str2bool` with information about `Boolean` equivalent.
- Updated README `merge` with info about `+` operator equivalent.
- Updated README `member` with equivalent alternative in language.
- Updated README `join_keys_to_values` with link to String.new.
- Updated README `has_key` shows deprecation in favor of `in`.
- Updated README `grep` adds information about `filter`.
- Updated README and `getvar.rb` as getvar has moved to puppet.
- Updated README for `getparam` to be the same as in function.
- Updated README `get_module_path` with info about built in variant.
- Updated README `difference` to mention `-` operator equiv.
- Updated README `delete` with built-in alternatives.
- Updated README `delete_values` with builtin equiv.
- Updated README `delete_undef` & `delete_regexp` with builtin equiv.
- Updated README `delete_at` with equivalent built-in examples.
- Updated README `coun`t to show built-in equiv.
- Updated README `convert_base` with built-in equiv.
- Updated README `concat` with built-in equiv using + and <<.
- Updated README `base_64` with built-in equiv using Binary type.
- Skipped tests for `abs` if puppet version < 6.0.0.
- Skipped tests for `min` and `max` if puppet version < 6.0.0.
- Skipped tests for `floor` if puppet version < 6.0.0.
- Skipped tests for `ceiling` if puppet version < 6.0.0.
- Skipped tests for `round` if puppet version < 6.0.0.
- Skipped tests for `upcase` if puppet version < 6.0.0.
- Skipped tests for `downcase` if puppet version < 6.0.0.
- Skipped tests for `capitalize` if puppet version < 6.0.0.
- Skipped tests for `camelcase` if puppet version < 6.0.0.
- Skipped tests for strip functions if puppet version < 6.0.0.
- Skipped tests for `chop` and `chomp` if puppet version < 6.0.0.
- Skipped tests for `sort` if puppet version < 6.0.0.
- Removed extra space in `describe` for `abs` test.
- Updated README and `any2array` with built-in equiv Array.new.
- Updated README and `any2bool` with built-in equiv Boolean.new.
- Updated README and `bool2num` with built-in equiv Numeric.new.
- Updated README and `bool2str` with built-in equiv String.new.
- Corrected equivalent example for `count`.
- Updated README and made mention of `filter` in `delete` a link.
- Updated docs and tests for `strftime`.
- Updated all acceptance test using Puppet.version.
- Change 'puppet' to 'Puppet' in function doc strings.
- HTTP type checks are now case insensitive.

#### Removed
- Support has been removed for `Scientific 5` and `Debian 7` operating systems.
- `Stdlib::(Ipv4|IPv6|Ip_address)` have been removed.

## Supported Release 4.25.1
### Summary

This is a patch which includes a roll up of small fixes. In Puppet 5.5.0 `flatten()`, `length(),` `empty(),` `join(),` `keys(),` and `values()` are now built into Puppet. Please note that the Puppet implementation of the functions will take precedence over the functions in 'puppetlabs-stdlib'.

#### Fixed
- Remove unneeded execute permission from test files.
- Puppet 5.5.0 function deprecation [MODULES-6894](https://tickets.puppetlabs.com/browse/MODULES-6894).

## Supported Release 4.25.0
### Summary

This is quite a feature heavy release, it makes this module PDK-compliant for easier maintenance and includes a roll up of maintenance changes.

#### Added
- PDK conversion [MODULES-6332](https://tickets.puppetlabs.com/browse/MODULES-6332).
- Update `join_keys_to_values` with an undef statement.
- Type alias `Stdlib::Fqdn` matches paths on a fully qualified domain name.
- Type alias `Stdlib::Host` matches a valid host, this can be a valid 'ipv4', 'ipv6' or 'fqdn'.
- Type alias `Stdlib::Port` matches a valid TCP/UDP Port number.
- Type alias `Stdlib::Filesource` matches paths valid values for the source parameter of the puppet file type.
- Type alias `Stdlib::IP::Address` matches any IP address, including both IPv4 and IPv6 addresses,
- Type alias `Stdlib::IP::Address::V4` matches any string consisting of a valid IPv4 address, this is extended by 'CIDR' and 'nosubnet'.
- Type alias `Stdlib::IP::Address::V6` matches any string consisting of a valid IPv6 address, this is extended by 'Full', 'Alternate' and 'Compressed'.
- Type alias `Stdlib::IP::Address::V6::Nosubnet`matches any string consisting of a valid IPv6 address with no subnet, this is extended by 'Full', 'Alternate' and 'Compressed'.
- Type alias `Stdlib::Port` matches a valid TCP/UDP Port number this is then extended to 'Privileged' which are ports less than 1024 and 'Unprivileged' which are ports greater than 1024.

## Supported Release 4.24.0
### Summary

This release includes a roll up of minor changes and a new feature which provides the ability to skip undef values `to_json_pretty()`.
We have also reverted a change that was previously made and resulted in breaking compatibility with Ruby 1.8.7.

#### Added
- Ability to skip undef values in `to_json_pretty()`.
- Fix type3x function in stdlib ([MODULES-6216](https://tickets.puppet.com/browse/MODULES-6216))

#### Changed
- Indentation for `sync.yml` was fixed.
- Updated type alias tests and dropped superfluous wrapper classes
- Revert to old ruby 1.X style of hash ([MODULES-6139](https://tickets.puppet.com/browse/MODULES-6139))
- `rubocop.yml` not managed by msync ([MODULES-6201](https://tickets.puppet.com/browse/MODULES-6201))

## Supported Release 4.23.0
### Summary

This release is in order to implement Rubocop changes throughout the module.

#### Added
- Standard and translated readme's have been updated.
- Rubocop has been implemented in the module and a wide variety of changes have been made to the code.
- Modulesync changes have been merged into the code.

#### Fixed
- Minor fix to the readme.

## Supported Release 4.22.0
### Summary

This is a clean release in preparation of putting the module through the rubocop process.

#### Added
- Support has been added for Debian 9
- 'Stdlib::Mode type' has been added to the module.
- A type for 'ensure' has been added to the service resources.
- A new function 'sprintf_hash' has been added to allow the use of named references.

#### Removed
- Support has been removed for: RedHat 4, CentOS 4, OracleLinux 4, Scientific 4, SLES 10 SP4, Windows Server 2003, Windows Server 2003 R2 and Windows 8.

#### Fixed
- The 'ruby_spec.rb' test file has been altered s that it properly checks results.
- Example syntax in 'file_line.rb' has been fixed.

## Supported Release 4.21.0
### Summary

This is a small feature release that includes a revamped, albeit backwards-compatible file_line type.

#### Added
- `replace_all_matches_not_matching_line` parameter in file_line
- additional tests and documentation for file_line

#### Removed
- duplicate spec test for absolute_path

#### Fixed
- Unixpath type to allow "/" as valid path
- file_line behavior that caused infinite appending of `line` to a file ([MODULES-5651](https://tickets.puppet.com/browse/MODULES-5651))

## Supported Release 4.20.0
### Summary

This release adds new functions and updated README translations.

#### Added
- `to_json`, `to_json_pretty`, and `to_yaml` functions
- new Japanese README translations

#### Fixed
- compatibility issue with older versions of Puppet and the `pw_hash` function ([MODULES-5546](https://tickets.puppet.com/browse/MODULES-5546))

#### Removed
- support for EOL platform Debian 6 (Squeeze)

## Supported Release 4.19.0
### Summary

This release adds new functions and better documentation/fixes for existing functions with a noteworthy fix for file_line.

#### Added
- Add validate_domain_name function
- Add the round function
- Add type for MAC address
- Add support for sensitive data type to pw_hash ([MODULES-4908](https://tickets.puppet.com/browse/MODULES-4908))
- Add new function, fact() (FACT-932)

#### Fixed
- Fixes for the file_line provider ([MODULES-5003](https://tickets.puppet.com/browse/MODULES-5003))
- Add documentation for email functions ([MODULES-5382](https://tickets.puppet.com/browse/MODULES-5382))
- unique function is deprecated for puppet version > 5. (FM-6239)
- Fix headers in CHANGELOG.md so that headers render correctly
- ensure_packages, converge ensure values 'present' and 'installed'

#### Changed
- Removes listed support for EOL Ubuntu versions

## Supported Release 4.18.0
### Summary

Small release that reverts the Puppet version requirement lower bound to again include Puppet 2.7+ and bumps the upper bound to now include Puppet 5.

#### Fixed
- Reverts lower bound of Puppet requirement to 2.7.20

## Supported Release 4.17.1
### Summary

Small release to address a bug (PUP-7650). Also pushes the Puppet version compatibility to 4.7.0.

#### Bugfixes
- (MODULES-5095) Workaround for PUP-7650
- (FM-6197) Formatting fixes for file_line resource


## Supported Release 4.17.0
### Summary
This release adds support for internationalization. It also contains Japanese translations for the README, summary and description of the metadata.json and major cleanups in the README. Additional folders have been introduced called locales and readmes where translation files can be found. A number of features and bug fixes are also included in this release. It also adds a new function `glob()` for expanding file lists. Also works around an issue that appeared in puppet 4.6.0 involving types being declared multiple times.

#### Features
- Addition of POT file / folder structure for i18n.
- Addition of Internationalized READMEs.
- `glob()` function

### Fixed
- Occasional duplicate type definitions when using `defined_with_params()`
- `file_line` encoding issue on ruby 1.8 (unsupported)
- Huge readme refresh

## Supported Release 4.16.0
### Summary

This release sees a massive update to all unit tests to test UTF8 characters. There are also multiple cleanups in preparation for internationalization. Alongside this, improvements to ipv6 support, a new length function compatible with Puppet 4, and an update to path types. Also contains multiple bug fixes around functionality and tests.

#### Features
- Addition of coverage in all unit tests for functions, data and resource types for UTF8 for i18n.
- All strings within the readme and functions that are split over two lines have been combined in preparation for i18n parser/decorator.
- Improvement on the ipv6 support for type - Improves regex to catch some valid (but lesser known) ipv6 strings, mostly those which are a mix of ipv6 strings and embedded ipv6 numbers.
- Adds a new parameter `encoding` to allow non UTF-8 files to specify a file encoding. This prevents receiving the error message "invalid byte sequence in UTF-8" when special characters that are not UTF-8 encoded appear in the input stream, such as the copyright symbol.
- Addition of the new length function. Returns the length of a given string, array or hash. To eventually replace the deprecated size() function as can handle the new type functionality introduced in Puppet 4.
- Permit double slash in absolute/Unix path types.

#### Bugfixes
- Fix unsupported data type error with rspec-puppet server.
- Now allows test module metadata.json to be read by Puppet.
- Fix acceptance test failure "Hiera is not a class".
- Removal of unsupported platforms and future parser setting in acceptance tests.
- Regex for tuple checking has been loosened.
- Ensure_packages function - Now only tries to apply the resource if not defined.
- (MODULES-4528) Use versioncmp to check Puppet version for 4.10.x compat.
- Adds comments to warn for UTF8 incompatibility of the functions that may not be compatible with UTF8 with Ruby < 2.4.0.

## Supported Release 4.15.0
### Summary

This release introduces multiple new functions, a new fact and the addition of Ubuntu Xenial support. Also includes a bugfix and documentation update.

#### Features
- Addition of puppet_server fact to return agents server.
- Addition of a pry function.
- Addition of tests for ensure_resources.
- Addition of FQDN UUID generation function.
- Addition of Ubuntu Xenial to OS Support.

#### Bugfixes
- Ensure_packages now works with Ruby < 2.0.
- Updated the documentation of str2bool function.

## Supported Release 4.14.0
### Summary

Adds several new features and updates, especially around refining the deprecation and validate_legacy functions. Also includes a Gemfile update around an issue with parallel_tests dependancy for different versions of Ruby.

#### Features
- Deprecation function now uses puppet stacktrace if available.
- join_key_to_values function now handles array values. If values are arrays, multiple keys are added for each element.
- Updated Gemfile to deal with parallel_tests Ruby dependancy (MODULES-3983).
- Updated/Fixed ipv4 regex validator (MODULES-3980).
- Deprecation clarification added to README.

#### Bugfixes
- README typo fixes.
- Use .dup to duplicate classes for modification (MODULES-3829).
- Fixes spec failures that were caused by a change in the tested error message in validate_legacy_spec.
- Broken link to validate_legacy docs fixed.
- Updates deprecation tests to include future parser.

## Supported Release 4.13.1
### Summary

This bugfix release addresses the `undefined method 'optional_repeated_param'` error messages seen by users of puppet 3.7.

It also improves the user experience around function deprecations by emitting one warning per function(-name) instead of only one deprecation overall. This allows users to identify all deprecated functions used in one agent run, with less back-and-forth.

#### Bugfixes

* Emit deprecations warnings for each function, instead of once per process. (MODULES-3961)
* Use a universally available API for the v4 deprecation stubs of `is_*` and `validate_*`. (MODULES-3962)
* Make `getvar()` compatible to ruby 1.8.7. (MODULES-3969)
* Add v4 deprecation stubs for the `is_` counterparts of the deprecated functions to emit the deprecations warnings in all cases.


## Supported Release 4.13.0
### Summary

This version of stdlib deprecates a whole host of functions, and provides stepping stones to move to Puppet 4 type validations. Be sure to check out the new `deprecation()` and `validate_legacy()` functions to migrate off the deprecated v3-style data validations.

Many thanks to all community contributors: bob, Dmitry Ilyin, Dominic Cleal, Joris, Joseph Yaworski, Loic Antoine-Gombeaud, Maksym Melnychok, Michiel Brandenburg, Nate Potter, Romain Tartière, Stephen Benjamin, and Steve Moore, as well as anyone contributing in the code review process and by submitting issues.

Special thanks to [Voxpupuli's](https://voxpupuli.org/) Igor Galić for donating the puppet-tea types to kickstart this part of stdlib.


#### Deprecations
* `validate_absolute_path`, `validate_array`, `validate_bool`, `validate_hash`, `validate_integer`, `validate_ip_address`, `validate_ipv4_address`, `validate_ipv6_address`, `validate_numeric`, `validate_re`, `validate_slength`, `validate_string`, and their `is_` counter parts are now deprecated on Puppet 4. See the `validate_legacy()` description in the README for help on migrating away from those functions.
* The `dig` function is provided by core puppet since 4.5.0 with slightly different calling convention. The stdlib version can still be accessed as `dig44` for now.


#### Features
* Add Puppet 4 data types for Unix, and Windows paths, and URLs.
* Add `deprecation` function to warn users of functionality that will be removed soon.
* Add `validate_legacy` function to help with migrating to Puppet 4 data types.

* Add `any2bool` function, a combination of of `string2bool` and `num2bool`.
* Add `delete_regex` function to delete array elements matching a regular expression.
* Add `puppet_environmentpath` fact to expose the `environmentpath` setting.
* Add `regexpescape` function to safely insert arbitrary strings into regular expressions.
* Add `shell_escape`, `shell_join`, and `shell_split` functions for safer working with shell scripts..

* The `delete` function now also accepts regular expressions as search term.
* The `loadyaml` function now accepts a default value, which is returned when there is an error loading the file.

#### Bugfixes
* Fix `file_line.match_for_absence` implementation and description to actually work. (MODULES-3590)
* Fix `getparam` so that it can now also return `false`. (MODULES-3933)
* Fix the fixture setup for testing and adjust `load_module_metadata` and `loadjson` tests.
* Fix `defined_with_params` to handle `undef` correctly on all puppet versions. (PUP-6422, MODULES-3543)
* Fix `file_line.path` validation to use puppet's built in `absolute_path?` matcher.

#### Minor Improvements
* README changes: improved descriptions of `deep_merge`, `delete`, `ensure_packages`, `file_line.after`, `range`, and `validate_numeric`.
* The `getvar` function now returns nil in all situations where the variable is not found.
* Update the `dig44` function with better `undef`, `nil`, and `false` handling.
* Better wording on `str2bool` argument validation error message.


### Known issues
* The `validate_legacy` function relies on internal APIs from Puppet 4.4.0 (PE 2016.1) onwards, and doesn't work on earlier versions.
* Puppet 4.5.0 (PE 2016.2) has a number of improvements around data types - especially error handling - that make working with them much nicer.

## Supported Release 4.12.0
### Summary

This release provides several new functions, bugfixes, modulesync changes, and some documentation updates.

#### Features
- Adds `clamp`. This function keeps values within a specified range.
- Adds `validate_x509_rsa_key_pair`. This function validates an x509 RSA certificate and key pair.
- Adds `dig`. This function performs a deep lookup in nested hashes or arrays.
- Extends the `base64` support to fit `rfc2045` and `rfc4648`.
- Adds `is_ipv6_address` and `is_ipv4_address`. These functions validate the specified ipv4 or ipv6 addresses.
- Adds `enclose_ipv6`. This function encloses IPv6 addresses in square brackets.
- Adds `ensure_resources`. This function takes a list of resources and creates them if they do not exist.
- Extends `suffix` to support applying a suffix to keys in a hash.
- Apply modulesync changes.
- Add validate_email_address function.

#### Bugfixes
- Fixes `fqdn_rand_string` tests, since Puppet 4.4.0 and later have a higher `fqdn_rand` ceiling.
- (MODULES-3152) Adds a check to `package_provider` to prevent failures if Gem is not installed.
- Fixes to README.md.
- Fixes catch StandardError rather than the gratuitous Exception
- Fixes file_line attribute validation.
- Fixes concat with Hash arguments.

## Supported Release 4.11.0
### Summary

Provides a validate_absolute_paths and Debian 8 support. There is a fix to the is_package_provider fact and a test improvement.

#### Features
-  Adds new parser called is_absolute_path
-  Supports Debian 8

#### Bugfixes
-  Allow package_provider fact to resolve on PE 3.x

#### Improvements
- ensures that the test passes independently of changes to rubygems for ensure_resource

## 2015-12-15 - Supported Release 4.10.0
### Summary

Includes the addition of several new functions and considerable improvements to the existing functions, tests and documentation. Includes some bug fixes which includes compatibility, test and fact issues.

#### Features
- Adds service_provider fact
- Adds is_a() function
- Adds package_provider fact
- Adds validate_ip_address function
- Adds seeded_rand function

#### Bugfixes
- Fix backwards compatibility from an improvement to the parseyaml function
- Renaming of load_module_metadata test to include \_spec.rb
- Fix root_home fact on AIX 5.x, now '-c' rather than '-C'
- Fixed Gemfile to work with ruby 1.8.7

#### Improvements
- (MODULES-2462) Improvement of parseyaml function
- Improvement of str2bool function
- Improvement to readme
- Improvement of intersection function
- Improvement of validate_re function
- Improved speed on Facter resolution of service_provider
- empty function now handles numeric values
- Package_provider now prevents deprecation warning about the allow_virtual parameter
- load_module_metadata now succeeds on empty file
- Check added to ensure puppetversion value is not nil
- Improvement to bool2str to return a string of choice using boolean
- Improvement to naming convention in validate_ipv4_address function

## Supported Release 4.9.1
### Summary

Small release for support of newer PE versions. This increments the version of PE in the metadata.json file.

## 2015-09-08 - Supported Release 4.9.0
### Summary

This release adds new features including the new functions dos2unix, unix2dos, try_get_value, convert_base as well as other features and improvements.

#### Features
- (MODULES-2370) allow `match` parameter to influence `ensure => absent` behavior
- (MODULES-2410) Add new functions dos2unix and unix2dos
- (MODULE-2456) Modify union to accept more than two arrays
- Adds a convert_base function, which can convert numbers between bases
- Add a new function "try_get_value"

#### Bugfixes
- n/a

#### Improvements
- (MODULES-2478) Support root_home fact on AIX through "lsuser" command
- Acceptance test improvements
- Unit test improvements
- Readme improvements

## 2015-08-10 - Supported Release 4.8.0
### Summary
This release adds a function for reading metadata.json from any module, and expands file\_line's abilities.

#### Features
- New parameter `replace` on `file_line`
- New function `load_module_metadata()` to load metadata.json and return the content as a hash.
- Added hash support to `size()`

#### Bugfixes
- Fix various docs typos
- Fix `file_line` resource on puppet < 3.3

## 2015-06-22 - Supported Release 4.7.0
### Summary

Adds Solaris 12 support along with improved Puppet 4 support. There are significant test improvements, and some minor fixes.

#### Features
- Add support for Solaris 12

#### Bugfixes
- Fix for AIO Puppet 4
- Fix time for ruby 1.8.7
- Specify rspec-puppet version
- range() fix for typeerror and missing functionality
- Fix pw_hash() on JRuby < 1.7.17
- fqdn_rand_string: fix argument error message
- catch and rescue from looking up non-existent facts
- Use puppet_install_helper, for Puppet 4

#### Improvements
- Enforce support for Puppet 4 testing
- fqdn_rotate/fqdn_rand_string acceptance tests and implementation
- Simplify mac address regex
- validate_integer, validate_numeric: explicitely reject hashes in arrays
- Readme edits
- Remove all the pops stuff for rspec-puppet
- Sync via modulesync
- Add validate_slength optional 3rd arg
- Move tests directory to examples directory

## 2015-04-14 - Supported Release 4.6.0
### Summary

Adds functions and function argument abilities, and improves compatibility with the new puppet parser

#### Features
- MODULES-444: `concat()` can now take more than two arrays
- `basename()` added to have Ruby File.basename functionality
- `delete()` can now take an array of items to remove
- `prefix()` can now take a hash
- `upcase()` can now take a hash or array of upcaseable things
- `validate_absolute_path()` can now take an array
- `validate_cmd()` can now use % in the command to embed the validation file argument in the string
- MODULES-1473: deprecate `type()` function in favor of `type3x()`
- MODULES-1473: Add `type_of()` to give better type information on future parser
- Deprecate `private()` for `assert_private()` due to future parser
- Adds `ceiling()` to take the ceiling of a number
- Adds `fqdn_rand_string()` to generate random string based on fqdn
- Adds `pw_hash()` to generate password hashes
- Adds `validate_integer()`
- Adds `validate_numeric()` (like `validate_integer()` but also accepts floats)

#### Bugfixes
- Fix seeding of `fqdn_rotate()`
- `ensure_resource()` is more verbose on debug mode
- Stricter argument checking for `dirname()`
- Fix `is_domain_name()` to better match RFC
- Fix `uriescape()` when called with array
- Fix `file_line` resource when using the `after` attribute with `match`

## 2015-01-14 - Supported Release 4.5.1
### Summary

This release changes the temporary facter_dot_d cache locations outside of the /tmp directory due to a possible security vunerability. CVE-2015-1029

#### Bugfixes
- Facter_dot_d cache will now be stored in puppet libdir instead of tmp

## 2014-12-15 - Supported Release 4.5.0
### Summary

This release improves functionality of the member function and adds improved future parser support.

#### Features
- MODULES-1329: Update member() to allow the variable to be an array.
- Sync .travis.yml, Gemfile, Rakefile, and CONTRIBUTING.md via modulesync

#### Bugfixes
- Fix range() to work with numeric ranges with the future parser
- Accurately express SLES support in metadata.json (was missing 10SP4 and 12)
- Don't require `line` to match the `match` parameter

## 2014-11-10 - Supported Release 4.4.0
### Summary
This release has an overhauled readme, new private manifest function, and fixes many future parser bugs.

#### Features
- All new shiny README
- New `private()` function for making private manifests (yay!)

#### Bugfixes
- Code reuse in `bool2num()` and `zip()`
- Fix many functions to handle `generate()` no longer returning a string on new puppets
- `concat()` no longer modifies the first argument (whoops)
- strict variable support for `getvar()`, `member()`, `values_at`, and `has_interface_with()`
- `to_bytes()` handles PB and EB now
- Fix `tempfile` ruby requirement for `validate_augeas()` and `validate_cmd()`
- Fix `validate_cmd()` for windows
- Correct `validate_string()` docs to reflect non-handling of `undef`
- Fix `file_line` matching on older rubies


## 2014-07-15 - Supported Release 4.3.2
### Summary

This release merely updates metadata.json so the module can be uninstalled and
upgraded via the puppet module command.

## 2014-07-14 - Supported Release 4.3.1
### Summary
This supported release updates the metadata.json to work around upgrade behavior of the PMT.

#### Bugfixes
- Synchronize metadata.json with PMT-generated metadata to pass checksums

## 2014-06-27 - Supported Release 4.3.0
### Summary
This release is the first supported release of the stdlib 4 series. It remains
backwards-compatible with the stdlib 3 series. It adds two new functions, one bugfix, and many testing updates.

#### Features
- New `bool2str()` function
- New `camelcase()` function

#### Bugfixes
- Fix `has_interface_with()` when interfaces fact is nil

## 2014-06-04 - Release 4.2.2
### Summary

This release adds PE3.3 support in the metadata and fixes a few tests.

## 2014-05-08 - Release - 4.2.1
### Summary
This release moves a stray symlink that can cause problems.

## 2014-05-08 - Release - 4.2.0
### Summary
This release adds many new functions and fixes, and continues to be backwards compatible with stdlib 3.x

#### Features
- New `base64()` function
- New `deep_merge()` function
- New `delete_undef_values()` function
- New `delete_values()` function
- New `difference()` function
- New `intersection()` function
- New `is_bool()` function
- New `pick_default()` function
- New `union()` function
- New `validate_ipv4_address` function
- New `validate_ipv6_address` function
- Update `ensure_packages()` to take an option hash as a second parameter.
- Update `range()` to take an optional third argument for range step
- Update `validate_slength()` to take an optional third argument for minimum length
- Update `file_line` resource to take `after` and `multiple` attributes

#### Bugfixes
- Correct `is_string`, `is_domain_name`, `is_array`, `is_float`, and `is_function_available` for parsing odd types such as bools and hashes.
- Allow facts.d facts to contain `=` in the value
- Fix `root_home` fact on darwin systems
- Fix `concat()` to work with a second non-array argument
- Fix `floor()` to work with integer strings
- Fix `is_integer()` to return true if passed integer strings
- Fix `is_numeric()` to return true if passed integer strings
- Fix `merge()` to work with empty strings
- Fix `pick()` to raise the correct error type
- Fix `uriescape()` to use the default URI.escape list
- Add/update unit & acceptance tests.


## 2014-03-04 - Supported Release - 3.2.1
### Summary
This is a supported release

#### Bugfixes
- Fixed `is_integer`/`is_float`/`is_numeric` for checking the value of arithmatic expressions.

#### Known bugs
* No known bugs

---

##### 2013-05-06 - Jeff McCune <jeff@puppetlabs.com> - 4.1.0

 * (#20582) Restore facter\_dot\_d to stdlib for PE users (3b887c8)
 * (maint) Update Gemfile with GEM\_FACTER\_VERSION (f44d535)

##### 2013-05-06 - Alex Cline <acline@us.ibm.com> - 4.1.0

 * Terser method of string to array conversion courtesy of ethooz. (d38bce0)

##### 2013-05-06 - Alex Cline <acline@us.ibm.com> 4.1.0

 * Refactor ensure\_resource expectations (b33cc24)

##### 2013-05-06 - Alex Cline <acline@us.ibm.com> 4.1.0

 * Changed str-to-array conversion and removed abbreviation. (de253db)

##### 2013-05-03 - Alex Cline <acline@us.ibm.com> 4.1.0

 * (#20548) Allow an array of resource titles to be passed into the ensure\_resource function (e08734a)

##### 2013-05-02 - Raphaël Pinson <raphael.pinson@camptocamp.com> - 4.1.0

 * Add a dirname function (2ba9e47)

##### 2013-04-29 - Mark Smith-Guerrero <msmithgu@gmail.com> - 4.1.0

 * (maint) Fix a small typo in hash() description (928036a)

##### 2013-04-12 - Jeff McCune <jeff@puppetlabs.com> - 4.0.2

 * Update user information in gemspec to make the intent of the Gem clear.

##### 2013-04-11 - Jeff McCune <jeff@puppetlabs.com> - 4.0.1

 * Fix README function documentation (ab3e30c)

##### 2013-04-11 - Jeff McCune <jeff@puppetlabs.com> - 4.0.0

 * stdlib 4.0 drops support with Puppet 2.7
 * stdlib 4.0 preserves support with Puppet 3

##### 2013-04-11 - Jeff McCune <jeff@puppetlabs.com> - 4.0.0

 * Add ability to use puppet from git via bundler (9c5805f)

##### 2013-04-10 - Jeff McCune <jeff@puppetlabs.com> - 4.0.0

 * (maint) Make stdlib usable as a Ruby GEM (e81a45e)

##### 2013-04-10 - Erik Dalén <dalen@spotify.com> - 4.0.0

 * Add a count function (f28550e)

##### 2013-03-31 - Amos Shapira <ashapira@atlassian.com> - 4.0.0

 * (#19998) Implement any2array (7a2fb80)

##### 2013-03-29 - Steve Huff <shuff@vecna.org> - 4.0.0

 * (19864) num2bool match fix (8d217f0)

##### 2013-03-20 - Erik Dalén <dalen@spotify.com> - 4.0.0

 * Allow comparisons of Numeric and number as String (ff5dd5d)

##### 2013-03-26 - Richard Soderberg <rsoderberg@mozilla.com> - 4.0.0

 * add suffix function to accompany the prefix function (88a93ac)

##### 2013-03-19 - Kristof Willaert <kristof.willaert@gmail.com> - 4.0.0

 * Add floor function implementation and unit tests (0527341)

##### 2012-04-03 - Eric Shamow <eric@puppetlabs.com> - 4.0.0

 * (#13610) Add is\_function\_available to stdlib (961dcab)

##### 2012-12-17 - Justin Lambert <jlambert@eml.cc> - 4.0.0

 * str2bool should return a boolean if called with a boolean (5d5a4d4)

##### 2012-10-23 - Uwe Stuehler <ustuehler@team.mobile.de> - 4.0.0

 * Fix number of arguments check in flatten() (e80207b)

##### 2013-03-11 - Jeff McCune <jeff@puppetlabs.com> - 4.0.0

 * Add contributing document (96e19d0)

##### 2013-03-04 - Raphaël Pinson <raphael.pinson@camptocamp.com> - 4.0.0

 * Add missing documentation for validate\_augeas and validate\_cmd to README.markdown (a1510a1)

##### 2013-02-14 - Joshua Hoblitt <jhoblitt@cpan.org> - 4.0.0

 * (#19272) Add has\_element() function (95cf3fe)

##### 2013-02-07 - Raphaël Pinson <raphael.pinson@camptocamp.com> - 4.0.0

 * validate\_cmd(): Use Puppet::Util::Execution.execute when available (69248df)

##### 2012-12-06 - Raphaël Pinson <raphink@gmail.com> - 4.0.0

 * Add validate\_augeas function (3a97c23)

##### 2012-12-06 - Raphaël Pinson <raphink@gmail.com> - 4.0.0

 * Add validate\_cmd function (6902cc5)

##### 2013-01-14 - David Schmitt <david@dasz.at> - 4.0.0

 * Add geppetto project definition (b3fc0a3)

##### 2013-01-02 - Jaka Hudoklin <jakahudoklin@gmail.com> - 4.0.0

 * Add getparam function to get defined resource parameters (20e0e07)

##### 2013-01-05 - Jeff McCune <jeff@puppetlabs.com> - 4.0.0

 * (maint) Add Travis CI Support (d082046)

##### 2012-12-04 - Jeff McCune <jeff@puppetlabs.com> - 4.0.0

 * Clarify that stdlib 3 supports Puppet 3 (3a6085f)

##### 2012-11-30 - Erik Dalén <dalen@spotify.com> - 4.0.0

 * maint: style guideline fixes (7742e5f)

##### 2012-11-09 - James Fryman <james@frymanet.com> - 4.0.0

 * puppet-lint cleanup (88acc52)

##### 2012-11-06 - Joe Julian <me@joejulian.name> - 4.0.0

 * Add function, uriescape, to URI.escape strings. Redmine #17459 (fd52b8d)

##### 2012-09-18 - Chad Metcalf <chad@wibidata.com> - 3.2.0

 * Add an ensure\_packages function. (8a8c09e)

##### 2012-11-23 - Erik Dalén <dalen@spotify.com> - 3.2.0

 * (#17797) min() and max() functions (9954133)

##### 2012-05-23 - Peter Meier <peter.meier@immerda.ch> - 3.2.0

 * (#14670) autorequire a file\_line resource's path (dfcee63)

##### 2012-11-19 - Joshua Harlan Lifton <lifton@puppetlabs.com> - 3.2.0

 * Add join\_keys\_to\_values function (ee0f2b3)

##### 2012-11-17 - Joshua Harlan Lifton <lifton@puppetlabs.com> - 3.2.0

 * Extend delete function for strings and hashes (7322e4d)

##### 2012-08-03 - Gary Larizza <gary@puppetlabs.com> - 3.2.0

 * Add the pick() function (ba6dd13)

##### 2012-03-20 - Wil Cooley <wcooley@pdx.edu> - 3.2.0

 * (#13974) Add predicate functions for interface facts (f819417)

##### 2012-11-06 - Joe Julian <me@joejulian.name> - 3.2.0

 * Add function, uriescape, to URI.escape strings. Redmine #17459 (70f4a0e)

##### 2012-10-25 - Jeff McCune <jeff@puppetlabs.com> - 3.1.1

 * (maint) Fix spec failures resulting from Facter API changes (97f836f)

##### 2012-10-23 - Matthaus Owens <matthaus@puppetlabs.com> - 3.1.0

 * Add PE facts to stdlib (cdf3b05)

##### 2012-08-16 - Jeff McCune <jeff@puppetlabs.com> - 3.0.1

 * Fix accidental removal of facts\_dot\_d.rb in 3.0.0 release

##### 2012-08-16 - Jeff McCune <jeff@puppetlabs.com> - 3.0.0

 * stdlib 3.0 drops support with Puppet 2.6
 * stdlib 3.0 preserves support with Puppet 2.7

##### 2012-08-07 - Dan Bode <dan@puppetlabs.com> - 3.0.0

 * Add function ensure\_resource and defined\_with\_params (ba789de)

##### 2012-07-10 - Hailee Kenney <hailee@puppetlabs.com> - 3.0.0

 * (#2157) Remove facter\_dot\_d for compatibility with external facts (f92574f)

##### 2012-04-10 - Chris Price <chris@puppetlabs.com> - 3.0.0

 * (#13693) moving logic from local spec\_helper to puppetlabs\_spec\_helper (85f96df)

##### 2012-10-25 - Jeff McCune <jeff@puppetlabs.com> - 2.5.1

 * (maint) Fix spec failures resulting from Facter API changes (97f836f)

##### 2012-10-23 - Matthaus Owens <matthaus@puppetlabs.com> - 2.5.0

 * Add PE facts to stdlib (cdf3b05)

##### 2012-08-15 - Dan Bode <dan@puppetlabs.com> - 2.5.0

 * Explicitly load functions used by ensure\_resource (9fc3063)

##### 2012-08-13 - Dan Bode <dan@puppetlabs.com> - 2.5.0

 * Add better docs about duplicate resource failures (97d327a)

##### 2012-08-13 - Dan Bode <dan@puppetlabs.com> - 2.5.0

 * Handle undef for parameter argument (4f8b133)

##### 2012-08-07 - Dan Bode <dan@puppetlabs.com> - 2.5.0

 * Add function ensure\_resource and defined\_with\_params (a0cb8cd)

##### 2012-08-20 - Jeff McCune <jeff@puppetlabs.com> - 2.5.0

 * Disable tests that fail on 2.6.x due to #15912 (c81496e)

##### 2012-08-20 - Jeff McCune <jeff@puppetlabs.com> - 2.5.0

 * (Maint) Fix mis-use of rvalue functions as statements (4492913)

##### 2012-08-20 - Jeff McCune <jeff@puppetlabs.com> - 2.5.0

 * Add .rspec file to repo root (88789e8)

##### 2012-06-07 - Chris Price <chris@puppetlabs.com> - 2.4.0

 * Add support for a 'match' parameter to file\_line (a06c0d8)

##### 2012-08-07 - Erik Dalén <dalen@spotify.com> - 2.4.0

 * (#15872) Add to\_bytes function (247b69c)

##### 2012-07-19 - Jeff McCune <jeff@puppetlabs.com> - 2.4.0

 * (Maint) use PuppetlabsSpec::PuppetInternals.scope (main) (deafe88)

##### 2012-07-10 - Hailee Kenney <hailee@puppetlabs.com> - 2.4.0

 * (#2157) Make facts\_dot\_d compatible with external facts (5fb0ddc)

##### 2012-03-16 - Steve Traylen <steve.traylen@cern.ch> - 2.4.0

 * (#13205) Rotate array/string randomley based on fqdn, fqdn\_rotate() (fef247b)

##### 2012-05-22 - Peter Meier <peter.meier@immerda.ch> - 2.3.3

 * fix regression in #11017 properly (f0a62c7)

##### 2012-05-10 - Jeff McCune <jeff@puppetlabs.com> - 2.3.3

 * Fix spec tests using the new spec\_helper (7d34333)

##### 2012-05-10 - Puppet Labs <support@puppetlabs.com> - 2.3.2

 * Make file\_line default to ensure => present (1373e70)
 * Memoize file\_line spec instance variables (20aacc5)
 * Fix spec tests using the new spec\_helper (1ebfa5d)
 * (#13595) initialize\_everything\_for\_tests couples modules Puppet ver (3222f35)
 * (#13439) Fix MRI 1.9 issue with spec\_helper (15c5fd1)
 * (#13439) Fix test failures with Puppet 2.6.x (665610b)
 * (#13439) refactor spec helper for compatibility with both puppet 2.7 and server (82194ca)
 * (#13494) Specify the behavior of zero padded strings (61891bb)

##### 2012-03-29 Puppet Labs <support@puppetlabs.com> - 2.1.3

* (#11607) Add Rakefile to enable spec testing
* (#12377) Avoid infinite loop when retrying require json

##### 2012-03-13 Puppet Labs <support@puppetlabs.com> - 2.3.1

* (#13091) Fix LoadError bug with puppet apply and puppet\_vardir fact

##### 2012-03-12 Puppet Labs <support@puppetlabs.com> - 2.3.0

* Add a large number of new Puppet functions
* Backwards compatibility preserved with 2.2.x

##### 2011-12-30 Puppet Labs <support@puppetlabs.com> - 2.2.1

* Documentation only release for the Forge

##### 2011-12-30 Puppet Labs <support@puppetlabs.com> - 2.1.2

* Documentation only release for PE 2.0.x

##### 2011-11-08 Puppet Labs <support@puppetlabs.com> - 2.2.0

* #10285 - Refactor json to use pson instead.
* Maint  - Add watchr autotest script
* Maint  - Make rspec tests work with Puppet 2.6.4
* #9859  - Add root\_home fact and tests

##### 2011-08-18 Puppet Labs <support@puppetlabs.com> - 2.1.1

* Change facts.d paths to match Facter 2.0 paths.
* /etc/facter/facts.d
* /etc/puppetlabs/facter/facts.d

##### 2011-08-17 Puppet Labs <support@puppetlabs.com> - 2.1.0

* Add R.I. Pienaar's facts.d custom facter fact
* facts defined in /etc/facts.d and /etc/puppetlabs/facts.d are
  automatically loaded now.

##### 2011-08-04 Puppet Labs <support@puppetlabs.com> - 2.0.0

* Rename whole\_line to file\_line
* This is an API change and as such motivating a 2.0.0 release according to semver.org.

##### 2011-08-04 Puppet Labs <support@puppetlabs.com> - 1.1.0

* Rename append\_line to whole\_line
* This is an API change and as such motivating a 1.1.0 release.

##### 2011-08-04 Puppet Labs <support@puppetlabs.com> - 1.0.0

* Initial stable release
* Add validate\_array and validate\_string functions
* Make merge() function work with Ruby 1.8.5
* Add hash merging function
* Add has\_key function
* Add loadyaml() function
* Add append\_line native

##### 2011-06-21 Jeff McCune <jeff@puppetlabs.com> - 0.1.7

* Add validate\_hash() and getvar() functions

##### 2011-06-15 Jeff McCune <jeff@puppetlabs.com> - 0.1.6

* Add anchor resource type to provide containment for composite classes

##### 2011-06-03 Jeff McCune <jeff@puppetlabs.com> - 0.1.5

* Add validate\_bool() function to stdlib

##### 0.1.4 2011-05-26 Jeff McCune <jeff@puppetlabs.com>

* Move most stages after main

##### 0.1.3 2011-05-25 Jeff McCune <jeff@puppetlabs.com>

* Add validate\_re() function

##### 0.1.2 2011-05-24 Jeff McCune <jeff@puppetlabs.com>

* Update to add annotated tag

##### 0.1.1 2011-05-24 Jeff McCune <jeff@puppetlabs.com>

* Add stdlib::stages class with a standard set of stages


\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
