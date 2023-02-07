# deepface
Deep Face Recognizing library using Docker and Rest API

This project will take a large volume of images (jpeg, png, or tiff) and extract all of the faces and create a database of faces and images.

Project Goals:
1. Use DOCKER iamge for running the code
2. Accessible via Rest API for controlling the process
3. Ability to process over 100,000 images unattended
4. Produce the following output:
     a. Face images for all files
     b. Database (SQL) export/import
        i. Image size and type
        ii. number of images in the processed directory
        iii. Image tested for working.
     c. MD5 fingerprint for all images.
     d. Processing Logs
5. Ability to add EXIF tags on images for future tracking
      a. Original Filename
      b. Recognized Name if exists
      c. Date of Processing
      d. Original Data (Pass thru)
      e. Partial contstructs from filename
     
5. Example Code to be provided
     a. How to create an initial database
     b. How to process a large number of files.
     c. Multithreaded workers/processors to handle large amounts of work.
     
6. Project will support use of CPU or NVIDIA GPU
