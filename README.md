# AWS_Cloud_Practitioner_Slides
Slides for [freeCodeCamp's AWS course](https://www.freecodecamp.org/news/aws-certified-cloud-practitioner-certification-study-course-pass-the-exam/).

The repo contains a pdf with all the slides in titled: `all_slides.pdf`.\
The `slides_by_chapter` directory holds 27 pdf files for slides split by topic chapter.

## How the slides were generated
This repo was created using the Python Pillow image library and Jupyter Notebook. 
We started off from [repo](https://github.com/Mainak99/AWS-Slides) by user **Mainak99**.\
The repo contains images of each slide as PNGs. 
Using the code in the .pynb file in this repo we iterate through each image file and add it to a nested array sorted by chapter.
We use Image.save method to convert the image to pdf and use the `append_images` to group slides together in one pdf.
