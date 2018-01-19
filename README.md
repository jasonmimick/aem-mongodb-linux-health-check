aem-mongodb-linux-health-check
==============================

~~~~
python ./aem-mongodb-linux-health-check.py --help
usage: aem-mongodb-linux-health-check.py [-h] [--verbose]
                                         [--format {pretty,yaml,json}]
                                         [--tests TESTS]

aem-mongodb-linux-health-check

optional arguments:
  -h, --help            show this help message and exit
  --verbose             Output verbose report.
  --format {pretty,yaml,json}
                        Specify the report output format
  --tests TESTS         Override default yaml file with test definitions

aem-mongodb-linux-health check is a tool which runs system commands to
validate recommended settings found in the MongoDB Production Notes. The
output of this tool is for informational purposes only and not intended to be
an official or certified report. The tool does require root-level privileges
to function properly.
~~~~
