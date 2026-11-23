# Video-To-Selective-Color
Gives your video a black-and-white look with a few objects left in color or sepia ("selective color"), similar to the effect in noir-ish movies like Sin City.

These are loose scripts I originally used on a couple music videos recently which I went ahead to package into something more reusable.

Download here: https://github.com/pftq/Video-To-Selective-Color/releases/tag/20261120<br>
You may also find these useful (one-click to download all [here](https://drive.google.com/drive/folders/1nvQFC5uwsZlf-82LuskCP-qut9xHw-lt?usp=sharing)):\
• [Video Debanding](https://github.com/pftq/Video-Debanding) (fixes quality issues with repeat re-processing/compression)\
• [Video Compare](https://github.com/pftq/Video-Compare) (to check export errors, differences, etc)\
• [MP4 Audio Delay Fix](https://github.com/pftq/MP4-Audio-Delay-Fix) (20ms delay at start of file)\
• [Video Frame Sync](https://github.com/pftq/Video-Frame-Sync) (syncing 2 files that drift out of sync)\
• [Video Mask](https://github.com/pftq/Video-Mask) (mask, sync, color-correct, and merge changes in one tool)\
• [Video Color Match](https://github.com/pftq/VideoColorMatch) (correcting color grading drift)\
• [Video Splicer](https://github.com/pftq/Video-Splicer) (trim or join MP4s without re-encoding)\
• [Screencaps Generator](https://github.com/pftq/Screencaps-Generator) (smart screencaps selection + gallery grid sheet)


https://github.com/user-attachments/assets/b3c5dd24-5d52-4a02-940a-746f75e224be



https://github.com/user-attachments/assets/32b33f75-1fa8-444a-a790-9e2772e6a668



<img width="669" height="469" alt="2026-11-20-16-13-19 00_00_43_11" src="https://github.com/user-attachments/assets/d04b7e5d-3273-4598-9a26-912ffd012b45" />

<img width="991" height="688" alt="image" src="https://github.com/user-attachments/assets/3f8572bd-7d4c-4bd4-bb25-03a8e112652b" />

It works on still images too.
<img width="669" height="469" alt="AlbumArt" src="https://github.com/user-attachments/assets/d0490771-eb0d-498b-ac40-f8578837e613" />


Credits
- [Python](https://www.python.org/), application runtime
- [Tcl/Tk](https://www.tcl.tk/) via Tkinter, desktop interface
- [PyAV](https://github.com/PyAV-Org/PyAV), video decoding for preview and scrubbing
- [FFmpeg](https://ffmpeg.org/) and [x264](https://www.videolan.org/developers/x264.html), media processing, audio handling, and H.264 export
- [OpenCV](https://opencv.org/), object selection, reference-image matching, and mask processing
- [NumPy](https://numpy.org/), color grading, film grain, and dust effects
- [Pillow](https://python-pillow.org/), reference thumbnails and preview display
- [PyInstaller](https://pyinstaller.org/), Windows executable packaging
