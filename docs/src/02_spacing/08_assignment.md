# **Utilizing Tailwind CSS Utilities**

## **Objective:**

The objective of this assignment is to provide hands-on experience with some essential Tailwind CSS utilities that are commonly used in web development. You will learn to apply utilities such as container, box-sizing, display, float, object-fit, shadow and opacity, hover and focus effects, and integrating icons using Tailwind. Additionally, you will demonstrate your understanding of Tailwind CSS by creating a visually appealing **navbar** and **hero section** as specified.

---

## **Requirements:**

1. Set up a basic Tailwind CSS project using either the CDN or npm installation.
2. Create an `index.html` file and apply Tailwind classes for the following utilities and features.
3. Each utility and feature must be demonstrated with at least one example in the HTML file.

---

## **Assignment Instructions:**

### **Step 1: Set Up the Project**
- Create a new folder for your project.
- Inside the project folder, create an HTML file named `index.html`.
- Include Tailwind CSS by either using the CDN link or setting up Tailwind using npm.

### **Step 2: Apply Each Utility**

1. **Container Utility**
   - Use Tailwind’s `container` class to create a responsive container that adjusts its width based on the current screen size.
   - Example:
     ```html
     <div class="container mx-auto bg-gray-200 p-4">
       This is a responsive container using Tailwind's container utility.
     </div>
     ```

2. **Box Sizing Utility**
   - Explore the `box-border` and `box-content` utilities to control how the width and height of an element are calculated.
   - Example:
     ```html
     <div class="box-border w-64 h-32 p-4 border-4 bg-blue-100">
       Box border example with Tailwind.
     </div>
     ```

3. **Display Utility**
   - Use the `block`, `inline-block`, `hidden`, and `flex` utilities to control the display properties of elements.
   - Example:
     ```html
     <div class="block bg-red-100 p-2">This is block display</div>
     <div class="inline-block bg-green-100 p-2">This is inline-block display</div>
     ```

4. **Float Utility**
   - Experiment with Tailwind’s `float-left`, `float-right`, and `clear-both` utilities to manage float positioning.
   - Example:
     ```html
     <div class="float-left w-1/2 bg-yellow-200 p-2">Floated Left</div>
     <div class="float-right w-1/2 bg-blue-200 p-2">Floated Right</div>
     ```

5. **Object Fit Utility**
   - Use the `object-contain`, `object-cover`, and `object-fill` utilities to control how media elements (like images) fit within their containers.
   - Example:
     ```html
     <img src="image.jpg" class="object-cover h-48 w-full" alt="Example Image">
     ```

6. **Shadow and Opacity Utilities**
   - Apply shadow effects using Tailwind’s `shadow` utilities and adjust the opacity with `opacity-50`, `opacity-75`, etc.
   - Example:
     ```html
     <div class="shadow-lg bg-white p-6 opacity-75">
       Box with shadow and opacity.
     </div>
     ```

7. **Hover and Focus Effects**
   - Use hover and focus states to add interactivity to buttons or text. Apply `hover:text-blue-500` or `focus:ring-2` for these effects.
   - Example:
     ```html
     <button class="bg-red-500 text-white p-4 hover:bg-red-700 focus:ring-4">Hover and Focus Me</button>
     ```

8. **How to Use Icons in Tailwind CSS**
   - Use popular icon libraries like Font Awesome or Heroicons and integrate icons into your design.
   - Example using Font Awesome:
     ```html
     <i class="fas fa-home text-2xl text-blue-500"></i> Home
     ```

---

### **Step 3: Navbar and Hero Section Design**

1. **Navbar Section**
   - The navbar should have a gray background (`bg-gray-700`).
   - Navbar items should be aligned to the right side.
   - Each navbar item must have:
     - A white background (`bg-white`),
     - Rounded corners (`rounded-lg`),
     - A shadow effect (`shadow`).
   - Add a smooth transition effect on hover and focus (`transition-colors duration-300`).

2. **Hero Section**
   - The hero section should have a margin-top of 70 pixels (`mt-[70]`).
   - The background color should be gray (`bg-gray-700`).
   - Inside the hero section:
     - Add a centered image of 64x64 pixels (`h-64 w-64`),
     - Ensure the image has rounded corners (`rounded-full`),
     - Apply a shadow effect (`shadow`).
   - Include a heading with:
     - A font size of 4xl (`text-4xl`),
     - Bold style (`font-bold`),
     - A margin-bottom of 4 (`mb-4`).
   - Add a paragraph with a font size of xl (`text-xl`).

---

### **Step 4: Submission Requirements**
1. Create a single HTML file named `index.html` where each utility and the navbar/hero section are demonstrated clearly with examples.
2. Ensure that each section is properly commented in the HTML file for clarity.

---

### **Evaluation Criteria**
You will be evaluated based on the following:
- Correct usage of each utility.
- Clear demonstration of each utility with distinct sections in the HTML file.
- Visual appeal and readability of the layout created using Tailwind’s utilities.
- Proper styling and implementation of the navbar and hero section.

---

### **Conclusion:**
By completing this assignment, you will gain a practical understanding of several key utilities in Tailwind CSS, along with hands-on experience in creating a functional and visually appealing navbar and hero section. These utilities and components will form the foundation for building more complex layouts and responsive designs in your future projects.
