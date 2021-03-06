## 1.3.1 - 2021 Jan 14
- Fix spelling of `Celsius` (@joseluis)

## 1.3.0 - 2020 Nov 29
- Added unit of mass `Stone`
- Added keyword `pounds-force` (used for `PoundsPerSquareInch`)
- Fixed lexing of `Pound`

## 1.2.0 - 2020 Nov 26
- Added units of electric current
- Added units of voltage
- Added units of resistance
- Added support for `Voltage * ElectricCurrent`
- Added support for `Voltage / ElectricCurrent`
- Added support for `Voltage / Resistance`
- Added support for `Power / ElectricCurrent`
- Added support for `Power / Voltage`
- Added support for `Power * Time`
- Added support for `ElectricCurrent * Resistance`
- Added support for `Energy / Time`
- Fixed dividing a unit by `NoUnit` resulting in `NoUnit`
- Fixed interpreting of `µs`
- Fixed panics caused in Rust `1.48.0` by switching `decimal` dependency to `decimal_fixes_mirror`

## 1.1.0 - 2020 Nov 14
- Added units of frequency
- Added support using foot-inch syntax with addition, like `2"+6'4"`
- Unsupported foot-inch syntax like `(6)'4"` and `6'4!"` now cause errors
- Fixed README.md stating the performance is 1000x slower than it actually is
- Fixed trailing percentage signs being ignored when `allow_trailing_operators` is true
- Fixed error caused by consecutive percentage signs

## 1.0.2 - 2020 Oct 12
- Fix parsing of unit `Quarter` (@ethwu)
- Use division instead of multiplication when dividing numbers of the same unit `Quarter` (@ethwu)

## 1.0.1 - 2020 Aug 20
- Fixed the library not working
- Added documentation comments
- Added docs.rs documentation link
- Various fixes and improvements

## 1.0.0 - 2020 Aug 20
- Initial release
