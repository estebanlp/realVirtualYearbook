---
title       : Creating a Virtual Yearbook of the REAL Mafia
subtitle    : Exploring its members' memories and connections
author      : Esteban Lopez
job         : UIUC PhD Candidate, REAL 'General'
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz, mathjax]
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

---

## Outline

>1. The Instrument
>2. Exploratory Analysis
>3. The REAL Mafia in a Network context
  - Academic
  - Friendship
>4. Spatial Analysis
>5. The REAL Virtual Yearbook
>6. Memories Semantic Analysis


--- 

## The Instrument

<!-- Table generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 19:13:57 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataTableID124d5e29153e () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Identification",
"Name, Country, Affiliation, etc." 
],
[
 "Time in REAL",
"Dates, Mafia role, General, sitting, etc." 
],
[
 "Academics with REAL",
"Research areas, collaboration, influences, post-mafia work." 
],
[
 "REAL Memories and Annecdotes",
"CU, UIUC, REAL, Geoff" 
] 
];
data.addColumn('string','Section');
data.addColumn('string','Description');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartTableID124d5e29153e() {
var data = gvisDataTableID124d5e29153e();
var options = {};
options["allowHtml"] = true;
options["width"] =    800;
options["height"] =    300;

    var chart = new google.visualization.Table(
    document.getElementById('TableID124d5e29153e')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "table";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartTableID124d5e29153e);
})();
function displayChartTableID124d5e29153e() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartTableID124d5e29153e"></script>
 
<!-- divChart -->
  
<div id="TableID124d5e29153e" 
  style="width: 800; height: 300;">
</div>
<!-- Table generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 19:13:57 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataTableID124d5e29153e () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Identification",
"Name, Country, Affiliation, etc." 
],
[
 "Time in REAL",
"Dates, Mafia role, General, sitting, etc." 
],
[
 "Academics with REAL",
"Research areas, collaboration, influences, post-mafia work." 
],
[
 "REAL Memories and Annecdotes",
"CU, UIUC, REAL, Geoff" 
] 
];
data.addColumn('string','Section');
data.addColumn('string','Description');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartTableID124d5e29153e() {
var data = gvisDataTableID124d5e29153e();
var options = {};
options["allowHtml"] = true;
options["width"] =    800;
options["height"] =    300;

    var chart = new google.visualization.Table(
    document.getElementById('TableID124d5e29153e')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "table";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartTableID124d5e29153e);
})();
function displayChartTableID124d5e29153e() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartTableID124d5e29153e"></script>
 
<!-- divChart -->
  
<div id="TableID124d5e29153e" 
  style="width: 800; height: 300;">
</div>
<br>

- Sampled REAL Mafia: _400 (aprox.) e-mails sent_
- Number of Respondents REAL Mafia: _104 responded surveys_
- Number of attendants to this event: _120 aprox._ 

---

## The 'Actual' Instrument

<iframe src="https://docs.google.com/forms/d/1B3qXUtLhqH7JSpo1zLH0DZeEzPPt0YIXEMp48NUA0eI/viewform?edit_requested=true" heingt='600px'></iframe>

--- .segue bg:indigo

## Exploratory Analysis

---  &vcenter

## Demographic Frequencies


<table style="text-align:center"><tr><td colspan="5" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td>Degree</td><td>Affiliation</td><td>Position</td><td>Mafia Type</td></tr>
<tr><td colspan="5" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td>BA : 3</td><td>University of Oviedo: 4</td><td>Professor :16</td><td>Master Student : 1</td></tr>
<tr><td style="text-align:left"></td><td>MA : 2</td><td>CEDEPLAR/UFMG : 3</td><td>Assistant Professor: 8</td><td>Other : 2</td></tr>
<tr><td style="text-align:left"></td><td>MS :13</td><td>UIUC : 3</td><td>Associate Professor: 8</td><td>PhD and Master Student: 4</td></tr>
<tr><td style="text-align:left"></td><td>Other: 1</td><td>CIDE : 2</td><td>PhD Candidate : 8</td><td>PhD Student :43</td></tr>
<tr><td style="text-align:left"></td><td>PhD :85</td><td>OECD : 2</td><td>Economist : 4</td><td>Visiting Scholar :54</td></tr>
<tr><td style="text-align:left"></td><td></td><td>REAL : 2</td><td>Full Professor : 3</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(Other) :88</td><td>(Other) :57</td><td></td></tr>
<tr><td colspan="5" style="border-bottom: 1px solid black"></td></tr></table>

