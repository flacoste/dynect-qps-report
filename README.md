dynect-qps-report
=================

Use the DynECT API to get a by host QPS report in CSV.

Usage and installation
----------------------

    $ bundle install
    $ bin/dynect-qps-report -c CUSTOMER_NAME -u USER_NAME -p PASSWORD zone.com
  
Pass as parameters the list of zones you want the report for.

The --start-time and --end-time can be used to control the start and end
time of the report. (Note that DynECT limits to 45 days the span on
which it will report).

Environment Configuration
-------------------------

* `CUSTOMER_NAME` - the DynECT customer_name API credential
* `USERNAME` - the DynECT user_name API credential
* `PASSWORD` - the DynECT password API credential
* `START_TIME`  - start of the report (human readable time format accepted)
* `END_TIME` - end of the report (human readable time format accepted) 
* `OUTPUT_FILE` - where the CSV report will be saved

Copyright
---------

(The MIT License)

Copyright (c) 2013 [Heroku](http://github.com/heroku)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

