# JSR-305

This project exists solely to extend JSR-305's nullability annotations with a `@NothingNull` package-level annotation that asserts that all fields, return values, and parameters are not null by default. You really get tired of typing `@Nonnull` after a while.

## Usage

Just add `@NothingNull` to all your package-info files and you're good to go.

## Maven

This project can be retrieved from [GPR](https://github.com/phantamanta44/jsr305/packages).