---  &vcenter

## Initial Country


<!-- GeoChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 14:12:58 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartIDe881267fb4 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Argentina",
1 
],
[
 "Austria",
4 
],
[
 "Brazil",
22 
],
[
 "Chile",
5 
],
[
 "China",
8 
],
[
 "Colombia",
7 
],
[
 "Spain",
13 
],
[
 "France",
1 
],
[
 "Greece",
1 
],
[
 "Guatemala",
1 
],
[
 "Honduras",
1 
],
[
 "Hong Kong",
1 
],
[
 "Indonesia",
1 
],
[
 "Ireland",
1 
],
[
 "Italia",
1 
],
[
 "Italy",
4 
],
[
 "Japan",
7 
],
[
 "Korea",
5 
],
[
 "Mexico",
1 
],
[
 "Netherlands",
1 
],
[
 "PERU",
1 
],
[
 "Poland",
1 
],
[
 "Portugal",
2 
],
[
 "Republic of Korea",
1 
],
[
 "Scotland",
1 
],
[
 "South Korea",
1 
],
[
 "Turkey",
6 
],
[
 "UK",
1 
],
[
 "USA",
3 
],
[
 "Vietnam",
1 
] 
];
data.addColumn('string','Var1');
data.addColumn('number','Freq');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartGeoChartIDe881267fb4() {
var data = gvisDataGeoChartIDe881267fb4();
var options = {};
options["width"] =    800;
options["height"] =    500;

    var chart = new google.visualization.GeoChart(
    document.getElementById('GeoChartIDe881267fb4')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "geochart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartGeoChartIDe881267fb4);
})();
function displayChartGeoChartIDe881267fb4() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoChartIDe881267fb4"></script>
 
<!-- divChart -->
  
<div id="GeoChartIDe881267fb4" 
  style="width: 800; height: 500;">
</div>
<!-- GeoChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 14:12:58 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartIDe881267fb4 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Argentina",
1 
],
[
 "Austria",
4 
],
[
 "Brazil",
22 
],
[
 "Chile",
5 
],
[
 "China",
8 
],
[
 "Colombia",
7 
],
[
 "Spain",
13 
],
[
 "France",
1 
],
[
 "Greece",
1 
],
[
 "Guatemala",
1 
],
[
 "Honduras",
1 
],
[
 "Hong Kong",
1 
],
[
 "Indonesia",
1 
],
[
 "Ireland",
1 
],
[
 "Italia",
1 
],
[
 "Italy",
4 
],
[
 "Japan",
7 
],
[
 "Korea",
5 
],
[
 "Mexico",
1 
],
[
 "Netherlands",
1 
],
[
 "PERU",
1 
],
[
 "Poland",
1 
],
[
 "Portugal",
2 
],
[
 "Republic of Korea",
1 
],
[
 "Scotland",
1 
],
[
 "South Korea",
1 
],
[
 "Turkey",
6 
],
[
 "UK",
1 
],
[
 "USA",
3 
],
[
 "Vietnam",
1 
] 
];
data.addColumn('string','Var1');
data.addColumn('number','Freq');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartGeoChartIDe881267fb4() {
var data = gvisDataGeoChartIDe881267fb4();
var options = {};
options["width"] =    800;
options["height"] =    500;

    var chart = new google.visualization.GeoChart(
    document.getElementById('GeoChartIDe881267fb4')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "geochart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartGeoChartIDe881267fb4);
})();
function displayChartGeoChartIDe881267fb4() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoChartIDe881267fb4"></script>
 
