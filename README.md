# GrayscaleImageBoxFilter
## Purpose
Smoothing is an image processing technique used to blur, remove small details and reduce the noise of an image. There are different filter types, such as linear and non-linear. The filter for this project was a 3*3 box filter. The box filter is the mean of the neighbouring pixel intensities. In this project, we explore how the box filter affects different images.

![Screenshot 2023-10-16 at 3 07 51 PM](https://github.com/DavidGuamanDavila/GrayscaleImageBoxFilter/assets/92492748/b9617969-eb44-4293-9cc2-ce4c216a0c8d)


## Procedure How to Run Tasks
### boxfilter.py File Procedure
#### Imports Required
- Import OS
- Import cv2
- Import numpy
#### Steps to Run Program
1. Clone the repo or fork the repo
2. Open your terminal and cd into the repository
3. Inside the repository depending on your terminal alias run: python3 boxfilter.py OR python boxfilter.py
4. Type the path of the image you want to open. For example: ~/Documents/trial.jpeg. Then the image will be displayed in the grayscale mode.

![Screenshot 2023-10-16 at 2 57 16 PM](https://github.com/DavidGuamanDavila/GrayscaleImageBoxFilter/assets/92492748/06cac6c7-d4d5-4d17-bbf8-e0a6c713edbf)

5. In the background, filtering is performed. The new image is saved, and both the original grayscale and the filtered image will be displayed.

Example of a padded image:

![Screenshot 2023-10-16 at 2 57 36 PM](https://github.com/DavidGuamanDavila/GrayscaleImageBoxFilter/assets/92492748/cfefdeb2-2929-4e99-8de5-b58372bde094)


Resultant message from the terminal:

![Screenshot 2023-10-16 at 2 57 53 PM](https://github.com/DavidGuamanDavila/GrayscaleImageBoxFilter/assets/92492748/3d32b501-45fd-44b6-a000-93fc41f2645f)


#### Results on Testing First Image

![Screenshot 2023-10-16 at 2 58 26 PM](https://github.com/DavidGuamanDavila/GrayscaleImageBoxFilter/assets/92492748/88f1f105-dde9-492c-9a35-fb87589b00e7)


The original image is on the left, and the resulting image is on the right.

#### Results on Testing Second Image

![Screenshot 2023-10-16 at 2 58 39 PM](https://github.com/DavidGuamanDavila/GrayscaleImageBoxFilter/assets/92492748/96810955-3ec7-435f-8111-29e931f8f165)


The original image is on the left, and the resulting image is on the right.

#### Results on Testing Third Image

![Screenshot 2023-10-16 at 2 58 50 PM](https://github.com/DavidGuamanDavila/GrayscaleImageBoxFilter/assets/92492748/129086cd-c047-452d-84fb-27b095481f20)


The original image is on the left, and the resulting image is on the right.

#### Results on Testing Fourth Image

![Screenshot 2023-10-16 at 2 59 09 PM](https://github.com/DavidGuamanDavila/GrayscaleImageBoxFilter/assets/92492748/ee8a0085-b732-4854-863f-81ec9728b369)


The original image is on the left, and the resulting image is on the right.

#### Results on Testing Fifth Image

![Screenshot 2023-10-16 at 2 59 21 PM](https://github.com/DavidGuamanDavila/GrayscaleImageBoxFilter/assets/92492748/a8c9933e-1e0d-4695-8902-7737e7ba3356)


The original image is on the left, and the resulting image is on the right.

### Overview boxfilter.py
1. User Image Input, Path Validation & Grayscale Conversion
The user provides the file path of an image. Also, the code checks if the file path is valid. Finally, using OpenCV, the image is loaded and displayed in grayscale mode.
2. Image Padding
A 1-pixel black border is added to the grayscale image to facilitate filtering.
3. Image Filtering
- A simple 3*3 filter matrix is applied to the image, performing a basic convolution operation.
- The filtered output image is generated.
4. Display Original vs. Filtered Images
The original grayscale image and the filtered image are displayed side by side for comparison.
5. Image Saving
The filtered image is saved with the filename **result_filtered_img.jpg**   

## Contributions of Each Group Member
Both Aabir Basu and Anton Guaman  worked to complete this project collaboratively by following the extreme programming methodology, most notably that of pair programming. All project requirements were distributed equally among the two group members through a mutual understanding of each other's strengths and schedules. All deliverable code was continuously peer-reviewed to ensure that development did not regress. Issues were made at each stage before a feature was added, helping the group keep track of what needed to be done and what was already implemented. 
