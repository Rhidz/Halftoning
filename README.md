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

  #### Error diffusion is a technique used in halftoning to distribute the quantization error, which occurs when representing continuous tones using a limited set of discrete levels or colors, across neighboring pixels. It is commonly employed to achieve high-quality halftone images with smoother transitions and reduced visibility of artifacts. In the process of error diffusion, each pixel in an image is quantized based on a predefined threshold or quantization table. The quantization error, which is the difference between the original pixel value and the quantized value, is then distributed to the neighboring pixels in a controlled manner. The basic idea behind error diffusion is to consider the future pixels during the quantization of the current pixel. The quantization error is distributed to the neighboring pixels, typically in a weighted manner, based on their proximity and influence on the current pixel. This distribution helps spread out the error and compensates for the loss of information due to the limited number of available levels.

  <img src="https://github.com/Rhidz/Halftoning/blob/main/dog_ed.png" align="center"
     width="400" height="400">

* Blue Noise Dithered Image:

  #### Blue noise refers to a specific type of noise that exhibits desirable properties when used in halftoning and other image processing applications. It is a type of random noise with a spectral distribution that emphasizes higher frequencies while minimizing low-frequency components.

  <img src="https://github.com/Rhidz/Halftoning/blob/main/blue.png" align="center"
     width="400" height="400">

* White Noise Dithered Image:

    #### White noise in halftoning refers to a type of random noise that is evenly distributed across all frequencies. It is named "white" because it is analogous to white light, which contains an equal amount of energy across the visible spectrum.

  <img src="https://github.com/Rhidz/Halftoning/blob/main/white.png" align="center"
     width="400" height="400">

  
