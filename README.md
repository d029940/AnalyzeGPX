# AnalyzeGPX

Shows routes, tracks and waypoints of a GPX file. Tested only with Garmin GPX files.

There are three areas (tabs), initially empty:
- Devices with GPX files: Shows a list of devices / volumes with GPX files.
- List the GPX files: lists GPX files of a selected device / volume.
- GPX Content: shows the content (routes, tracks, waypoints) of a GPX file.

The tabs will be populated with the following actions:

- The "Open GPX file" button lets you locate and open a specific GPX file in the file system and shows it in the "GPX Content" tab.
- The "Load Garmin devices" looks for attached devices/volumes for a folder "/Garmin/GPX" and lists all devices in "Devices with GPX files" tab.
- Clicking on a device/volume in the "Devices with GPX files" tab lists all GPX files on that device/volume
- Clicking on a GXP file in the "List the GPX files" tab will show the content of the GPX file in the "GPX Content" tab.


Technical details:
This a MacOS App written in Swift and using Storyboard.
It is one of my first projects and I am still learning. There are certainly better ways for design and implementation.
