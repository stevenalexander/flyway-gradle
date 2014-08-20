# Flyway gradle

Simple Flyway tutorial sample using H2 with a couple of migration scripts.

## Run

Creates an H2 DB populated with the migration scripts in src/main/resources/db/migration

```
gradle flywayMigrate -i
```