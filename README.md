# Online_Summer_Internship_2026

## WEEK 1

**_TASK 1- Extract Frames from a Video_**

Download a 1 minute Youtube video and extract frames from it using ffmpeg.



**_TASK 2- Stitch the frames extracted from Task 1 to make a Video_**

Reconstruct the video from the 1800 frames extracted from the 1 minute clip.


**_TASK 3- Add Audio to the Video made in Task 2_**

Merge an audio to the reconstructed video


## WEEK 2

**_Task 1, 2, 3_**

Create a Virtual Environment for Python using venv.

Install ultralytics package.

Run object detection code on pretrained YOLO26 model.

**_Extended Task_**

Apply object detection technique on multiple images and reconstruct them into a video having audio.

## WEEK 3

**_Task 1- Semantic Segmentation of images_**

Apply the object segmentation technique on multiple image and reconstruct them into a video with audio.

**_Task 2- Stack three videos vertically_**

Stack the three videos i.e. raw, object-detected and object-segmented into a single video using vstack and add audio to it.

## WEEK 4

**_Task 1- YOLO Analysis Configuration Report_**

Explore YOLO dataset directory structure and configuration files, also analyze YOLO label files containing class IDs and normalized object coordinates used for object detection training.

**_Task 2- Create a YOLO-Compatible dataset_**

Create a YOLO-compatible labeled dataset using Label Studio in a separate virtual environment by extracting image frames from a real-world object detection video. Generate files required for training and validation using the YOLOv26 framework.

## WEEK 5

**_Task 1 - 5_**
1. Annotate images using label-studio, generating YOLO-compatible label files along with train/val splits and configuration files.
2. Resize images to lower resolution(384px width) using ffmpeg.
3. Train a pretrained YOLO model using the prepared dataset and monitor its performance.
4. Use the trained weights to run interface on unseen test images.
5. Generate video from predictions, stack the video with the input video for comparision, also add audio to it.
