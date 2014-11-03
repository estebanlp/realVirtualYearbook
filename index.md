---
title       : Creating a Virtual Yearbook of the REAL Mafia
subtitle    : Exploring its members' memories and connections
author      : Esteban Lopez
job         : UIUC PhD Candidate, REAL 'General'
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz]
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
<!-- Sun Nov  2 19:04:03 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataHistogramID11dc3e6510ce () {
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
function drawChartHistogramID11dc3e6510ce() {
var data = gvisDataHistogramID11dc3e6510ce();
var options = {};
options["allowHtml"] = true;
options["width"] =    800;
options["height"] =    300;

    var chart = new google.visualization.Histogram(
    document.getElementById('HistogramID11dc3e6510ce')
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
callbacks.push(drawChartHistogramID11dc3e6510ce);
})();
function displayChartHistogramID11dc3e6510ce() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartHistogramID11dc3e6510ce"></script>
 
<!-- divChart -->
  
<div id="HistogramID11dc3e6510ce" 
  style="width: 800; height: 300;">
</div>
<!-- Histogram generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 19:04:03 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataHistogramID11dc3e6510ce () {
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
function drawChartHistogramID11dc3e6510ce() {
var data = gvisDataHistogramID11dc3e6510ce();
var options = {};
options["allowHtml"] = true;
options["width"] =    800;
options["height"] =    300;

    var chart = new google.visualization.Histogram(
    document.getElementById('HistogramID11dc3e6510ce')
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
callbacks.push(drawChartHistogramID11dc3e6510ce);
})();
function displayChartHistogramID11dc3e6510ce() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartHistogramID11dc3e6510ce"></script>
 
<!-- divChart -->
  
<div id="HistogramID11dc3e6510ce" 
  style="width: 800; height: 300;">
</div>

--- .segue bg:indigo

## Academics at REAL

---  &vcenter

## FRIST most important research area at REAL.

<!-- PieChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 19:12:06 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataPieChartID122e76ab4e16 () {
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
function drawChartPieChartID122e76ab4e16() {
var data = gvisDataPieChartID122e76ab4e16();
var options = {};
options["allowHtml"] = true;
options["width"] =    700;
options["height"] =    600;
options["legend"] = "none";

    var chart = new google.visualization.PieChart(
    document.getElementById('PieChartID122e76ab4e16')
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
callbacks.push(drawChartPieChartID122e76ab4e16);
})();
function displayChartPieChartID122e76ab4e16() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartPieChartID122e76ab4e16"></script>
 
<!-- divChart -->
  
<div id="PieChartID122e76ab4e16" 
  style="width: 700; height: 600;">
</div>
<!-- PieChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 19:12:06 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataPieChartID122e76ab4e16 () {
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
function drawChartPieChartID122e76ab4e16() {
var data = gvisDataPieChartID122e76ab4e16();
var options = {};
options["allowHtml"] = true;
options["width"] =    700;
options["height"] =    600;
options["legend"] = "none";

    var chart = new google.visualization.PieChart(
    document.getElementById('PieChartID122e76ab4e16')
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
callbacks.push(drawChartPieChartID122e76ab4e16);
})();
function displayChartPieChartID122e76ab4e16() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartPieChartID122e76ab4e16"></script>
 
<!-- divChart -->
  
<div id="PieChartID122e76ab4e16" 
  style="width: 700; height: 600;">
</div>

---  &vcenter

## SECOND most important research area at REAL.

<!-- PieChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 19:12:06 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataPieChartID122e6893c337 () {
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
function drawChartPieChartID122e6893c337() {
var data = gvisDataPieChartID122e6893c337();
var options = {};
options["allowHtml"] = true;
options["width"] =    700;
options["height"] =    600;
options["legend"] = "none";

    var chart = new google.visualization.PieChart(
    document.getElementById('PieChartID122e6893c337')
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
callbacks.push(drawChartPieChartID122e6893c337);
})();
function displayChartPieChartID122e6893c337() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartPieChartID122e6893c337"></script>
 
<!-- divChart -->
  
<div id="PieChartID122e6893c337" 
  style="width: 700; height: 600;">
</div>
<!-- PieChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 19:12:06 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataPieChartID122e6893c337 () {
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
function drawChartPieChartID122e6893c337() {
var data = gvisDataPieChartID122e6893c337();
var options = {};
options["allowHtml"] = true;
options["width"] =    700;
options["height"] =    600;
options["legend"] = "none";

    var chart = new google.visualization.PieChart(
    document.getElementById('PieChartID122e6893c337')
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
callbacks.push(drawChartPieChartID122e6893c337);
})();
function displayChartPieChartID122e6893c337() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartPieChartID122e6893c337"></script>
 
<!-- divChart -->
  
<div id="PieChartID122e6893c337" 
  style="width: 700; height: 600;">
</div>

--- &vcenter

## Productivity by Mafia Type

![plot of chunk unnamed-chunk-8](assets/fig/unnamed-chunk-8.png) 

--- &vcenter

## Productivity by Research Area (First)

![plot of chunk unnamed-chunk-9](assets/fig/unnamed-chunk-9.png) 

---

## The REAL Mafia in a Network Context

<iframe src="http://www.real.illinois.edu/networksVis/REALAcademicNet2/network/index.html#" heingt='600px'></iframe>
