# Good first issues

These are seeded starter tasks. Each one is small, testable, and needs no network access.

1. Add support for a "Shipper" and "Receiver" (or "Consignee") label pair, mapped to origin and destination when those labels are absent.
   Add parser tests for both labels and update the README field list.

2. Add a `--csv` output mode that prints one row per parsed file with columns for load number, origin, destination, dates, miles, and total rate.
   Add a CLI test that checks the header row and one data row.

3. Accept multi stop loads: collect extra "Stop" lines into a `stops` array in the JSON output, keeping origin and destination unchanged.
   Add parser tests with a two stop example.

4. Add a `--strict` flag that makes `--check` also fail when linehaul, fuel surcharge, or miles are missing, and document which fields each mode requires.
   Add CLI tests for both modes.
