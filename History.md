# History

## Master (unreleased)

- Fix returning to previous date after block when `Timecop.thread_safe = true` (#216)

## v0.9.2

- Make `require 'timecop'` threadsafe (#239)

## v0.9.1

- fix Date.parse when month/year only given (#206)

## v0.9.0

- add thread_safe option (#184)
- in safe mode, when already frozen, allow traveling with no block (#202)
- using Time.travel with a string should AS' Time.zone class (#170)
- fix Timecop being ignored when Date.parse infers year (#171, #158, #133)


## v0.9.2

- Make `require 'timecop'` threadsafe (#239)

## v0.9.1

- fix Date.parse when month/year only given (#206)

## v0.9.0

- add thread_safe option (#184)
- in safe mode, when already frozen, allow traveling with no block (#202)
- using Time.travel with a string should AS' Time.zone class (#170)
- fix Timecop being ignored when Date.parse infers year (#171, #158, #133)
