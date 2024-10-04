# Avataar_Assignment

## Table of Contents

- [Introduction](#introduction)
- [Implementation](#implementation)
- [Image uploaded by user](#image_uploaded_by_user)
- [Object_segmented](#object_segmented)
- [Object's position changed](#object's_position_changed)

## Introduction
This project focuses on interactive object segmentation and manipulation using the Segment Anything Model (SAM). The core objective is to enable users to upload images, segment specific objects, and perform transformations like moving or manipulating the segmented object. SAM, developed by Meta AI, is a state-of-the-art model for object segmentation, capable of identifying various objects in an image without specific annotations.

## Implementation
1. Environment Setup: Install necessary libraries (PIL, matplotlib, ipywidgets, torch, SAM) and configure GPU for model acceleration.

2. Argument Parsing: Use argparse to simulate command-line inputs for object class (--class) and output file (--output).

3. Image Upload: Load and display user-uploaded images using PIL and matplotlib or ipywidgets for an interactive experience.

4. Object Segmentation: Use SAM to segment objects based on predefined classes (e.g., stool, shelf) using bounding boxes.

5. Object Manipulation: Manipulate the segmented object (e.g., move it) within the image by adjusting its location.

6. Save Output: Save the final image with the manipulated object to the user-specified output path.

## Image uploaded by user

![image](https://github.com/user-attachments/assets/4887828d-c2f9-4b17-98eb-1432739e302e)

## Object segmented

![image](https://github.com/user-attachments/assets/692535c1-6e58-4d39-928c-6127d05180d4)

## Object's position changed

![image](https://github.com/user-attachments/assets/e0421674-96ef-4abd-b7df-d9928d0c2bf3)


