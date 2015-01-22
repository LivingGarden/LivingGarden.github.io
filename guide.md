---
layout: default
title:  OpenStreetMap Tracing Guide
permalink: /guide/
toc: true

---


#OpenStreetMap Tracing Guide

The purpose of this guide is to assist remote mappers in indentifying geographic features unique to volcanic areas of Indonesia. Listed in this guide are the most common features you can identify using high resolution satellite imagery. For reference on the basics of how to use OpenStreetMap, see the State Department's [MapGive](http://mapgive.state.gov/learn-to-map/) website.

![Indonesia](http://upload.wikimedia.org/wikipedia/commons/thumb/6/67/Paluweh_volcano_in_Indonesia.jpg/1280px-Paluweh_volcano_in_Indonesia.jpg)

-----

##Tagging Features

###Tagging
It is important that features are tagged appropriately and consistently. 

<table>
  <thead>
    <tr>
      <th>Feature</th>
      <th>Initial Tag</th>
      <th>General Tag</th>
      <th>Specific Tag</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>All Buildings</td>
      <td>Building</td>
      <td>Building</td>
      <td>House</td>
    </tr>
    <tr>
      <td>Water Features</td>
      <td>Water</td>
      <td>River/Lake</td>
      <td>Ditch/Stream</td>
    </tr>
    <tr>
      <td>All Roads and Highways</td>
      <td>Road</td>
      <td>Road</td>
      <td>Primary/Residential</td>
    </tr>
  </tbody>
</table>

Only use the specific tags when applicable. For all other features, please use general tags such as "building", "road", etc.

###Attributes
Similar to tagging, more in-depth information about a feature in the OpenStreetMap database should be added when applicable. Only add attribute information if you have the accurate infromation regarding the features.

###Editing Existing Work
OpenStreetMap is a collaborative platform. If you see traced features that look incorrect based on the satellite, you may edit them accordingly. See the Water Features section below for more information and examples.

###Saving Edits
Save your edits often, as a browser crash will delete all unsaved tracing.

----

##Tracing Features

###Buildings

Common building types in this region include, but are not limited to: homes, health clinics, schools, religious structures, shops, and agriculture.

How to Trace Buildings
To trace buildings, place a node around every corner. Some buildings will be harder to discern than others--in these cases, trace the buildings as best as possible. When tracing is complete, remember to tag the newly added feature. See the images below for a step-by-step explaination on how to trace a building.

<figure>
	<img src="../images/guide/building.png">
	<figcaption>Find a building that has not been mapped yet.</figcaption>
</figure>

<figure>
	<img src="../images/guide/building2.png">
	<figcaption>Click on "Area" and begin tracing. Place a node at each corner of the building. A node is placed every time a user clicks on the mouse.</figcaption>
</figure>

<figure>
	<img src="../images/guide/building3.png">
	<figcaption>After tracing is complete, double click to complete the polygon. Look at the tag list and click on "building".</figcaption>
</figure>

<figure>
	<img src="../images/guide/buildingGIF.gif">
	<figcaption>An animation of the process.</figcaption>
</figure>

-----

###Rivers/Lakes

Many of the water features users encounter in Indonesia have already been added. However, there are still plenty smaller rivers, streams, and agricultural water features to map.

Editing Water Features:
While many water features are already in OSM, not all are traced correctly. Some were added via bulk upload using global datasets and as such, do not have good granularity.

<figure>
	<img src="../images/guide/river4.png">
	<figcaption>Editing a line feature.</figcaption>
</figure>

<figure>
	<img src="../images/guide/riverGIF.gif">
	<figcaption>Animation of editing a line feature.</figcaption>
</figure>

Creating Water Features:
When creating new water features in OSM, you first need to determine if a area or line is necessary. The choice is mostly in reference to rivers. You may trace the river as a polygon or use the line tool to trace the along the <i>center</i> of the river. With either option, the user must trace the whole length of the river. Because of this, both options will involve zooming and panning around the imagery.

How to Trace Rivers

<figure>
	<img src="../images/guide/river5.png">
	<figcaption>Find a river that isn't in OSM and click on "Line".</figcaption>
</figure>

<figure>
	<img src="../images/guide/river6.png">
	<figcaption>When done tracing, double click and tag appropriately.</figcaption>
</figure>

<figure>
	<img src="../images/guide/river2GIF.gif">
	<figcaption>Short animation of river tracing.</figcaption>
</figure>

-----

###Roads

Editing Road Features:
Similar to the river features, not all road data is properly traced in OSM and can be edited. Roads may also not be completely, in which case a user can finish tracing the length of the road. 

<figure>
	<img src="../images/guide/road.png">
	<figcaption>Click on the last node of a line and select "Continue this line".</figcaption>
</figure>

<figure>
	<img src="../images/guide/roadGIF.gif">
	<figcaption>Short animation on road editing.</figcaption>
</figure>

Creating Road Features:
There are plenty of roads that have not been traced into OpenStreetMap yet. If it is unclear what type of road it is, use the general "road" tag.

How to Trace Roads

<figure>
	<img src="../images/guide/road2.png">
	<figcaption>Find a road that hasn't been traced in OSM. Click "Line" and begin tracing.</figcaption>
</figure>

<figure>
	<img src="../images/guide/road3.png">
	<figcaption>Double-click when done and tag the new feature appropriately.</figcaption>
</figure>

<figure>
	<img src="../images/guide/road2GIF.gif">
	<figcaption>Short animation on road creation.</figcaption>
</figure>