<!-- divChart -->
  
<div id="GeoChartIDe881267fb4" 
  style="width: 800; height: 500;">
</div>

---  &vcenter

## Current Country


<!-- GeoChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 14:12:58 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartIDe8868a0303 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Australia",
1 
],
[
 "Austria",
4 
],
[
 "Brazil",
13 
],
[
 "USA",
38 
],
[
 "Chile",
3 
],
[
 "China",
2 
],
[
 "Colombia",
3 
],
[
 "Spain",
14 
],
[
 "France",
2 
],
[
 "Guatemala",
1 
],
[
 "Ireland",
1 
],
[
 "Italia",
1 
],
[
 "Italy",
3 
],
[
 "Japan",
4 
],
[
 "Korea",
3 
],
[
 "Mexico",
2 
],
[
 "Netherlands",
1 
],
[
 "Portugal",
3 
],
[
 "Sweden",
1 
],
[
 "Turkey",
2 
],
[
 "United Kingdom",
2 
] 
];
data.addColumn('string','Var1');
data.addColumn('number','Freq');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartGeoChartIDe8868a0303() {
var data = gvisDataGeoChartIDe8868a0303();
var options = {};
options["width"] =    800;
options["height"] =    500;

    var chart = new google.visualization.GeoChart(
    document.getElementById('GeoChartIDe8868a0303')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "geochart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartGeoChartIDe8868a0303);
})();
function displayChartGeoChartIDe8868a0303() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoChartIDe8868a0303"></script>
 
<!-- divChart -->
  
<div id="GeoChartIDe8868a0303" 
  style="width: 800; height: 500;">
</div>
<!-- GeoChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 14:12:58 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartIDe8868a0303 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Australia",
1 
],
[
 "Austria",
4 
],
[
 "Brazil",
13 
],
[
 "USA",
38 
],
[
 "Chile",
3 
],
[
 "China",
2 
],
[
 "Colombia",
3 
],
[
 "Spain",
14 
],
[
 "France",
2 
],
[
 "Guatemala",
1 
],
[
 "Ireland",
1 
],
[
 "Italia",
1 
],
[
 "Italy",
3 
],
[
 "Japan",
4 
],
[
 "Korea",
3 
],
[
 "Mexico",
2 
],
[
 "Netherlands",
1 
],
[
 "Portugal",
3 
],
[
 "Sweden",
1 
],
[
 "Turkey",
2 
],
[
 "United Kingdom",
2 
] 
];
data.addColumn('string','Var1');
data.addColumn('number','Freq');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartGeoChartIDe8868a0303() {
var data = gvisDataGeoChartIDe8868a0303();
var options = {};
options["width"] =    800;
options["height"] =    500;

    var chart = new google.visualization.GeoChart(
    document.getElementById('GeoChartIDe8868a0303')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "geochart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartGeoChartIDe8868a0303);
})();
function displayChartGeoChartIDe8868a0303() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoChartIDe8868a0303"></script>
 
<!-- divChart -->
  
<div id="GeoChartIDe8868a0303" 
  style="width: 800; height: 500;">
</div>

--- 
## Duration in REAL

