---
title       : Creating a Virtual Yearbook of the REAL Mafia
subtitle    : Exploring its members' memories and connections
author      : Esteban Lopez
job         : UIUC PhD Candidate, REAL 'General'
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [shiny, interactive, bootstrap]
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


--- .centrepre &vcenter

## The Instrument

<!-- Table generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Thu Oct 30 18:08:26 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataTableID27244531993a () {
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
function drawChartTableID27244531993a() {
var data = gvisDataTableID27244531993a();
var options = {};
options["allowHtml"] = true;

    var chart = new google.visualization.Table(
    document.getElementById('TableID27244531993a')
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
callbacks.push(drawChartTableID27244531993a);
})();
function displayChartTableID27244531993a() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartTableID27244531993a"></script>
 
<!-- divChart -->
  
<div id="TableID27244531993a" 
  style="width: 500; height: automatic;">
</div>
<!-- Table generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Thu Oct 30 18:08:26 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataTableID27244531993a () {
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
function drawChartTableID27244531993a() {
var data = gvisDataTableID27244531993a();
var options = {};
options["allowHtml"] = true;

    var chart = new google.visualization.Table(
    document.getElementById('TableID27244531993a')
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
callbacks.push(drawChartTableID27244531993a);
})();
function displayChartTableID27244531993a() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartTableID27244531993a"></script>
 
<!-- divChart -->
  
<div id="TableID27244531993a" 
  style="width: 500; height: automatic;">
</div>

--- #dillinger

## The 'Actual' Instrument

<iframe src="https://docs.google.com/forms/d/1B3qXUtLhqH7JSpo1zLH0DZeEzPPt0YIXEMp48NUA0eI/viewform?edit_requested=true" heingt='600px'></iframe>

---  &vcenter

## Exploratory Analysis 

<strong>Demographic Frequencies </strong>


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
<!-- Sun Nov  2 13:50:34 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartIDc445947edc8 () {
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
function drawChartGeoChartIDc445947edc8() {
var data = gvisDataGeoChartIDc445947edc8();
var options = {};
options["width"] =    600;
options["height"] =    500;

    var chart = new google.visualization.GeoChart(
    document.getElementById('GeoChartIDc445947edc8')
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
callbacks.push(drawChartGeoChartIDc445947edc8);
})();
function displayChartGeoChartIDc445947edc8() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoChartIDc445947edc8"></script>
 
<!-- divChart -->
  
<div id="GeoChartIDc445947edc8" 
  style="width: 600; height: 500;">
</div>
<!-- GeoChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 13:50:34 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartIDc445947edc8 () {
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
function drawChartGeoChartIDc445947edc8() {
var data = gvisDataGeoChartIDc445947edc8();
var options = {};
options["width"] =    600;
options["height"] =    500;

    var chart = new google.visualization.GeoChart(
    document.getElementById('GeoChartIDc445947edc8')
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
callbacks.push(drawChartGeoChartIDc445947edc8);
})();
function displayChartGeoChartIDc445947edc8() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoChartIDc445947edc8"></script>
 
<!-- divChart -->
  
<div id="GeoChartIDc445947edc8" 
  style="width: 600; height: 500;">
</div>

---  &vcenter

## Current Country


<!-- GeoChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 13:50:34 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartIDc4414c1343 () {
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
function drawChartGeoChartIDc4414c1343() {
var data = gvisDataGeoChartIDc4414c1343();
var options = {};
options["width"] =    600;
options["height"] =    500;

    var chart = new google.visualization.GeoChart(
    document.getElementById('GeoChartIDc4414c1343')
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
callbacks.push(drawChartGeoChartIDc4414c1343);
})();
function displayChartGeoChartIDc4414c1343() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoChartIDc4414c1343"></script>
 
<!-- divChart -->
  
<div id="GeoChartIDc4414c1343" 
  style="width: 600; height: 500;">
</div>
<!-- GeoChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 13:50:34 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartIDc4414c1343 () {
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
function drawChartGeoChartIDc4414c1343() {
var data = gvisDataGeoChartIDc4414c1343();
var options = {};
options["width"] =    600;
options["height"] =    500;

    var chart = new google.visualization.GeoChart(
    document.getElementById('GeoChartIDc4414c1343')
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
callbacks.push(drawChartGeoChartIDc4414c1343);
})();
function displayChartGeoChartIDc4414c1343() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoChartIDc4414c1343"></script>
 
<!-- divChart -->
  
<div id="GeoChartIDc4414c1343" 
  style="width: 600; height: 500;">
</div>

---  &vcenter

## FRIST most important research area at REAL.

<!-- PieChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 13:52:23 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataPieChartIDc5be9f41a8 () {
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
function drawChartPieChartIDc5be9f41a8() {
var data = gvisDataPieChartIDc5be9f41a8();
var options = {};
options["allowHtml"] = true;
options["slices"] = {5: {offset: 0.2}, 10: {offset: 0.3}};
options["pieHole"] =    0.2;
options["chartArea"] = {left:0,top:0,width:'100%',height:'100%'};
options["height"] = "500px";
options["legend"] = "none";

    var chart = new google.visualization.PieChart(
    document.getElementById('PieChartIDc5be9f41a8')
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
callbacks.push(drawChartPieChartIDc5be9f41a8);
})();
function displayChartPieChartIDc5be9f41a8() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartPieChartIDc5be9f41a8"></script>
 
<!-- divChart -->
  
<div id="PieChartIDc5be9f41a8" 
  style="width: 500; height: 500px;">
</div>
<!-- PieChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 13:52:23 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataPieChartIDc5be9f41a8 () {
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
function drawChartPieChartIDc5be9f41a8() {
var data = gvisDataPieChartIDc5be9f41a8();
var options = {};
options["allowHtml"] = true;
options["slices"] = {5: {offset: 0.2}, 10: {offset: 0.3}};
options["pieHole"] =    0.2;
options["chartArea"] = {left:0,top:0,width:'100%',height:'100%'};
options["height"] = "500px";
options["legend"] = "none";

    var chart = new google.visualization.PieChart(
    document.getElementById('PieChartIDc5be9f41a8')
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
callbacks.push(drawChartPieChartIDc5be9f41a8);
})();
function displayChartPieChartIDc5be9f41a8() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartPieChartIDc5be9f41a8"></script>
 
<!-- divChart -->
  
<div id="PieChartIDc5be9f41a8" 
  style="width: 500; height: 500px;">
</div>

---  &vcenter

## SECOND most important research area at REAL.

<!-- PieChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 13:52:23 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataPieChartIDc5b798f8417 () {
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
function drawChartPieChartIDc5b798f8417() {
var data = gvisDataPieChartIDc5b798f8417();
var options = {};
options["allowHtml"] = true;
options["slices"] = {5: {offset: 0.2}, 10: {offset: 0.3}};
options["pieHole"] =    0.2;
options["chartArea"] = {left:0,top:0,width:'100%',height:'100%'};
options["height"] = "500px";
options["legend"] = "none";

    var chart = new google.visualization.PieChart(
    document.getElementById('PieChartIDc5b798f8417')
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
callbacks.push(drawChartPieChartIDc5b798f8417);
})();
function displayChartPieChartIDc5b798f8417() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartPieChartIDc5b798f8417"></script>
 
<!-- divChart -->
  
<div id="PieChartIDc5b798f8417" 
  style="width: 500; height: 500px;">
</div>
<!-- PieChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 13:52:23 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataPieChartIDc5b798f8417 () {
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
function drawChartPieChartIDc5b798f8417() {
var data = gvisDataPieChartIDc5b798f8417();
var options = {};
options["allowHtml"] = true;
options["slices"] = {5: {offset: 0.2}, 10: {offset: 0.3}};
options["pieHole"] =    0.2;
options["chartArea"] = {left:0,top:0,width:'100%',height:'100%'};
options["height"] = "500px";
options["legend"] = "none";

    var chart = new google.visualization.PieChart(
    document.getElementById('PieChartIDc5b798f8417')
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
callbacks.push(drawChartPieChartIDc5b798f8417);
})();
function displayChartPieChartIDc5b798f8417() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartPieChartIDc5b798f8417"></script>
 
<!-- divChart -->
  
<div id="PieChartIDc5b798f8417" 
  style="width: 500; height: 500px;">
</div>

---  &vcenter

## THIRD most important research area at REAL.

<!-- PieChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 13:54:20 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataPieChartIDc73559409ba () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Environmental and Natural Resources",
6 
],
[
 "Innovation and Regional Economic Development",
6 
],
[
 "Location and Interaction",
6 
],
[
 "New Economic Geography and Evolutionary Economic Geography",
7 
],
[
 "Other",
33 
],
[
 "Regional Economic Growth",
11 
],
[
 "Regional Housing and Labor Markets",
7 
],
[
 "Spatial Analysis and Geocomputation",
8 
],
[
 "Spatial Econometrics",
13 
],
[
 "Spatial Statistics",
7 
] 
];
data.addColumn('string','Var1');
data.addColumn('number','Freq');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartPieChartIDc73559409ba() {
var data = gvisDataPieChartIDc73559409ba();
var options = {};
options["allowHtml"] = true;
options["slices"] = {5: {offset: 0.2}, 10: {offset: 0.3}};
options["pieHole"] =    0.2;
options["chartArea"] = {left:0,top:0,width:'100%',height:'100%'};
options["height"] = "500px";
options["legend"] = "none";

    var chart = new google.visualization.PieChart(
    document.getElementById('PieChartIDc73559409ba')
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
callbacks.push(drawChartPieChartIDc73559409ba);
})();
function displayChartPieChartIDc73559409ba() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartPieChartIDc73559409ba"></script>
 
<!-- divChart -->
  
<div id="PieChartIDc73559409ba" 
  style="width: 500; height: 500px;">
</div>
<!-- PieChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Sun Nov  2 13:54:20 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataPieChartIDc73559409ba () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Environmental and Natural Resources",
6 
],
[
 "Innovation and Regional Economic Development",
6 
],
[
 "Location and Interaction",
6 
],
[
 "New Economic Geography and Evolutionary Economic Geography",
7 
],
[
 "Other",
33 
],
[
 "Regional Economic Growth",
11 
],
[
 "Regional Housing and Labor Markets",
7 
],
[
 "Spatial Analysis and Geocomputation",
8 
],
[
 "Spatial Econometrics",
13 
],
[
 "Spatial Statistics",
7 
] 
];
data.addColumn('string','Var1');
data.addColumn('number','Freq');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartPieChartIDc73559409ba() {
var data = gvisDataPieChartIDc73559409ba();
var options = {};
options["allowHtml"] = true;
options["slices"] = {5: {offset: 0.2}, 10: {offset: 0.3}};
options["pieHole"] =    0.2;
options["chartArea"] = {left:0,top:0,width:'100%',height:'100%'};
options["height"] = "500px";
options["legend"] = "none";

    var chart = new google.visualization.PieChart(
    document.getElementById('PieChartIDc73559409ba')
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
callbacks.push(drawChartPieChartIDc73559409ba);
})();
function displayChartPieChartIDc73559409ba() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartPieChartIDc73559409ba"></script>
 
<!-- divChart -->
  
<div id="PieChartIDc73559409ba" 
  style="width: 500; height: 500px;">
</div>

--- #dillinger

## The REAL Mafia in a Network Context

<iframe src="http://www.real.illinois.edu/networksVis/REALAcademicNet2/network/index.html#" heingt='600px'></iframe>
