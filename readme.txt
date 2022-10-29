installation

1)  run the following command in your Terminal/Command Prompt to install the libraries required
    pip install -r requirements.txt

2)Open terminal. Go into the cloned project directory and type the following command:
   python train_mask_detector.py --dataset dataset

3) To detect face masks in an image type the following command:
     python detect_mask_image.py --image images/pic1.jpeg

4) To detect face masks in real-time video streams type the following command:
     python detect_mask_video.py 