<!-- Histogram generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sat Nov  8 10:36:58 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataHistogramID391111c80526 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 11 
],
[
 12 
],
[
 13 
],
[
 26 
],
[
 18 
],
[
 51 
],
[
 24 
],
[
 3 
],
[
 3 
],
[
 22 
],
[
 5 
],
[
 4 
],
[
 12 
],
[
 0 
],
[
 12 
],
[
 60 
],
[
 5 
],
[
 30 
],
[
 3 
],
[
 21 
],
[
 19 
],
[
 48 
],
[
 12 
],
[
 43 
],
[
 43 
],
[
 3 
],
[
 2 
],
[
 2 
],
[
 24 
],
[
 12 
],
[
 52 
],
[
 3 
],
[
 18 
],
[
 3 
],
[
 56 
],
[
 36 
],
[
 4 
],
[
 18 
],
[
 20 
],
[
 1 
],
[
 13 
],
[
 36 
],
[
 11 
],
[
 3 
],
[
 59 
],
[
 48 
],
[
 38 
],
[
 9 
],
[
 60 
],
[
 12 
],
[
 60 
],
[
 3 
],
[
 55 
],
[
 12 
],
[
 40 
],
[
 12 
],
[
 42 
],
[
 3 
],
[
 36 
],
[
 2 
],
[
 48 
],
[
 32 
],
[
 11 
],
[
 11 
],
[
 5 
],
[
 10 
],
[
 27 
],
[
 9 
],
[
 12 
],
[
 6 
],
[
 54 
],
[
 60 
],
[
 0 
],
[
 13 
],
[
 72 
],
[
 3 
],
[
 50 
],
[
 5 
],
[
 7 
],
[
 30 
],
[
 24 
],
[
 1 
],
[
 16 
],
[
 60 
],
[
 15 
],
[
 15 
],
[
 4 
],
[
 36 
],
[
 24 
],
[
 48 
],
[
 24 
],
[
 26 
],
[
 3 
],
[
 12 
],
[
 38 
],
[
 6 
],
[
 46 
],
[
 53 
],
[
 59 
],
[
 7 
],
[
 24 
],
[
 26 
],
[
 12 
],
[
 18 
] 
];
data.addColumn('number','months_total');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartHistogramID391111c80526() {
var data = gvisDataHistogramID391111c80526();
var options = {};
options["allowHtml"] = true;
options["width"] =    800;
options["height"] =    350;
options["legend"] = {position:'top'};
options["legend.alignment"] = "end";

    var chart = new google.visualization.Histogram(
    document.getElementById('HistogramID391111c80526')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartHistogramID391111c80526);
})();
function displayChartHistogramID391111c80526() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartHistogramID391111c80526"></script>
 
<!-- divChart -->
  
<div id="HistogramID391111c80526" 
  style="width: 800; height: 350;">
</div>
- Mafia type by duration:
  - _0-14_: Short term scholars (Spaniards & Brazilian Sandwich Mostly)
  - _14-28_: Long term scholars & Masters
  - _28+_: PhD Students and REAL lovers.

--- .segue bg:indigo

## Academics at REAL

--- &twocol w1:45% w2:35% &vcenter

## 1st most important research area at REAL.
*** =left
<!-- PieChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Fri Nov  7 06:28:48 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataPieChartID2fc1789f2fb9 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Environmental and Natural Resources",
5 
],
[
 "Innovation and Regional Economic Development",
2 
],
[
 "Location and Interaction",
6 
],
[
 "New Economic Geography and Evolutionary Economic Geography",
3 
],
[
 "Other",
22 
],
[
 "Regional Economic Growth",
30 
],
[
 "Regional Housing and Labor Markets",
17 
],
[
 "Spatial Analysis and Geocomputation",
4 
],
[
 "Spatial Econometrics",
12 
],
[
 "Spatial Statistics",
3 
] 
];
data.addColumn('string','Var1');
data.addColumn('number','Freq');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartPieChartID2fc1789f2fb9() {
var data = gvisDataPieChartID2fc1789f2fb9();
var options = {};
options["allowHtml"] = true;
options["width"] =    600;
options["height"] =    550;
options["legend"] = "none";

    var chart = new google.visualization.PieChart(
    document.getElementById('PieChartID2fc1789f2fb9')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartPieChartID2fc1789f2fb9);
})();
function displayChartPieChartID2fc1789f2fb9() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartPieChartID2fc1789f2fb9"></script>
 
<!-- divChart -->
  
<div id="PieChartID2fc1789f2fb9" 
  style="width: 600; height: 550;">
