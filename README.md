# java-cli-maven-hibernate-oracle-trigger

## Description
Creates a small database table
called `dog` and populates with hql.

Added an insert trigger to `dog`.

## Tech stack
- java
- maven
  - hibernate
  - hql
  - envers
  - log4j
  - oracle driver

## Docker stack
- maven:3-openjdk-17
- gvenzl/oracle-free

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
