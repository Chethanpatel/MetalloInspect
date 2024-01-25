# MetalloInspect

## Metal Surface Defect Detection

MetalloInspect is a deep learning project designed for the classification of six possible defects on metal surfaces using state-of-the-art techniques. The goal is to accurately identify and categorize the following defects:

- 0: Crazing
- 1: Inclusions
- 2: Patches
- 3: Pitted Surface
- 4: Rolled in Scale
- 5: Scratches

### Datasets

Two types of datasets were employed in the project:

1. **Small Dataset**
   - Images: 90 (15 for each defect)
   - Training Set: 60 images
   - Test Set: 30 images

2. **Large Dataset (Best Results)**
   - Images: 1800 (300 for each defect)
   - Training Set: 1620 images
   - Test Set: 180 images

### Implementation

The entire project was implemented using Python, and the code along with detailed comments and outputs can be found in the [Jupyter Notebook](Metal_Surface_Defects_Detection.ipynb).

### Results

The best results were achieved with the large dataset, demonstrating the effectiveness of deep learning in metal surface defect detection.