</div>
<!-- PieChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Fri Nov  7 06:28:48 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataPieChartID2fc1789f2fb9 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Environmental and Natural Resources",
5 
],
[
 "Innovation and Regional Economic Development",
2 
],
[
 "Location and Interaction",
6 
],
[
 "New Economic Geography and Evolutionary Economic Geography",
3 
],
[
 "Other",
22 
],
[
 "Regional Economic Growth",
30 
],
[
 "Regional Housing and Labor Markets",
17 
],
[
 "Spatial Analysis and Geocomputation",
4 
],
[
 "Spatial Econometrics",
12 
],
[
 "Spatial Statistics",
3 
] 
];
data.addColumn('string','Var1');
data.addColumn('number','Freq');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartPieChartID2fc1789f2fb9() {
var data = gvisDataPieChartID2fc1789f2fb9();
var options = {};
options["allowHtml"] = true;
options["width"] =    600;
options["height"] =    550;
options["legend"] = "none";

    var chart = new google.visualization.PieChart(
    document.getElementById('PieChartID2fc1789f2fb9')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartPieChartID2fc1789f2fb9);
})();
function displayChartPieChartID2fc1789f2fb9() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartPieChartID2fc1789f2fb9"></script>
 
<!-- divChart -->
  
<div id="PieChartID2fc1789f2fb9" 
  style="width: 600; height: 550;">
</div>

*** =right

>- <strong> within Regional Economic Growth falls:</strong>
    - Neoclasical, Endogenous & Spatial Growth Models
    - CGEs, static, dynamic and spatial
    - Regional growth and convergence
    - Spatial Policy for Growth and Equity

>- _together Growth, Spatial Econometrics, Housing & Labor make up to 63%_

--- &twocol w1:45% w2:35% &vcenter

## 2nd most important research area at REAL.
*** =left
<!-- PieChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Fri Nov  7 06:33:32 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataPieChartID2ff556c25684 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Environmental and Natural Resources",
5 
],
[
 "Innovation and Regional Economic Development",
5 
],
[
 "Location and Interaction",
8 
],
[
 "New Economic Geography and Evolutionary Economic Geography",
4 
],
[
 "Other",
14 
],
[
 "Regional Economic Growth",
26 
],
[
 "Regional Housing and Labor Markets",
6 
],
[
 "Spatial Analysis and Geocomputation",
8 
],
[
 "Spatial Econometrics",
20 
],
[
 "Spatial Statistics",
8 
] 
];
data.addColumn('string','Var1');
data.addColumn('number','Freq');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartPieChartID2ff556c25684() {
var data = gvisDataPieChartID2ff556c25684();
var options = {};
options["allowHtml"] = true;
options["width"] =    600;
options["height"] =    550;
options["legend"] = "none";

    var chart = new google.visualization.PieChart(
    document.getElementById('PieChartID2ff556c25684')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartPieChartID2ff556c25684);
})();
function displayChartPieChartID2ff556c25684() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartPieChartID2ff556c25684"></script>
 
<!-- divChart -->
  
<div id="PieChartID2ff556c25684" 
  style="width: 600; height: 550;">
</div>
<!-- PieChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Fri Nov  7 06:33:32 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataPieChartID2ff556c25684 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Environmental and Natural Resources",
5 
],
[
 "Innovation and Regional Economic Development",
5 
],
[
 "Location and Interaction",
8 
],
[
 "New Economic Geography and Evolutionary Economic Geography",
4 
],
[
 "Other",
14 
],
[
 "Regional Economic Growth",
26 
],
[
 "Regional Housing and Labor Markets",
6 
],
[
 "Spatial Analysis and Geocomputation",
8 
],
[
 "Spatial Econometrics",
20 
],
[
 "Spatial Statistics",
8 
] 
];
data.addColumn('string','Var1');
data.addColumn('number','Freq');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartPieChartID2ff556c25684() {
var data = gvisDataPieChartID2ff556c25684();
var options = {};
options["allowHtml"] = true;
options["width"] =    600;
options["height"] =    550;
options["legend"] = "none";

    var chart = new google.visualization.PieChart(
    document.getElementById('PieChartID2ff556c25684')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartPieChartID2ff556c25684);
})();
function displayChartPieChartID2ff556c25684() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartPieChartID2ff556c25684"></script>
 
