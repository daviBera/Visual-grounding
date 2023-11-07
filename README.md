# Visual Grounding with YOLOv5 and CLIP

This is the final assignment of my Deep Learning course.

In this project we address the problem of visual grounding, which involves linking language and perception by grounding. Our task is to build, fine-tune, and evaluate a deep learning framework that can learn to perform visual grounding on a given dataset. Specifically, we train our model to predict a set of bounding boxes in each image that correspond to the entities referred in the textual descriptions.

To address this task, we leverage the power of the **[YOLO v5](https://github.com/ultralytics/yolov5.git)** (You Look Only Once) object detector and the **[CLIP](https://github.com/openai/CLIP.git)** (Contrastive Language-Image Pre-training) model.
We test and fine-tune our model on the **RefCOCOg** dataset, comprising 25,799 images, each of which contains an average of 3.7 referring expressions.

## Collaborators

- **[@daviBera](https://github.com/YourGitHubUsername)**
- **[@ValentinaFusa](https://github.com/ValentinaFusa)**
- **[@LuciaXausa](https://github.com/LuciaXausa)**

## Usage

The Jupyter Notebook is runnable. We recommend to run it using a GPU for faster execution.
