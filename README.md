# AR Book Cover Project - "Fourth Wing" by Rebecca Yarros

All files avaliable in [this Box folder](https://vanderbilt.box.com/s/539mvsi04w69feg0qbur6off1p880i9o) because the project could not be uploaded to Github due to its size.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [How to Use](#how-to-use)
- [Limitations](#limitations)
- [Contributing](#contributing)

## Features

1. **Front Cover:**
   - Augmented text displaying the title and author.
   - Two animated dragon models, one black and one golden, important characters in the book.
   - The cover itself is replaced by a blurred digital version, which one of the dragons standing on it, and the other flying above.

3. **Back Cover:**
   - Augmented reality text displaying relevant information about the book (title, author, number of pages, publication date, ISBN).
   - AR button to toggle between book details and a short review created for the book.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Unity installed on your machine.
- Vuforia SDK integrated into your Unity project. Follow the [Vuforia in Unity guide](https://library.vuforia.com/articles/Training/getting-started-with-vuforia-in-unity.html).

### Installation

1. Download the project zip file from [Box](https://vanderbilt.box.com/s/8k8h8ju21l10acdnmsakofkjxzvktvkm).

2. Extract the contents of the zip file to your desired location.

3. Open the project in Unity.

4. Run and track the book using the computer's webcam.

5. Have the book handy of print the images from [front](https://vanderbilt.box.com/s/ez0elkownwpo5i19px4h7hiqy2lbo1fs) and [back](https://vanderbilt.box.com/s/drga1hcngojxw2igio3n1vmz49y5y6d7) covers.

## How to Use

1. **Front Cover:**
   - Launch the AR application.
   - Point your device's camera towards the front cover of "Fourth Wing - Holiday Edition"
   - Experience the AR content.

2. **Back Cover:**
   - Flip the book to the back cover.
   - Use the AR button to switch between book details and a short review.
  
## Video Demo

<video width="640" height="360" controls>
  <source src="https://vanderbilt.box.com/s/xnl7oxyhtha1d968bnnzfb6liwm1nkso" type="video/mp4">
  Your browser does not support the video tag.
</video>

## Limitations

Please be aware of the following limitations:

- The back cover may have difficulty providing stable tracking due to a lack of distinguishing features (while creating the targets in Vuforia, the front cover got 5 stars and the back cover only 2). Furthermore, lighting changes can affect tracking reliability in the back cover.
- The project currently uses the deprecated Vuforia Virtual Button, which still functions but may not be supported in future updates.


**3D Models Credit:**
The dragon 3D models used in this project were downloaded from [Sketchfab](https://sketchfab.com/). Credit and thanks to the respective creators for their contributions.

