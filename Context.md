# ApoorvaUtilities

Foundation-only helpers shared by every other package. No dependencies.

## Quick Index

- **Layout** — extensions on `Array`/`Dictionary`/`Bool`/`Int`/`Int64`/`Double`/`String`/`Date` + `SortType`, one test file per extension.
- **Rules** — date/number formatting must be locale/timezone-independent; no domain types (those belong in `ApoorvaModels`).
- **Commands** — `swift test` / `swift test --filter <Name>`.

## Layout
- `Sources/ApoorvaUtilities/` — extensions on `Array`, `Dictionary`, `Bool`, `Int`, `Int64`, `Double`, `String`, `Date`, plus `SortType`.
- `Tests/ApoorvaUtilitiesTests/` — one test file per extension.

## Rules
- Date and number formatting must not depend on the machine locale. Tests must pin locale and time zone.
- Keep this package free of domain types. Those belong in `ApoorvaModels`.

## Commands
```bash
swift test
swift test --filter DateExtensionTests
```
