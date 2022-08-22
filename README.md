# Dissertation2020
(It's 2022! But I put this to commemorate the year I met my lovely partner... No. Just a typo...)

## Deep Learning Based Human Body Size Measurement Application
The application measures the body size using the height. It displays 5 dimensions (sleeve length, inseam, chest girth, waist girth and hip girth)

<br>This application runs throught the Jupyter Notebook file scripted by Python. How does it work? 

0. Check the 'run.ipynb' file first. It's an operation file.
<br>1. Change the 'image_route' and 'side_image_route' with the route of images the user wants to put. <br>
(The default images are set and you can try these if you want to check the running of the app without other images. Yes. They are me. I should have tightened my abdomen.) 
<br>2. Change 'output_route' to the name of file you want to get. Normally .png, .jpg are the safe options.
<br>3. Change 'body_height' to the person's height in the image.
<br>4. Do not touch threshold unless you want to do some experimentation of the deep learning model. The higher the threshold is, the stricter the model judges the body parts.
<br>5. Do not also fontsize and spacing unless the letter on the images are too small to you.
<br>6. Once you finish the input chunk of the notebook, run the second chunk of codes. It will show the merged image with two photos and the estimated measurement of the person in the images.
<br>(It can take about 30 seconds to finish)
<br>7. Once it's finished, it's finished. Check your measurements and see how accurate they are.

