fusion-table-search-and-zoom
============================

A template for adding a simple search-and-zoom box (and optional color legend) to your Fusion Table maps. Adapted from:
https://developers.google.com/fusiontables/docs/samples/search_and_zoom

Instructions for what to change are in the HTML itself but the main things are:

On both maps:

Line 38: Change map width (and height) to match your needs

Line 53: Lat/lon coordinates for your map centre

Line 54: Default zoom for the map (on load and reset)

Line 55: Table ID for your Fusion Table

Line 79: Geocoding bias (set to Greater Vancouver, BC) but can be whatever you want, or nothing. What you write here will be appended to address before geocoding is run


On color legend:

Line 121: Map title and change width to match map width

Lines 128-132: Colors and width of bars for color legend (can have however many bars you want, but must match with labels below)

Lines 135-139: Color labels (should match number of colors)

