# Forgery Detection System
In today’s technical world, the digital image is a vital part of many application domains. The meaning of image forgery is the manipulation of digital images to hide important information or output false information. Due to the introduction of modern image processing tools, digital image forgery is at its peak. Copy-move forgery is one of the most commonly used techniques to perform image forgery. The aim of the proposed system is to detect and highlight the malpractices performed on modern-day digital images.

# Forgery Detection System
The Forgery Detection System contained in this repository currently features forensic methods to detect the following:

- Double JPEG compression
- Copy-move forgeries
- Metadata Analysis
- CFA artifacts
- Noise variance inconsitencies
- Error Level Analysis
- Image Extraction
- String Extraction
- For More Detail - [Research Paper](https://www.jetir.org/papers/JETIR2504B38.pdf)

## To Run:
<!-- Place any(JPEG) images that you wish to analyze into the **image** folder Present in the Project directory. -->

Navigate to the **Project** directory:
```
$ cd Forgery-Foresight
```

Next, run the **detect.py** script, providing the image you wish to evaluate:
```
$ python GUI.py
```

Once finished, details on the image will be reported in the terminal. Supplemental images generated during copy-move forgery detection can be found in the output directory.

##  IMAGES
<img src="Screenshot/1.jpg">
<img src="Screenshot/2.jpg">
