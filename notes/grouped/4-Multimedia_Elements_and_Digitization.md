# Images , Colors and Videos #

## Table of Content ## 
| Table of Content |
| :------------------- | 
| [Source](#Source)|
| [Homework](#Homework) |
| [Image Colors](#Image-Colors) |
| [Videos](#Videos) |
| [Keywords](#Keywords) |

## Source ##

| Images, colors and videos |
| :------------------- | 
| [8 December 2021](https://github.com/SMSOSS/ict_notes/blob/master/notes/08Dec.md)|
| [9 December 2021](https://github.com/SMSOSS/ict_notes/blob/master/notes/09Dec.md) |
| [15 December 2021](https://github.com/SMSOSS/ict_notes/blob/master/notes/15Dec.md) |
| [16 December 2021](https://github.com/SMSOSS/ict_notes/blob/master/notes/16Dec.md) |
 
## Homework ##
-  [google form](https://docs.google.com/forms/d/e/1FAIpQLSdA_swHfVyhCcZf7cMGXOF92vj9A93O9WhjBJncKZ4pY9JCZA/viewform?hr_submission=ChgIn5r6vj0SEAjC6r6z8gwSBwjG9KnypAsQAQ)

--- 

## Image Colors ## 
### Color depth ###
-  **Color depth(色彩深度)** is used to indicate the color in one pixel
-  Also known as number of color : ``` 2^0 = 1-bit(Black and White) |||  2^8 = 8-bit(RGB)```  

### Bitmap ###
-  **Bitmap** is a file format that stores colors so that it form a image
-  Screen is divided into pixels -> Combine it to form a bitmap
-  Currently used bits : ``` 24-bits(8 Red 8 Green 8 Blue) ||| 32-bits(8 Cyan 8 Magenta 8 Yellow 8 Black)```
-  How to show colors(24 bit) :  ```show Red -> 8 Red 0 Green 0 Blue ||| show Black -> 8 Red 8 Green 8 Blue```
-  Currently used resolutions : ``` 1920x1080 (mainly used for PCs) ||| 1080x1920(mainly used for phones)``` 

### Imaging ###
-  Video quality(720p 1080p etc)
    - 720p = HD (YouTube HD is 1080p)
    - 1080p = Video that consists image of 1920x1080
    - 1080i = Used when TVs only had 50Hz refresh rate(Generate half an image per scan -> trick our brain that we're seeing full)
    - 2k = 2560x1440 
    - 4k = 3840x2160
    - 8k = 7680x4320
    - resolution **increases** -> size of file **increase** too
-  Compression(影像壓縮)
    - 2k monitor but source only 1080p ? -> Oh no! Compression will be involved
    - **Lossy conversion** : Display colors close enough to be useful (combines similar colors -> not a lot of detail)
    - **Loseless conversion** : Display all colors truly (no combines similar colors -> lot of detail) 

### Image File Types ###
-  BMP(bitmap image file)
    - No compression is invovled -> **largest** in file size
-  JPG 
    - A lot of compression -> **smallest** in file size
-  PNG
    - Not that much of compression -> **smaller** file size , compared to BMP
-  GIF
    - Bunches of photos(like animation)
    - File size varies
-  TIFF(Tag Image File Format)
    - No compression is involved 
    - Usually used by scanners -> preferred by photographers , digital artists , etc
-  RAW
    - No compression is involved
    - Usually used by scanners -> extremely uncommon
    - Normal image / editors **can't** view/edit them           

### Calculation of Image file size ###
- Resolution × Color Depth 
- Remember to convert color depth to bytes a!
--- 

## Videos ## 
### Videos ###
-  Made up of audio(soundtrack) and a lot of images
-  FPS(Frames Per Second)
    - How many pictures are there per second ? (60/90/120/144/More)
    - **higher** FPS -> **more** stuff animations "seem" to be
    - Humans can sometimes read up to 1000FPS (More than 1000 FPS = 1000FPS as we can't even see all frames)
-  Resolution / Frame Size : Same as picture
-  Color Depth 
    - number of bits used to indicate the color of a single pixel (usually 10/12/24 bits)
-  Compression (same with images)
    - **Lossy conversion** : Combine similar colors into one color (**smaller** file size but **lower** quality in return)
    - **Loseless conversion** : No dirty hack , save whatever is recorded (**larger** file size) 

### Calculation of Video file size ###
- Frame size x Frame rate x color depth / compression ratio x duration(seconds)
- Bitrate x duration(seconds) 

### Video Format ###
-  AVI
    - Usually **largest** file size 
    - sometimes uncompressed -> better quality
-  MP4
    - **Smaller** file size
    - "Acceptable video quality (how vague!!)
-  WMV(Windows Media Video)
    - Usually seen in Windows
    - Supported by Windows primarily -> not really cross-platform
-  MOV
    - Usually seen on Apple software
    - QuickTime video    
-  FLV(Flash Video)
    - Flash is dea now so rest in peace \\|/
-  AVI and MP4 is used more commonly nowadays  

### Streaming ###
- To make you able to view videos more quicker , **streaming(影音串流)** has been introduced
- It works by caching your videos for few seconds
- Streaming != Live (streaming doesn't have to be live)
- Video is playing when video is downloading 
- Data used by streaming = Data used by downloading whole video (can't save cellular data)
- limitations : Net speed makes video unplayable (fix by buffer time)

---

## Keywords ##
-  Color depth 
-  bitmap
-  image compression
-  streaming
-  video quality
