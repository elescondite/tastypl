# Changelog

All notable changes to tastypl are documented in this file.

## 2021.03.07

### Added

- Crypto currency transaction handling (alpha). Only tested with simple buy/sell in ETH/USD
- Added crypto currency notional bought/sold totals to -daily and -cumulative options
- Add sample CSV output
- Add CHANGELOG.md (this file)

### Changed

- Updated README.md with command line options and sample -daily output

## 2021.02.27

### Removed

- Removed all `Net Liquidation` calculations. Without proper marked-to-market data, this is simply misleading

## 2021.02.21

### Added 

- Add new small exchange futures /S2Y and /S30Y	

### Changed

- Fix another case of the smalls futures using a 2 digit year when all other futures use 1. Happened only on expiration.	
- Re-work -daily output. Add daily activity as well as cumulative to date columns. New command line option -daily-todate (default true)	

## 2021.02.13

### Added

- First attempt to dump a daily CSV of balances with -daily command line option
- Add Net Liquidation value to chart. 

### Changed

- Default chart size is now 1920x1080

## 2020.10.16

### Added

- Add -chartNoCash option to exclude cash from chart of P&L

### Changed

- Bug fix. Recent updates to tastyworks have meant that commissions columns can use "--" as well as "0.00"

## 2020.08.18

### Added

- Added more futures symbols. /SIL /HG /MJY /6M /STIX /MCD

## 2020.07.10 - Initial Fork

### Added

- Initial fork from [](https://github.com/gotasty/tastypl)
- Add small exchange futures detection

