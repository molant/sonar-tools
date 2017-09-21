# Description

`crawler` can be used to scan a list of websites stored in a text file
where each line is a URL.

This script is used to to check the stability and performance of
`sonar`.

## Usage

1. Update the `.sonarrc` file to the desired configuration
1. Update `urls.txt` with the urls to analyze
1. Run the following command (assumes code is compiled and in the dist)
   folder: `node crawler.js urls.txt`

By default `crawler` will scan 10 URLs simultaneously. You can change
that behavior via the command line. The following will scan 5 sites
simultaneously `node crawler.js urls.txt 5`.

You can also use `npm script crawl` to run the defaults.
