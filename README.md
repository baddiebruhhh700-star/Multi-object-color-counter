          # Multi-object-color-counter
DETECT AND COUNTS COLORED OBJECTS USING OpenCV- HSV MASKING, MORPHOLOGY  & and; COUNTOR .
             #### WHAT ITS DOES
Load an image and convert to HSV color space
isolate a red ball using cv2.inRange()
Cleans the result masking with morphological operations
Detects objects boundaries with cv2.findcontours()
Filter out noise by contour area
Draws bounding boxes around detect object
Display a live object count on the output image 

            ###PIPELINE 
IMAGE LOAD , HSV CONVERSION , COLOR MASK, MORPHOLOGY(CLOSE THEN OPEN) , CONTOUR DETECTION , AREA FILTER, BOUNDING BOXES , SAVE , SHOW.

              ##KNOWN LIMITATIONS

HSV-based detection is sensitive to lighting and struggles with strongly reflective or glossy surface , real world objects with uneven lighting may need per image threshold tuning

It work on single color per run , multi-color detection would need separate masking passes

static image only in this version , no video or live tracking.

            ## REQUIREMENT 
OPENCV-PYTHON            NUMPY 

             ## USAGE

  python multiple_obj_color_contour.py

   I WILL UPDATE LOWER_HSV/ UPPER_HSV VALUES AND IMAGE PATH FOR YOUR OWN TARGET COLOR IMAGE.
