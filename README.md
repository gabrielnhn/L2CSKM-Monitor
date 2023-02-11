# L2CSKM-Monitor

#### Install all requirements:
```bash
pip install -r requirements.txt 
```

#### Get the gaze estimation model L2CSNet_gaze360.pkl from [here](https://drive.google.com/drive/folders/17p6ORr-JQJcw-eYtG2WGNiuS_qVKwdWd?usp=sharing) or [here](https://github.com/Ahmednull/L2CS-Net).
* Store it in the `./models/` folder


#### Run the monitoring system:
```bash
python3 driver_monitoring_system.py --gaze_model ./models/L2CSNet_gaze360.pkl --gpu 0 --video_source {{SOURCE}} --video_output {{OUTPUT}} --distraction_model ./models/gnb.pkl
```

