---
layout: post
status: publish
published: true
title: New SDE Connection Properties for ArcGIS Desktop 10.1 - Updated
author:
  display_name: Michael Foulger
  login: mfoulger
  email: michaelfoulger@utah.gov
  url: ''
author_login: mfoulger
author_email: michaelfoulger@utah.gov
wordpress_id: 10061
wordpress_url: http://gis.utah.gov/?p=10061
date: '2012-09-13 10:00:46 -0600'
date_gmt: '2012-09-13 16:00:46 -0600'
categories:
- Data
- Featured
tags: []
---
<p>New Connection Method</p>
<p>Esri is now providing a tool to create an ArcSDE Connection File wherever you would like on your file system. <span style="color: #ff0000;"> (NOTE:  This tool is only available to users running a Standard (ArcEditor) or Advanced (ArcInfo) license level.  Users of a Basic (ArcView) license will need to download the connection file, available in a link below.)</span>  The tool is located in the standard toolbox under Data Management -&gt; Workspace -&gt; Create ArcSDE Connection File.  Here's a look at where it's located, and what it looks like when filled out:</p>
<p>&nbsp;</p>
<p><a href="{{ "/new-sde-connection-properties-for-arcgis-desktop-10-1/arcsdeconnectionfile/" | prepend: site.baseurl }}" rel="attachment wp-att-11567"><img class="aligncenter size-full wp-image-11567" title="ArcSDEConnectionFile" src="{{ "/images/ArcSDEConnectionFile-e1346951121724.png" | prepend: site.baseurl }}" alt="" width="912" height="613" /></a></p>
<p>&nbsp;</p>
<p>You can save the connection file anywhere you'd like, but if you want to see the connection in the Database Connections folder in ArcGIS Desktop, you'll need to save it to this location:</p>
<p>C:\Users\&lt;Your User Name&gt;\AppData\Roaming\ESRI\Desktop10.1\ArcCatalog</p>
<p>It should be noted that the AppData folder is most likely hidden by default. In Windows 7, you can make it visible by going to Control Panel -&gt; Folder Options, choosing the view tab, and enabling "Show hidden files, folders, and drives from the Hidden files and folders area. (Thanks Doug!)</p>
<p>Just replace the entry &lt;Your User Name&gt; with your login name.</p>
<p>&nbsp;</p>
<p><strong><span style="color: #000000;">Instructions for Basic (ArcView) license level users:</span></strong></p>
<p>If you're using a Basic license for Esri's desktop product (ArcView), and wish to connect to the SGID, you'll need to download a connection file from our FTP site:</p>
<p><a title="Click Here to Download Connection File" href="ftp://ftp.agrc.utah.gov/ApplicationServer/ArcGIS_Connection_File/ConnectSGID10.sde">ftp://ftp.agrc.utah.gov/ApplicationServer/ArcGIS_Connection_File/ConnectSGID10.sde</a></p>
<p>You should download and save the file locally to this location:</p>
<p>C:\Users\&lt;Your User Name&gt;\AppData\Roaming\ESRI\Desktop10.1\ArcCatalog</p>
<p>It should be noted that the AppData folder is most likely hidden by default. In Windows 7, you can make it visible by going to Control Panel -&gt; Folder Options, choosing the view tab, and enabling "Show hidden files, folders, and drives from the Hidden files and folders area.</p>
<p>Just replace the entry &lt;Your User Name&gt; with your login name.</p>
