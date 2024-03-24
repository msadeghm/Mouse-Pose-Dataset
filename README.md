# Mouse-Pose Dataset

The Mouse Pose dataset is essential for detecting and tracking the pose of mice within a vivarium environment. This dataset consists 1560 images, each has 20 mice. This dataset consists of a meticulously curated collection of images extracted from videos recorded within our vivarium archive, which houses a population of 20 mice in enriched environments. These videos, categorized by gender, capture various environmental conditions such as food and water sections, both within and outside the vivarium.

# Annotation Process
The annotations of each image include bounding boxes for each mouse within the image, along with keypoint annotations that denote key anatomical landmarks on the mouse, such as the snout, ears, hips, base tail, and tail tag. These annotations follow the COCO format, incorporating three key values: the x-coordinate, y-coordinate, and visibility status of each keypoint. Visibility status is color-coded, with blue denoting "visible" keypoints and red indicating "non-visible" keypoints. Annotations are then converted into the TXT format, adhering to the YOLO standard.
