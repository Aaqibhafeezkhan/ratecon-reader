# Changelog

## v1.0.0

- Initial release.
- Parses load number, broker name and MC number, origin, destination, pickup and delivery dates, total rate, linehaul, fuel surcharge, miles, weight, commodity, and detention or layover notes.
- Handles label variants such as Load #, Load No, Rate, Total, Miles, Origin, Destination, Pick Up, and Delivery, plus money formats like $1,234.50 and 1234.50.
- CLI flags: file or stdin input, `--json` (default), `--summary`, and `--check`.
- 23 node:test tests, all passing.
