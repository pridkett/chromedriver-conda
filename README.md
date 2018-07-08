Anaconda Build Package for ChromeDriver
=======================================

Patrick Wagstrom &lt;patrick@wagstrom.net&gt;

April 2017

This is a really simple Conda build file that installs the ChromeDriver for Selenium. I had been using another package, but unfortunately there were some recent changes required in ChromeDriver that make it so it can't save PNGs anymore. This should give us the most up to date version of ChromeDriver.

Usage
-----

    conda build .
    conda install selenium-chromedriver --use-local

License
-------

The scripts in this build package are licensed under the terms of the MIT license.