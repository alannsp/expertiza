Expertiza
=========

[![Build Status](https://travis-ci.org/expertiza/expertiza.png?branch=rails4)](https://travis-ci.org/expertiza/expertiza)
[![Code Climate](https://codeclimate.com/github/expertiza/expertiza.png)](https://codeclimate.com/github/expertiza/expertiza)
[![Coverage Status](https://coveralls.io/repos/expertiza/expertiza/badge.png?branch=rails4)](https://coveralls.io/r/expertiza/expertiza?branch=rails4)

###E1510. Fix Instructor Login Performance Issue
###Problem description
Currently when an Instructor logs into Expertiza,there a lot of select* from assignments queries being fired on database which would have an adverse effect on performance.
Analyze and reduce the number of select queries executed to improve the performance.
<img align=left src="https://github.com/fwu8/expertiza/blob/master/photo/before_modify.png" style="float:left;with:100px;height:300px">
![Alt text](https://github.com/fwu8/expertiza/tree/master/photo/before_modify.png?raw=true "optional Title")

###Use Query Reviewer to trace the queries
![Alt text](https://github.com/fwu8/expertiza/blob/master/photo/Screenshot%20from%202015-03-14%2018:47:51.png?raw=true "optional Title")



 * [OSX](http://wikis.lib.ncsu.edu/index.php/Creating_a_Mac_OS_X_Development_Environment_for_the_Expertiza_Application)
 * [Linux](http://wikis.lib.ncsu.edu/index.php/Creating_a_Linux_Development_Environment_for_the_Expertiza_Application)
 * [Windows](http://wikis.lib.ncsu.edu/index.php/Creating_a_Windows_Development_Environment_for_the_Expertiza_Application)

Contributing
------------

 * [Fork](http://help.github.com/fork-a-repo/) the expertiza project
 * [Create a new branch](http://progit.org/book) for your contribution with a descriptive name
 * [Commit and push](http://progit.org/book) until you are happy with your contribution - follow the style guidelines below
 * Make sure to add tests for it; the tests should fail before your contribution/fix and pass afterward
 * [Send a pull request](http://help.github.com/send-pull-requests) to have your code reviewed for merging back into Expertiza

