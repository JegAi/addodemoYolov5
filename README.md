# addodemo
this repository is aimed  to host a yolov5 implementation  with the purpose of show Ai capabilities in the food industry  

workink env 5.6
backup env 5 and 5.0

# Yolov5 repository

    git clone https://github.com/ultralytics/yolov5.git

    pip install -U -r requirements2.txt

# making of virtual enviroment addodemoYolo5

    conda create -n <name> python=3.8

# installinh pytorch with gpu support

    # usefull link https://www.fatalerrors.org/a/the-most-detailed-yolov5-environment-configuration-in-history.html
    pip install torch===1.7.0 torchvision===0.8.1 -f https://download.pytorch.org/whl/torch_stable.html -i https://pypi.douban.com/simple

# runing commands

    # 1. Inference

    `detect.py` runs YOLOv5 inference on a variety of sources, downloading models automatically from the [latest YOLOv5 release](https://github.com/ultralytics/yolov5/releases), and saving results to `runs/detect`. Example inference sources are:

    ```shell
    python detect.py --source 0  # webcam
                            img.jpg  # image 
                            vid.mp4  # video
                            path/  # directory
                            path/*.jpg  # glob
                            'https://youtu.be/Zgi9g1ksQHc'  # YouTube
                            'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream
```





