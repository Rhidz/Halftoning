# Halftoning
Digital Halftoning of Continuous-Tone Images and Halftone Removal



<img src="https://github.com/Rhidz/Halftoning/blob/main/Halftoning.png" align="center"
     width="600" height="400">
     


Halftoning is a technique used in printing and image processing to reproduce continuous-tone images using limited sets of discrete tones or colors. It is primarily used when reproducing images with grayscale or full-color content on devices that are only capable of producing binary or limited color output, such as black-and-white printers or newspaper presses.

The goal of halftoning is to simulate the appearance of shades of gray or different colors by varying the density or arrangement of small dots or patterns. These dots or patterns, called halftone dots, are typically of equal size but vary in their spacing or placement. When viewed from a distance, the human eye perceives the arrangement of dots as different shades or colors.

# Algorithms Implemented

Image before any of the following algorithms are applied:

<img src="https://github.com/Rhidz/Halftoning/blob/main/dog.jpg" align="center"
     width="400" height="400">

* Independent Quantization:
   
  #### In the context of grayscale images, independent quantization refers to the process of quantizing the intensity values of each pixel independently. Instead of treating the entire grayscale image as a whole, independent quantization analyzes and quantizes the intensity values of individual pixels separately. Typically, grayscale images represent each pixel's intensity with a single value, ranging from black (minimum intensity) to white (maximum intensity). When applying independent quantization in halftoning grayscale images, the goal is to transform these continuous intensity values into a limited set of discrete tones or levels.

  <img src="https://github.com/Rhidz/Halftoning/blob/main/dod_iq.png" align="center"
     width="400" height="400">

* Error Diffusion:

  <img src="https://github.com/Rhidz/Halftoning/blob/main/dog_ed.png" align="center"
     width="400" height="400">

* Blue Noise Dithered Image:

  <img src="https://github.com/Rhidz/Halftoning/blob/main/blue.png" align="center"
     width="400" height="400">

* White Noise Dithered Image:

  <img src="https://github.com/Rhidz/Halftoning/blob/main/white.png" align="center"
     width="400" height="400">
  

  
