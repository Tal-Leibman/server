# Changelog

## Version 0.6.1
* Collection: save the UID on the model to use the db for enforcing uniqueness

## Version 0.6.0
* Fix stoken calculation performance - was VERY slow in some rare cases
* Fix issues with host verification failing with a custom port - part 2

## Version 0.5.3
* Add missing migration

## Version 0.5.2
* Fix issues with host verification failing with a custom port
* Add env variable to change configuration file path.
* Change user creation to not ask for a password (and clarify the readme).

## Version 0.5.1
* Enforce collections to always have a collection type set
* Collection saving: add another verification for collection UID uniqueness.

## Version 0.5.0
* First Etebase-server release (was EteSync-server before)
