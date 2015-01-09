---
layout: default
title:  OpenStreetMap Tracing Guide
permalink: /guide/
toc: true

---


#OpenStreetMap Tracing Guide



![OSM]({{site.url}}../images/guide/OSM2.png)

TO EXPAND: The purpose of this guide is to assist remote mappers in indentifying geographic features unique to volcanic areas of Indonesia. Listed in this guide are the most common features you can identify using high resolution satellite imagery. For reference on the basics of how to use OpenStreetMap, see the State Department's [MapGive](http://mapgive.state.gov/learn-to-map/) website.

-----

##TAGGING FEATURES AND ATTRIBUTION

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

##TRACING FEATURES

###Buildings

Common building types in this region include, but are not limited to: homes, health clinics, schools, religious structures, shops, and agriculture.

How to Trace Buildings
To trace buildings, place a node around every corner. Some buildings will be harder to discern than others--in these cases, trace the buildings as best as possible. When tracing is complete, remember to tag the newly added feature. See the images below for a step-by-step explaination on how to trace a building.

![OSMBuilding]({{site.url}}../images/guide/building.png)
<br />
<sup><i>Find a building that has not been mapped yet.</i></sup>

![OSMBuilding2]({{site.url}}../images/guide/building2.png)
<br />
<sup><i>Click on "Area" and begin tracing. Place a node at each corner of the building. A node is placed every time a user clicks on the mouse.</i></sup>

![OSMBuilding3]({{site.url}}../images/guide/building3.png)
<br />
<sup><i>After tracing is complete, double click to complete the polygon. Look at the tag list and click on "building".</i></sup>

![OSMBuildingGIF]({{site.url}}../images/guide/buildingGIF.gif)
<br />
<sup><i>An animation of the process.</i></sup>

-----

###Rivers/Lakes

Many of the water features users encounter in Indonesia have already been added. However, there are still plenty smaller rivers, streams, and agricultural water features to map.

Editing Water Features:
While many water features are already in OSM, not all are traced correctly. Some were added via bulk upload using global datasets and as such, do not have good granularity.

![OSMWater3]({{site.url}}../images/guide/river4.png)
<br />
<sup><i>Editing a line feature.</i></sup>

![OSMWaterGIF2]({{site.url}}../images/guide/riverGIF.gif)
<br />
<sup><i>Animation of editing a line feature.</i></sup>

Creating Water Features:
When creating new water features in OSM, you first need to determine if a area or line is necessary. The choice is mostly in reference to rivers. You may trace the river as a polygon or use the line tool to trace the along the <i>center</i> of the river. With either option, the user must trace the whole length of the river. Because of this, both options will involve zooming and panning around the imagery.

How to Trace Rivers

![OSMWater]({{site.url}}../images/guide/river5.png)
<br />
<sup><i>Find a river that isn't in OSM and click on "Line".</i></sup>

![OSMWater2]({{site.url}}../images/guide/river6.png)
<br />
<sup><i>When done tracing, double click and tag appropriately.</i></sup>

![OSMWaterGIF]({{site.url}}../images/guide/river2GIF.gif)
<br />
<sup><i>Short animation of river tracing.</i></sup>

-----

###Roads

Editing Road Features:
Similar to the river features, not all road data is properly traced in OSM and can be edited. Roads may also not be completely, in which case a user can finish tracing the length of the road. 

![OSMRoads3]({{site.url}}../images/guide/road.png)
<br />
<sup><i>Click on the last node of a line and select "Continue this line".</i></sup>

![OSMRoadsGIF2]({{site.url}}../images/guide/roadGIF.gif)
<br />
<sup><i>Short animation on road editing.</i></sup>

Creating Road Features:
There are plenty of roads that have not been traced into OpenStreetMap yet. If it is unclear what type of road it is, use the general "road" tag.

How to Trace Roads

![OSMRoads]({{site.url}}../images/guide/road2.png)
<br />
<sup><i>Find a road that hasn't been traced in OSM. Click "Line" and begin tracing.</i></sup>

![OSMRoads2]({{site.url}}../images/guide/road3.png)
<br />
<sup><i>Double-click when done and tag the new feature appropriately.</i></sup>

![OSMRoadsGIF]({{site.url}}../images/guide/road2GIF.gif)
<br />
<sup><i>Short animation on road creation.</i></sup>
