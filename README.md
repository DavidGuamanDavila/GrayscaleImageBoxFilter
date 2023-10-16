# GrayscaleImageFilter
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
![Screenshot 2023-10-14 at 12 31 50 AM](https://github.com/MUN-McIntyre/project-2-a2-aabirbasu-1630-antonguaman-4155/assets/92492748/5c55de8a-e09a-49c5-9cf3-84b701cd5029)
5. In the background, filtering is performed. The new image is saved, and both the original grayscale and the filtered image will be displayed.

Example of a padded image:

![padded_image](https://github.com/MUN-McIntyre/project-2-a2-aabirbasu-1630-antonguaman-4155/assets/92492748/b8ec7202-112d-41d2-9221-379676a5fde0)

Resultant message from the terminal:

![Screenshot 2023-10-14 at 12 34 02 AM](https://github.com/MUN-McIntyre/project-2-a2-aabirbasu-1630-antonguaman-4155/assets/92492748/3581e775-5f07-45d7-92e0-dc500fde3770)

#### Results on Testing First Image

<img width="1001" alt="Screenshot 2023-10-14 at 12 31 27 AM" src="https://github.com/MUN-McIntyre/project-2-a2-aabirbasu-1630-antonguaman-4155/assets/92492748/9c2acb6c-73a2-47a4-88e3-475b291659ed">


The original image is on the left, and the resulting image is on the right.

#### Results on Testing Second Image

<img width="502" alt="Screenshot 2023-10-14 at 12 37 25 AM" src="https://github.com/MUN-McIntyre/project-2-a2-aabirbasu-1630-antonguaman-4155/assets/92492748/0e7a2930-6467-417a-8bf6-a1aefab85791">

The original image is on the left, and the resulting image is on the right.

#### Results on Testing Third Image

<img width="1231" alt="Screenshot 2023-10-14 at 12 37 53 AM" src="https://github.com/MUN-McIntyre/project-2-a2-aabirbasu-1630-antonguaman-4155/assets/92492748/cc982750-6b2d-47c7-bcea-000c2313a421">

The original image is on the left, and the resulting image is on the right.

#### Results on Testing Fourth Image

<img width="1369" alt="Screenshot 2023-10-14 at 12 38 24 AM" src="https://github.com/MUN-McIntyre/project-2-a2-aabirbasu-1630-antonguaman-4155/assets/92492748/4669b52c-3226-48f6-bb4d-59e105d4b6e0">

The original image is on the left, and the resulting image is on the right.

#### Results on Testing Fifth Image

<img width="962" alt="Screenshot 2023-10-14 at 12 39 07 AM" src="https://github.com/MUN-McIntyre/project-2-a2-aabirbasu-1630-antonguaman-4155/assets/92492748/7cab2485-0941-41d6-b6ab-8a389768a748">

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
