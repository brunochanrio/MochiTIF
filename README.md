# MochiTIF
Replacement Library and Live TV app for the TV Input Framework Companion Library and Live Channels app on Android TV and Google TV

<img src="https://brunochanrio.github.io/MochiTIF/MochiTIF_Logo.png"/>

MochiTIF is a project that aims to offer a updated replacement for both the Google TV Input Framework Companion Library and the Live Channels app on Android TV and Google TV, with support for newer devices and new features

## Development status
<table>
  <thead>
    <tr><th align="left">Component Name</th><th align="left">Component to replace</th><th align="left">Status</th><th align="left">Download</th></tr>
  </thead>
  <tbody>
    <tr><td>MochiTIF Core Library</td><td>TIF Companion Library</td><td nowrap>In development</td><td></td></tr>
    <tr></td><td>MochiTIF Live TV</td><td>Live Channels</td><td nowrap >In development</td><td></td></tr>
    <tr></td><td>MochiTIF Sample TV Input</td><td>Android Sample TV Input App</td><td nowrap>Included in MochiTIF Live TV App</td><td></td></tr>
    <tr></td><td>MochiTIF Xtream Codes API Supplementary Library</td><td></td><td nowrap>Planned</td><td></td></tr>
    <tr></td><td>MochiTIF M3U Supplementary Library</td><td></td><td nowrap>Planned</td><td></td></tr>
  </tbody>
</table>

## Components of MochiTIF

### MochiTIF Core Library
The core library of MochiTIF, based on the <a href="https://github.com/amzn/ftv-livetv-sample-tv-app/tree/master/AndroidTvSampleInput/library">Amazon implementation</a> of the Google TIF Companion Library and modified to get channels visible on non-system TV Input Framework-based Live TV apps, allows you to build apps for Android TV and Google TV that adds channels via the TV Input Framework that can be played via either the <a href="https://play.google.com/store/apps/details?id=com.google.android.tv">Google Live Channels</a> app or the newer Live Channels-based MochiTIF Live TV app

### MochiTIF Live TV
The MochiTIF Live TV, based on the <a href="https://android.googlesource.com/platform/packages/apps/TV/">AOSP Source Code</a> of the <a href="https://play.google.com/store/apps/details?id=com.google.android.tv">Live Channels</a> app, allows you to watch channels from the TV Tuner and apps that use the TV Input Framework, like <a href="https://play.google.com/store/apps/details?id=by.stari4ek.tvirl">TVirl</a> and <a href="https://github.com/brunochanrio/DangoPlayer-TV">DangoPlayer TV</a> (this last one uses a in-development version of the MochiTIF Core Library), and access HDMI and another video inputs of your TV

NOTE: Some features like DVR, Parental Control, Content Rating, Timeshift and HDMI-CEC are unsupported by MochiTIF Live TV because requires the Live TV app to be a system app

### MochiTIF Sample TV Input
The MochiTIF Sample TV Input, bundled in MochiTIF Live TV app, allows you to demonstrate the functionality of MochiTIF by adding demo channels to the channels list

### MochiTIF Xtream Codes API Supplementary Library
The Xtream Codes API Supplementary Library of MochiTIF, allows you to build apps for Android TV and Google TV that offers channels from a Xtream Codes API account, and also VOD Content like Movies and Series

This supplementary library is not independent and requires the MochiTIF Core Library to be added to your project

### MochiTIF M3U Supplementary Library
The M3U Supplementary Library of MochiTIF, allows you to build apps for Android TV and Google TV that offers channels from a M3U Playlist, with its EPG Guides

This supplementary library is not independent and requires the MochiTIF Core Library to be added to your project
