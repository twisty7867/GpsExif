GpsExif
=======

A pair of tools to capture GPS information from iOS devices, match the time with photos taken by a digital camera, and add GPS coordinates to the EXIF data for photos taken.

The mobile half of the tool runs on an iOS device and captures the GPS data, along with dates and times. 
It also provides the capability to display the current time on the iOS device as a 2D barcode, so that it can be matched to the time on the camera. 

The desktop half of the tool merges the GPS data file from the iOS application with the files from the camera. It can read 2D barcodes from the photos taken in order to align the camera's time with the iOS device's time.
