---
name: IS 445 Homework 8
tools: [Python, HTML, vega-lite]
image: assets/pngs/cars.png
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Testing things for HW 8

Just testing to see if a new project page is made or not.

# Plot 1

<vegachart schema-url="{{ site.baseurl }}/assets/json/cars.json" style="width: 100%"></vegachart>

This is where plot 1 is explained yada yada

# Plot 2

<vegachart schema-url="{{ site.baseurl }}/assets/json/cars.json" style="width: 100%"></vegachart>

This is where plot 2 is explained duh

# The Interactivity

I chose to make Plot 2 interactive cuz blah blah blah

## Data and Methods to check out!

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/Sabir-R/srahm-jekyll/blob/main/python_notebooks/hw8.ipynb" text="The Analysis" %}
</div>