<!-- divChart -->
  
<div id="PieChartID2ff556c25684" 
  style="width: 600; height: 550;">
</div>
*** =right
>- All spatial sciences grow in importance
>- Further survey should have a finer categorization

--- &vcenter

## Productivity by Research Area (1st)

<!-- ColumnChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sat Nov  8 12:08:53 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataColumnChartID3c7a7fc7466f () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "1",
1,
2,
2,
1,
8,
11,
3,
3,
0,
2 
],
[
 "2 to 3",
2,
0,
1,
1,
11,
13,
9,
1,
7,
1 
],
[
 "4 to 5",
2,
0,
2,
1,
0,
3,
4,
0,
2,
0 
],
[
 "More than 5",
0,
0,
1,
0,
3,
3,
1,
0,
3,
0 
] 
];
data.addColumn('string','working_papers');
data.addColumn('number','Environmental');
data.addColumn('number','Reg. Econ. Dev.');
data.addColumn('number','Location and Interaction');
data.addColumn('number','NEG');
data.addColumn('number','Other');
data.addColumn('number','Econ. Growth');
data.addColumn('number','Housing & Labor Mark.');
data.addColumn('number','Geocomputation');
data.addColumn('number','Spatial Econometrics');
data.addColumn('number','Spatial Statistics');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartColumnChartID3c7a7fc7466f() {
var data = gvisDataColumnChartID3c7a7fc7466f();
var options = {};
options["allowHtml"] = true;
options["width"] =    950;
options["height"] =    500;
options["vAxis"] = {title:'Frequency'};

    var chart = new google.visualization.ColumnChart(
    document.getElementById('ColumnChartID3c7a7fc7466f')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartColumnChartID3c7a7fc7466f);
})();
function displayChartColumnChartID3c7a7fc7466f() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartColumnChartID3c7a7fc7466f"></script>
 
<!-- divChart -->
  
<div id="ColumnChartID3c7a7fc7466f" 
  style="width: 950; height: 500;">
</div>

--- &vcenter
## Productivity by Research Area (1st) & No. of Months

<!-- ColumnChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sat Nov  8 12:08:53 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataColumnChartID3c7a73e162f2 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "1",
18,
14.5,
7.5,
3,
14.5,
16.09090909,
7,
17.33333333,
null,
2.5 
],
[
 "2 to 3",
12,
null,
19,
3,
14.09090909,
15.69230769,
33.11111111,
60,
17.57142857,
48 
],
[
 "4 to 5",
31,
null,
57,
46,
null,
40.66666667,
41,
null,
15,
null 
],
[
 "More than 5",
null,
null,
52,
null,
57.33333333,
56,
24,
null,
15.33333333,
null 
] 
];
data.addColumn('string','working_papers');
data.addColumn('number','Environmental');
data.addColumn('number','Reg. Econ. Dev.');
data.addColumn('number','Location and Interaction');
data.addColumn('number','NEG');
data.addColumn('number','Other');
data.addColumn('number','Econ. Growth');
data.addColumn('number','Housing & Labor Mark.');
data.addColumn('number','Geocomputation');
data.addColumn('number','Spatial Econometrics');
data.addColumn('number','Spatial Statistics');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartColumnChartID3c7a73e162f2() {
var data = gvisDataColumnChartID3c7a73e162f2();
var options = {};
options["allowHtml"] = true;
options["width"] =    950;
options["height"] =    500;
options["vAxis"] = {title:'Average Number of months'};

    var chart = new google.visualization.ColumnChart(
    document.getElementById('ColumnChartID3c7a73e162f2')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartColumnChartID3c7a73e162f2);
})();
function displayChartColumnChartID3c7a73e162f2() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartColumnChartID3c7a73e162f2"></script>
 
<!-- divChart -->
  
<div id="ColumnChartID3c7a73e162f2" 
  style="width: 950; height: 500;">
