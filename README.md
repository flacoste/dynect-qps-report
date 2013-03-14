dynect-qps-report
=================

Use the DynECT API to get a by host QPS report in CSV.

Usage and installation
----------------------

    $ bundle install
    $ bin/dynect-qps-report -c CUSTOMER_NAME -u USER_NAME -p PASSWORD
  
The --start-time and --end-time can be used to control the start and end
time of the report. (Note that DynECT limits to 45 days the span on
which it will report).

Environment Configuration
-------------------------

* CUSTOMER_NAME -- the DynECT customer_name API credential
* USERNAME -- the DynECT user_name API credential
* PASSWORD -- the DynECT password API credential
* START_TIME -- start of the report (human readable time format accepted)
* END_TIME -- end of the report (human readable time format accepted) 
* OUTPUT_FILE -- where the CSV report will be saved

