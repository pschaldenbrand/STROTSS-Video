# STROTSS Video

###Video style transfer using Style Transfer by Relaxed Optimal Transport and Self-Similarity (STROTSS)

Each frame of the content video is styled by the given style image.  strotss.py produces a directory with each styled frame as well as the original frame.  The script requires ffmpeg to stitch the images into a video.

A forked version of https://github.com/futscdav/strotss. See the original code and links to paper at https://github.com/nkolkin13/STROTSS

Usage:
```
python strotss.py <content> <style> [--weight 1.0] [--output strotss_animation] [--animation_fps 10] [--resize_to 512] [--device "cuda:0"]
```

<p align="center">
  <img src="content.jpg" width="350" title="Content">
  <img src="style.png" width="350" alt="Style">
  <img src="strotss.png" width="350" alt="Result">
</p>
