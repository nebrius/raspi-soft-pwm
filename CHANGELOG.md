## 4.0.1 (2017-9-12)

- Updated dependencies. The breaking changes in dependencies do not break the behavior of this module.

## 4.0.0 (2017-9-12)

- BREAKING CHANGE: dropped support for Node.js < 4.0.0, and now enforce it via package.json "engines" field.
- SORT OF BREAKING-ISH CHANGE: dropped support for attempting to install on non-arm platforms via package.json's "cpu" field.
    - Attempting to install this on a non-Raspberry Pi platform before gave a bunch of obtuse errors, so this doesn't _actually_ change the ability to install raspi-soft-pwm, but does make it fail earlier and harder.

## 3.0.0 (2017-04-26)

- Updated the project to TypeScript
- BREAKING CHANGE: changed `write()` to accept a duty cycle between 0 and 1 instead of an integer between 0 and the range to match raspi-pwm

## 2.0.2 (2017-01-02)

- Fixed a bug when the WiringPi number is 0

## 2.0.1 (2016-11-29)

- Fixed a bug with sending fractional values in

## 2.0.0 (2016-11-28)

- Added `frequency` getter
- BREAKING CHANGE: Removed default pin value

## 1.0.1 (2016-11-02)

- Added `range` getter

## 0.9.1 (2016-09-04)

- Update dependencies

## 0.9.0 (2016-03-10)

- Initial implementation
