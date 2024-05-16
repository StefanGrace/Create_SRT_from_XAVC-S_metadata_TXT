# Convert ExifTool output TXT to SRT

This program takes a TXT file containing Sony XAVC-S camera metadata outputted by ExifTool, and creates an SRT file that contains the following realtime video meta data:
* Date and time
* Aperture
* Shutter speed
* Gain (dB)

Note that this probably won't work for metadata from camera brands other than Sony.

Note that to extract the realtime XAVC-S metadata you need the original file as it came of the camera, if the file has been altered in any way, even with FFmpeg, then this won't work.
