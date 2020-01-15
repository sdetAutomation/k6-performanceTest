```                                                                      
#             .___      __     _____          __                         __  .__               
#    ______ __| _/_____/  |_  /  _  \  __ ___/  |_  ____   _____ _____ _/  |_|__| ____   ____  
#   /  ___// __ |/ __ \   __\/  /_\  \|  |  \   __\/  _ \ /     \\__  \\   __\  |/  _ \ /    \ 
#   \___ \/ /_/ \  ___/|  | /    |    \  |  /|  | (  <_> )  Y Y  \/ __ \|  | |  (  <_> )   |  \
#  /____  >____ |\___  >__| \____|__  /____/ |__|  \____/|__|_|  (____  /__| |__|\____/|___|  /
#       \/     \/    \/             \/                         \/     \/                    \/ 
```

# k6-performanceTest
example of how to use k6 load testing framework & execute tests as part of your ci pipeline.

[![Build Status](https://travis-ci.org/sdetAutomation/k6-performanceTest.svg?branch=master)](https://travis-ci.org/sdetAutomation/k6-performanceTest)

Introduction
------------
This project is made for anyone who is looking for a starting point for writing performance tests using k6. This solution also executes performance test as part of ci pipeline.

For more information regarding k6 please visit: https://www.k6.io

Project structure
-----
* examples:
Contains test example written in JS.


k6 installation
-----
These are the steps to set-up k6.

    - brew tap loadimpact/k6
    - brew install k6


Test api's
-----
http://services.groupkt.com/country/get/all

http://jsonplaceholder.typicode.com


Executing Test
------------
cd into examples folder:

Execute command line: `k6 run jsonplaceholder_example.js`


Continuous Integration(CI)
------------
A web hook has been setup with Travis CI for all Push and Pull Requests.  All tests run on check in and daily.


Questions / Contact / Contribute
------------
Feel free to fork this repo, add to it, and create a pull request if you like to contribute.

If you have any questions, you can contact me via email: `sdet.testautomation@gmail.com`
