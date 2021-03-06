reusable-charts
===============

Plot data in cool Scalable Vector Graphcis plots (charts) using d3 with wrappers for common chart types (pie charts and line graphs).


DEVELOP
=======

1. Launch a command prompt
   
   * Linux: <CTRL><ALT>T
   * Windows: Start->Run->"Cmd" in Windows
   
2. Install git
   
   * Linux: `sudo aptitude install git`
   * Windows: `http://code.google.com/p/msysgit/downloads/list?q=full+installer+official+git`

2.1 Checkout git: from the command line type >git help

2.2 Generate SSh key from Git Bash console into your local computers .ssh folder

2.3 copy ssh key form local machine and paste it in the github or bitbucket web page under your account in the ssh keys list
   
3. `cd directory_where_you_want_to_put_the_source_code`

4. `git clone GIT_URI_LISTED_AT_github.com/hosbonlane/reusable-charts`

5. Make your changes

6. Update your local repository to record your changes:
   
   `git commit -a -m 'Notes about what you changed'`
   
7. Share your changes:
   
   `git push -u origin master`

8. Share more changes:
   
   `git push`

8. Keep up to date:
   
   `git pull`
   

INSTALL
-------

Just copy the javascript files into your web app path and include something like this in your HTML::

    <!-- D3 for plotting SVG graphics, charts, maps -->
    <script type="text/javascript" src="/static/js/d3.v2.js"></script>
    <!-- the main reusable-charts library -->
    <script type="text/javascript" src="/static/js/standard_charts.js"></script>
    <!-- Array.map() and other functions missing from some browsers -->
    <script type="text/javascript" src="/static/js/browser_compatibility.js"></script>
    <!-- geodesy calculations for mapping -->
    <script type="text/javascript" src="/static/js/geodesy.js"></script>
    <!-- not required, but the sylvester linear algebra library is great for things like $v() and $m() -->
    <!--    <script type="text/javascript" src="/static/js/sylvester.js"></script>-->

RUN
---

Point your browser to the examples.html page.


DOCUMENTATION
=============

Self-documenting, wouldn't you know ;)  We'd welcome your addition to the docs (wiki).

GOALS
=====

Comply with Mike Bostoks "best practices" as they evolve, based on his blog at [http://bost.ocks.org/mike/].

References and Inspiration: 
=====

1) http://www.tutorialspoint.com/javascript/array_map.htm
2) http://simonwillison.net/2004/may/26/addloadevent/ 
3) http://www.alistapart.com/articles/behavioralseparation
4) http://bost.ocks.org/mike/chart/

