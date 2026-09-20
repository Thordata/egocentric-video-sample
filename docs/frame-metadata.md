# Driving Sample Frame Metadata

These files were generated from the public sample URL returned by the DataMall dataset API for SKU `VID-20260728-151612-899`.

Source video:

`https://bj-video-annotation.tos-cn-beijing.volces.com/js-datamall/20260728/1785222859959093726-20260725103636%20000056.mp4`

The downloaded MP4 has these verified properties:

- SHA-256: `2DED594132809AEF8FB471BEFDC5085AF4C2C7DBA2EB3B1EB0F0618879FFFD1B`
- Size: 58,419,103 bytes
- Container: MP4
- Video codec sample entry: `avc1` (H.264)
- Dimensions: 720 x 480 pixels
- Video samples: 6,001
- Average frame rate: 20 fps
- Duration: 300.05 seconds
- Audio track: not present

`metadata/frame-metadata.csv` contains one row for every video sample in the MP4 video track. `frame_index` is zero based, and `timestamp_sec` is the decoded sample start timestamp derived from the MP4 timing table. It contains 6,001 rows plus the header and does not contain frame image paths.

`metadata/frame-metadata-1fps.csv` contains one row at or after each one-second interval. It contains 301 rows plus the header and is an explicitly documented sample of the full frame index.

Both files map timestamps to the six existing segment IDs using these boundaries in seconds: `0`, `33.4`, `66.7`, `133.3`, `200`, `266.6`, and `300.067`. The segment labels remain `needs_review` because the video content and annotations have not been independently reviewed.

The product page describes product-level video specifications of 3840 x 2160 and 24.6 Mb/s. Those values do not describe this downloaded preview file and must not replace the verified sample-level values above.
