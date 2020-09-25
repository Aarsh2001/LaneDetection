# LaneDetection

Works well for images and videos in a straight line. Work still in progress for detecting curved lines in real time.

The `filevideostream.py` is a class that i've used to improve the fps rate of processing frames and reading video files. I've utilized
**queue data structure** and **threading** to achieve this.The implementation of this is done in `LaneDetection-Copy1.py` file for **I/O operations**.

Use `--image [pathname]` for lane detection in image and `--video [pathname]` for  detection in video.
