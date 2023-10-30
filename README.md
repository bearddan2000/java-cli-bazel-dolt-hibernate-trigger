# java-cli-bazel-dolt-hibernate-trigger

## Description
Creates a small database table
called `dog` and populates with hql.

Added an insert trigger to `dog`.

## Tech stack
- java
- bazel
  - hibernate
  - hql
  - log4j
  - dolt driver

## Docker stack
- l.gcr.io/google/bazel:latest
- dolthub/dolt-sql-serverdb

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
