---
layout: page
permalink: /teaching/
title: teaching
description: 
---

#### I've taught the following courses at the undergraduate level (links to the most recent syllabus are provided for each course):

 Course                        | Semester(s)                                         
-------------------------------|-----------------------------------------------------
 Money & Banking               | f2015, sp2016, su2016, f2016, sp2017, f2017, [sp2018](https://drive.google.com/open?id=1-KsqTI43-Aj7o74THp9516iQazxGA0Fp)
 International Economics       | su2017, [su2018](https://drive.google.com/open?id=19bNOvuJUcOuJfaMDThSlAZXRHv24Qy5o)
 Principles of Microeconomics | [sp2016](https://drive.google.com/open?id=1djcMuDbCogYAHh9QyxppcZCMu40k0WLL)

#### Summary of teaching evaluations
(a complete set of teaching evaluations are available upon request)

<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js">
    
    google.charts.load('current', {
        'packages': ['bar']
      });
 
      google.charts.setOnLoadCallback(drawChart);
      function drawChart() {
        var data = google.visualization.arrayToDataTable([
          ["Semester", "Hamalainen", "ECON Average"],
          ["Fall 2015", 5.4, 5.1],
          ["Spring 2016", 5.45, 5.2],
          ["Summer 2016", 5.6, 5.2],
          ["Fall 2016", 5.3, 5.2],
          ["Spring 2017", 5.6, 5.2],
          ["Summer 2017", 5.4, 5.4],
          ["Fall 2017", 5.5, 5.1],
          ["Spring 2018", 5.8, 5.1],
          ["Summer 2018", 5.4, 5.2],
        ]);
        var options = {
          chart: {
            title: 'Course Evaluations',
            subtitle: 'Instructor Questions (2015-2018)',
          },
          bars: 'horizontal', // Required for Material Bar Charts.
          hAxis: {
            format: 'decimal',
            viewWindow: {
              min: 4.5,
              max: 6
            },
            ticks: [4.5, 5.0, 5.5, 6]
          },
          height: 400,
          colors: ['#5DADE2', '#7F8C8D']
        };
        var chart = new google.charts.Bar(document.getElementById('chart_div'));

        chart.draw(data, google.charts.Bar.convertOptions(options));

        var btns = document.getElementById('btn-group');

        btns.onclick = function(e) {

          if (e.target.tagName === 'BUTTON') {
            options.hAxis.format = e.target.id === 'none' ? '' : e.target.id;
            chart.draw(data, google.charts.Bar.convertOptions(options));
          }
        }
      } 
      
</script>

