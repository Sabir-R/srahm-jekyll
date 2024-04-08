---
name: IS 445 Homework 8
tools: [Python, HTML, vega-lite]
image: assets/pngs/hw8.png
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# IS 445 Homework 8
Use python, altair, and vega-lite to make two visualizations from the Building Inventory dataset.

# Plot 1

<vegachart schema-url="{{ site.baseurl }}/assets/json/testchart2.json" style="width: 100%"></vegachart>

This first visualization is the same as from homework 7. "I wanted to visualize what year the buildings were acquired and how many per that year as well. Unfortunately, I ran into the same issue of not being sure how I could change the zoom level of the chart so that it wasn't very zoomed out." I made sure on the python side that I only considered buildings acquired after the year 1000 since it did not make sense that buildings were acquired in year 0. Since this was my first try with altair I kept it simple and just specified x and y values just to see how it worked and if I could produce similar results to my starboard chart.

# Plot 2

<vegachart schema-url="{{ site.baseurl }}/assets/json/testchart4.json" style="width: 100%"></vegachart>

This second visualization is also very similar to the one from homework 7. "I want to compare how many buildings each agency/group/university has under their name. I used a bar chart for this to make it easier to tell the difference. Unfortunately, I had to tweak the scale to make it very tall in order to see the difference for the groups that don’t even own close to 100 buildings." This time however, I was able to figure out the tooltip interactivity and implement it into this visualization this time. Now, it is easier to hover over the bars for the agency's that are all quite small compared to the rest to be able to see the exact number and know how they compare to the other small ones.

## Data and Methods to check out!

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/Sabir-R/srahm-jekyll/blob/main/python_notebooks/HW8-Workbook.ipynb" text="The Analysis" %}
</div>

