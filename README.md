# Automagic Flow Viewer (HTML/JavaScript)
Recreates [Gridvision Engineering GmbH Automagic](http://automagic4android.com/en/)'s flow viewing by parsing flows XML files in HTML/JavaScript.

Uses [jgraph](https://github.com/jgraph/mxgraph/)'s 'mxGraph' Javascript third party library. Info about the license can be found in the GitHub repository.

Built for [Automagic Premium](https://play.google.com/store/apps/details?id=ch.gridvision.ppam.androidautomagic) 1.30.0

Backward and forward compatibility depends on changes made to the structure of XML files.

## To test
Since the index.html page tries to open another file, a webserver has to be set up, using "file://" to open the file on a browser will not work.

As viewed on a Windows Google Chrome browser:
![SOS](http://automagic4android.com/forum/download/file.php?id=698&sid=896a9ce04aa3f8e0d84fe326d0a0bf45)
