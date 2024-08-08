
# Advanced Flexbox and Grid

## FlexGrid Pet Emporium
![Screenshot of the project](assets/images/example.jpg)

## Description
In this assignment, with step-by-step assistance from AI, you will utilize Flexbox and CSS Grid to create a responsive pet store webpage. "FlexGrid's Pet Emporium". Now let's get started.

## Project Structure

```
FlexGridsPetEmporium
│   index.html
│   styles.css
└───assets
    └───images
```

## Setup Steps

1. **Create the Project Folder:**
   - Create a main project folder named `FlexGridsPetEmporium`.

2. **Create HTML and CSS Files:**
   - Create a new HTML file named `index.html`.
   - Create a new CSS file named `styles.css`.

3. **Inside the Project Folder:**
   - Create a folder named `assets`.
   - Create another folder named `images` inside the assets folder.

4. **Download Pet Photos:**
   - Go to [Pexels.com](https://www.pexels.com) and download 12 pet photos of your choice.

5. **Rename the Photos:**
   - Rename the downloaded photos to shorter names for easier reference, such as `Pet1.jpg`, `Pet2.jpg`, ..., `Pet12.jpg`.

6. **Place the Photos in the images Folder:**
   - Move the downloaded (and renamed) pet photos into the `images` folder inside the `assets` folder.

7. **Download Background Image:**
   - Go to [Pexels.com](https://www.pexels.com) and search for light background images.
   - Find something that you think will work with your Pet Store site and download it.
   - Rename this image to `Background.jpg` and also place it in the `assets/images` folder.

## Coding Steps with AI Assistance

Now let's start coding with the help of AI.

### Let's start with the index.html steps

#### Steps to ask AI

1. **Add HTML Boilerplate with Web Page Title and Footer**
   - **What to ask AI:**
     Can you provide me with a detailed HTML boilerplate for a web page with a header, main content area, and footer, along with a linked CSS file, and title the page 'FlexGrids Pet Emporium'. Include an h1 tag in the header and a p tag in the main content area with a witty description for a pet store. This "witty description" should be a p tag with a class of "store-description".
   - **Where to place the provided code:**
     Copy the HTML boilerplate code provided by the AI and paste it into your `index.html` file.

2. **Add Navigation Bar Code**
   - **What to ask AI:**
     Can you provide me with HTML code to add a navigation bar with "Login," "Our Locations," and "Contact Us" options to my existing HTML boilerplate? The nav bar will be a black bar at the top once I style it.
   - **Where to place the provided code:**
     - Open your `index.html` file.
     - Locate the `<header>` tag in your `index.html` file. The `<header>` tag should be inside the `<body>` tags.
     - Paste the copied navigation bar code between the `<body>` and the `<header>` tags.

3. **Add Pet Image Boxes Section**
   - **What to ask AI:**
      Now that we have a navigation bar, let's add 12 boxes for the pet photos with cute pet names and short personality descriptions. Can you provide me with HTML code to add a section under the main content area with 12 image boxes for pet photos located in the assets/images folder? The photos are named Pet1.jpg to Pet12.jpg. Each box should have an image, a cute pet name, and a short personality description underneath. Please ensure this code uses a `<section>` tag with a class of "pet-gallery".  
   - **Where to place the provided code:**
     - Open your `index.html` file.
     - Locate the existing `<main>` tag in your `index.html` file. This tag should already contain the initial `<p>` tag with the business description.
     - Paste all the copied pet image boxes `<section>` code directly below the existing `<p>` tag inside the `<main>`. This will ensure that the pet image boxes section appears right after the business description.

4. **Add a Section for Location and Hours**
   - **What to ask AI:**
     Next, let's add a section for the location and hours. Can you provide me with HTML code to add a section for location and hours, including an address, phone number, and business hours? 
   - **Where to place the provided code:**
     - Open your `index.html` file.
     - Locate the existing `<footer>` tag in your `index.html` file.
     - Paste the copied location and hours section code directly above the `<footer>` tag.

5. **Now test your `index.html` file in the browser. You should see the skeleton of a web page coming together.**
<img src="assets/images/example2.png" alt="Small Image" width="300" height="300">
Next, we can add some styling.

### Let's add some CSS code to our `styles.css` file

#### Steps to ask AI

1. **Add Basic Styles**
   - **What to ask AI:**
     Can you provide me with CSS code to set some basic styles, such as margin, padding, and box-sizing for all elements, and set a font for the body?
   - **Where to place the provided code:**
     Copy the CSS code provided by the AI and paste it in your `styles.css` file.

2. **Style the Header and Navigation Bar**
   - **What to ask AI:**
     Can you provide me with CSS code to style the header and navigation bar, making the nav bar a black bar at the top of the page with white text? Here is the `html` code to use for reference for styling.
     **(copy and paste the nav bar code from your html file to include with the AI ask `<nav>` to `</nav>`)**
   - **Where to place the provided code:**
     Copy the CSS code provided by the AI and paste it nexr of in `styles.css` file.
  
3. **Style the Navigation Bar**
   - **What to ask AI:**
     Can you provide me with CSS code to style the navigation bar? The navigation bar should be full-width with a black background. Use Flexbox to handle the layout and ensure the text is centered within the navigation bar. Use my navigation html code supplied here for reference when building the CSS please. 
     *(Now copy and paste all the nav bar code  `<nav>` all your code `</nav>` from your `index.html` into the current AI request so it can be used by AI for reference when building out the CSS)*
   - **Where to place the provided code:**
     - Open your `styles.css` file and paste the supplied CSS code for the navigation bar next in the `styles.css` file.
   
