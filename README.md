## Image Data Cleaning Helper Functions
#### Convert PDF to images and delete the original pdf 
  pdf2img.ipynb

#### Delete corrupted images that cannot be read by opencv 
  remove_corrupt_files.ipynb

#### Delete duplicate files
  Make sure to check the duplcates before deleting. Some files with a very small difference may be considered as same files.
  remove_duplicates.ipynb
   
#### Convert Object Detection labels 
Convert Object Detection labels labelled using [vgg-image-annotator](http://www.robots.ox.ac.uk/~vgg/software/via/via-1.0.6.html) to YOLO-v3 format and split data for train and valid 
vgg2yolo.ipynb
