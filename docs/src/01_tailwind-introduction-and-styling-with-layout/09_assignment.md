# Styling and Layout Using Tailwind CSS

Learning a new technology is most effective when paired with hands-on practice. In this chapter, we present an **assignment** designed to familiarize you with the essential features of **Tailwind CSS**. By the end of this assignment, you will have built a small project that utilizes various Tailwind CSS utilities for styling text and layout. This practical task will help reinforce your understanding of key concepts, including **text color**, **background color**, **font size**, **font weight**, **text alignment**, and more.

---

## 1. Objective

The primary objective of this assignment is to provide you with **practical experience** in setting up and working with Tailwind CSS. You will:
- Set up a basic Tailwind CSS project.
- Use Tailwind’s utility classes to style elements in an HTML file.
- Explore a variety of properties, including font sizes, text colors, background colors, and hover effects.

Upon completion, you will have hands-on experience with Tailwind CSS’s capabilities and be better prepared for larger projects.

---

## 2. Requirements

To complete this assignment, ensure that you meet the following requirements:

1. **Set up the project** and have access to a code editor or Integrated Development Environment (IDE) of your choice. Popular editors include **Visual Studio Code**, **Sublime Text**, or **Atom**.
   
2. Have a basic understanding of **HTML** and **CSS**. This knowledge is essential for creating the structure of your project and applying Tailwind classes effectively.

3. **Internet connectivity**: You will need an internet connection to download necessary resources, including Tailwind CSS, through either CDN or npm.

4. Explore the following Tailwind utilities:
   - **Text Color**: Apply different colors to your text elements.
   - **Background Color**: Add background colors to various sections.
   - **Font Weight**: Adjust the weight of text (bold, normal, light).
   - **Font Size**: Control the size of your text for headings, paragraphs, and other text elements.
   - **Text Alignment**: Align text to the left, right, center, or justify it.

---

## 3. Assignment Instructions

### Step 1: Set Up the Project
- Initialize a new project folder.
- Inside the project folder, create an HTML file named `index.html`.
- Create a CSS file named `styles.css`, where you will add your custom Tailwind classes and custom styles.
- Link the `styles.css` file to your `index.html` file to ensure your Tailwind utilities apply correctly.

### Step 2: Include Tailwind CSS
- To include Tailwind CSS, you can either use the **CDN link** in the HTML file or **install Tailwind using npm** for more control.
  - **CDN Setup**: If you’re using the CDN approach, add the following `<link>` tag in the `<head>` section of your HTML:
    ```html
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.0.0/dist/tailwind.min.css" rel="stylesheet">
    ```

  - **npm Setup**: Alternatively, follow the steps to install Tailwind via npm, as discussed in previous chapters.

### Step 3: Structure the HTML
- Use your HTML file to create the structure of your project. Include at least the following elements:
  - A **header** with a title using a large font size.
  - A **section** with some text content demonstrating different text colors, font weights, and background colors.
  - A **button** with hover effects, showcasing interactive elements.
  - Ensure all text elements have appropriate alignment.

### Step 4: Apply Tailwind Classes
- In your `index.html` file, apply various Tailwind utility classes for styling. Your goal is to explore and demonstrate the use of different Tailwind features, including:
  - **Text Color**: Use different text color utilities such as `text-red-500`, `text-blue-600`, etc.
  - **Background Color**: Apply background colors using `bg-green-200`, `bg-gray-300`, etc.
  - **Font Size**: Set different font sizes using `text-xl`, `text-2xl`, etc.
  - **Font Weight**: Control font weight using `font-bold`, `font-light`, `font-semibold`, etc.
  - **Text Alignment**: Use alignment utilities like `text-left`, `text-center`, `text-right`, and `text-justify`.
  
### Example of Basic HTML Structure:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="styles.css" rel="stylesheet">
    <title>Tailwind CSS Assignment</title>
</head>
<body class="bg-gray-100 p-6">
    <header>
        <h1 class="text-3xl font-bold text-center text-blue-500">Welcome to My Tailwind Project</h1>
    </header>
    
    <section class="mt-8 bg-white p-6 shadow-lg">
        <p class="text-gray-700 text-lg">
            This is a paragraph using Tailwind CSS. The text is styled with <span class="text-green-500 font-bold">green</span> and <span class="font-semibold">semi-bold</span> weight.
        </p>
    </section>
    
    <button class="mt-6 bg-red-500 text-white font-semibold p-4 hover:bg-red-700">
        Hover over me!
    </button>
</body>
</html>
```

---

## 4. Submission Requirements

When completing the assignment, ensure you submit the following files:

1. A single **HTML file** named `index.html`, which contains the structure and Tailwind CSS classes applied to different elements.
   
2. A **CSS file** named `styles.css` where you will add the necessary Tailwind CSS classes and custom styles (if any).

---

## 5. Evaluation Criteria

You will be evaluated based on how well you apply the following Tailwind CSS utilities:
- **Text Color**: Different text color variations are used effectively.
- **Background Color**: Appropriate background colors are applied to sections, demonstrating contrast and design balance.
- **Font Weight & Font Size**: Different weights and sizes are applied to text elements, showcasing visual hierarchy.
- **Text Alignment**: Text is properly aligned and organized within the layout.
- **Hover Effects**: Buttons or interactive elements have hover states applied, demonstrating interactivity.

---

## 6. Conclusion

This assignment will give you practical experience in setting up and working with Tailwind CSS. By completing it, you will become more familiar with the framework’s utility-first approach and learn how to apply its powerful styling options. These skills will be invaluable as you build more complex projects in the future.
