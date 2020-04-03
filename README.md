# Solr tools

Author: Jan Høydahl @ Cominvent AS

Collection of simple tools for Solr.

[![Travis CI Build Status](https://travis-ci.org/cominvent/solr-tools.png)](https://travis-ci.org/cominvent/solr-tools)

## upgradeindex.sh
Bash script to upgrade an entire Solr index from 4.x or 5.x to 6.x so it can be read by Solr6.x or Solr 7.x. See [README](./upgradeindex/README.md)

## SolrPasswordHash
Simple command line tool to generate a password hash for `security.json`

### Build

    mvn package

### Usage:

    java -jar target/solr-tools-1.0-SNAPSHOT.jar admin 123
    HZtl83vopLyZfOpGedEQveAwvVdAQ1Ukr6dDJPEfs/w= MTIz
    
# License

All tools © [Cominvent AS](www.cominvent.com) and licensed under the Apache License v2.0
