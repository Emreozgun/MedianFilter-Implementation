
# Median Filter Implementation with different ordering methods

Salt-and-pepper noise is a form of noise sometimes seen on images. It is also known as impulse noise. This noise can be caused by sharp and sudden disturbances in the image signal. It presents itself as sparsely occurring white and black pixels.

An effective noise reduction method for this type of noise is a **median filter** or a morphological filter.I have been implemented median filter with three different ordering methods.These are Lexicographical ordering, Bitmix ordering and Norm based ordering.The median filter run through each element of the signal (in this case the image) and replace each pixel with the median of its neighboring pixels (located in a square neighborhood around the evaluated pixel).I want to observe different methods on median filter and comparing these.

> This project is an application that runs through the console.

![Badges](https://img.shields.io/badge/linux-shell-green) 
![Badges](https://img.shields.io/badge/shell-commands-lightgrey)
![Badges](https://img.shields.io/badge/love-coding-black.svg)
![Badges](https://img.shields.io/badge/core-dumped-red)
![Badges](https://img.shields.io/badge/lsf-wc-yellow)
![Badges](https://img.shields.io/badge/build-passing-succes.svg)
![Badges](https://img.shields.io/badge/test-success-success.svg)
![Badges](https://img.shields.io/badge/computer-science-critical.svg)
![Badges](https://img.shields.io/badge/love-linux-yellow.svg)
![Badges](https://img.shields.io/badge/coding-life-red.svg)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Badges](https://img.shields.io/badge/open-source-blueviolet.svg)

## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Results](#results)
- [Support](#support)

## Installation

- All the `code` required to get started

### Clone
- Install python3 and PILL
-**sudo su** - to root 
- **"apt-get update && apt-get install python3.6"** - to install python3
- **"python3 -m pip install Pillow"** - to install PILL 
- Clone this repo to your local machine using `https://github.com/Emreozgun/MedianFilter-Implementation.git`
- Then open the terminal and go to the directory where the file is located.
- Run with **python3 MedianFılter.py** 


## Features
  ### Lexicographical ordering 
  >
  ### Bitmix ordering
  >
  ### Norm based ordering
  > 

## Results 
 ### First picture - Sample
![b](https://user-images.githubusercontent.com/30092986/92998200-2a434900-f521-11ea-827b-17f296c15288.png)
 ### Scalar implementation - Result 
![b png_scalar_](https://user-images.githubusercontent.com/30092986/92998079-7e99f900-f520-11ea-94b4-a1787292051e.png)
 ### Norm based ordering - Result
 ![b png_vector_norm_based_ordering](https://user-images.githubusercontent.com/30092986/92998267-75f5f280-f521-11ea-97f9-0852dd200796.png)
 ### Lexical ordering - Result
 ![b png_vector_lexicographical_ordering](https://user-images.githubusercontent.com/30092986/92998278-8efea380-f521-11ea-86ea-1acb5c4b3198.png)
 ### Bitmax ordering - Result 
 ![b png_vector_bitMix_ordering](https://user-images.githubusercontent.com/30092986/92998292-a6d62780-f521-11ea-9f3b-fbbaf9471e34.png)
 ### Opencv Median Filter - Result
 ![result_opencv](https://user-images.githubusercontent.com/30092986/92998576-2b757580-f523-11ea-8f70-9b67b8a71401.jpg)
  
## Support

Reach out to me at one of the following places!

- Linkedin at <a href="https://www.linkedin.com/in/emre-ozgun" target="_blank">`Emre_Ozgun_linkedin`</a>
- Stackoverflow at <a href="https://stackoverflow.com/users/12690037/emre-ozgun" target="_blank">`Emre_Ozgun_stackoverflow`</a>

---