</div>

--- &vcenter

## Productivity by Research Area (2nd)

<!-- ColumnChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sat Nov  8 13:17:59 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataColumnChartID3e63176e4e74 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "1",
3,
1,
3,
0,
7,
7,
1,
1,
8,
2 
],
[
 "2 to 3",
1,
4,
2,
2,
4,
7,
4,
7,
9,
6 
],
[
 "4 to 5",
0,
0,
2,
1,
2,
6,
1,
0,
2,
0 
],
[
 "More than 5",
1,
0,
1,
1,
1,
6,
0,
0,
1,
0 
] 
];
data.addColumn('string','working_papers');
data.addColumn('number','Environmental');
data.addColumn('number','Reg. Econ. Dev.');
data.addColumn('number','Location and Interaction');
data.addColumn('number','NEG');
data.addColumn('number','Other');
data.addColumn('number','Econ. Growth');
data.addColumn('number','Housing & Labor Mark.');
data.addColumn('number','Geocomputation');
data.addColumn('number','Spatial Econometrics');
data.addColumn('number','Spatial Statistics');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartColumnChartID3e63176e4e74() {
var data = gvisDataColumnChartID3e63176e4e74();
var options = {};
options["allowHtml"] = true;
options["width"] =    950;
options["height"] =    500;
options["vAxis"] = {title:'Frequency'};

    var chart = new google.visualization.ColumnChart(
    document.getElementById('ColumnChartID3e63176e4e74')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartColumnChartID3e63176e4e74);
})();
function displayChartColumnChartID3e63176e4e74() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartColumnChartID3e63176e4e74"></script>
 
<!-- divChart -->
  
<div id="ColumnChartID3e63176e4e74" 
  style="width: 950; height: 500;">
</div>

--- &vcenter
## Productivity by Research Area (2nd) & No. of Months

<!-- ColumnChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sat Nov  8 13:17:59 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataColumnChartID3e634ae0adb0 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "1",
8,
18,
18.33333333,
null,
6.714285714,
12,
18,
15,
17.375,
18 
],
[
 "2 to 3",
27,
17.75,
46,
35,
20.5,
17.42857143,
13.5,
14.42857143,
22.11111111,
19.33333333 
],
[
 "More than 5",
72,
null,
53,
24,
59,
36.33333333,
null,
null,
36,
null 
],
[
 "4 to 5",
null,
null,
47,
60,
44,
38.33333333,
24,
null,
21,
null 
] 
];
data.addColumn('string','working_papers');
data.addColumn('number','Environmental');
data.addColumn('number','Reg. Econ. Dev.');
data.addColumn('number','Location and Interaction');
data.addColumn('number','NEG');
data.addColumn('number','Other');
data.addColumn('number','Econ. Growth');
data.addColumn('number','Housing & Labor Mark.');
data.addColumn('number','Geocomputation');
data.addColumn('number','Spatial Econometrics');
data.addColumn('number','Spatial Statistics');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartColumnChartID3e634ae0adb0() {
var data = gvisDataColumnChartID3e634ae0adb0();
var options = {};
options["allowHtml"] = true;
options["width"] =    950;
options["height"] =    500;
options["vAxis"] = {title:'Average Number of months'};

    var chart = new google.visualization.ColumnChart(
    document.getElementById('ColumnChartID3e634ae0adb0')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartColumnChartID3e634ae0adb0);
})();
function displayChartColumnChartID3e634ae0adb0() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartColumnChartID3e634ae0adb0"></script>
 
<!-- divChart -->
  
<div id="ColumnChartID3e634ae0adb0" 
  style="width: 950; height: 500;">
</div>

--- &vcenter

## Productivity by Mafia Type

![plot of chunk unnamed-chunk-12](assets/fig/unnamed-chunk-12.png) 


---

## The REAL Mafia in a Network Context (Academics)

<iframe src="http://www.real.illinois.edu/networksVis/REALAcademicNet2/network/index.html#" heingt='600px'></iframe>
