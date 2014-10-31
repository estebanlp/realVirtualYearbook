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

--- 

## The "Actual" Instrument

<iframe src="https://docs.google.com/forms/d/1B3qXUtLhqH7JSpo1zLH0DZeEzPPt0YIXEMp48NUA0eI/edit" heingt='600px'></iframe>

--- .middle

Slidify is Awesome
