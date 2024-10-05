# Website Design with Tailwind CSS

---

## **Objective:**

Design a visually appealing website layout using Tailwind CSS utility classes. Implement essential design techniques such as proper indentation, cursor styles, visibility, gradient backgrounds, form styling, flexbox and grid layouts, and pagination. The objective is to practice Tailwind CSS concepts in a real-world scenario while maintaining clean and responsive design.

---

## **Requirements:**

### **1. Navbar Section**:
   - Apply a **cursor style** to the navbar items that changes to a pointer when hovered using `cursor-pointer`.
   - Align the logo and navbar items using **flexbox** (`flex`, `justify-between`).
   - Ensure each navbar item has a hover effect to change text color (`hover:text-color`).
   - The background should be solid and styled using a background color (`bg-color`).

### **2. Hero Section**:
   - Apply a **linear gradient background** to the hero section using Tailwind’s gradient utilities (`bg-gradient-to-r`, `from-color`, `to-color`).
   - Center the text inside the hero section using **flexbox** (`flex`, `items-center`, `justify-center`).
   - Use large font sizes (`text-4xl`, `text-6xl`) and bold styles (`font-bold`).
   - Include a call-to-action button with hover effects (`hover:bg-color`, `hover:scale-105`).

### **3. Services Section**:
   - Use **grid layout** to create a responsive services section (`grid`, `grid-cols-1`, `md:grid-cols-3`).
   - Apply appropriate margins and paddings for spacing between the service cards (`p-6`, `m-4`).
   - Each card should have a border, shadow, and hover effect (`border`, `shadow`, `hover:shadow-lg`).
   - Ensure proper text alignment, font size, and text color for readability.

### **4. Contact Us Section**:
   - Use **flexbox** to align the image and contact form side by side on medium and large screens (`flex`, `md:flex-row`, `flex-col` for small screens).
   - Style the form inputs and buttons using appropriate Tailwind CSS utilities (`border`, `rounded`, `focus:outline-none`, `hover:bg-color`).
   - The form should include input fields (name, email, message) with suitable padding and margins (`p-4`, `m-2`).

### **5. Footer Section**:
   - Divide the footer into **grid layout** with three columns for About Us, Contact Info, and Social Media (`grid`, `grid-cols-1`, `md:grid-cols-3`).
   - Apply **hover effects** to social media icons (`hover:text-color`, `hover:scale-110`).
   - Ensure the text is well spaced, readable, and appropriately aligned.
   - Social media icons should be clickable, and cursor style should be set to `cursor-pointer`.

### **6. Pagination**:
   - Create a pagination component using **flexbox** (`flex`, `justify-center`, `space-x-2`).
   - Use **hover and focus effects** for pagination buttons (`hover:bg-color`, `focus:outline-none`).
   - Ensure the pagination is responsive and aligns properly on different screen sizes.

### **7. Visibility and Hidden Content**:
   - Use the **visibility** utility (`hidden`, `visible`) to create a section of content that can be toggled on and off using JavaScript.
   - Ensure the section is hidden initially (`hidden`) and visible when a button is clicked (`visible`).
   - Use `pointer-events-none` and `pointer-events-auto` for controlling click events on hidden sections.

---

## **Submission:**

1. A single **HTML file** named `index.html` that contains the code for your Tailwind CSS project.
2. A **CSS file** named `styles.css` where you will add any necessary custom Tailwind CSS classes and styles.

---

## **Conclusion:**
This assignment will help you practice and apply various **Tailwind CSS** utilities such as cursor styles, visibility, gradient backgrounds, forms, flexbox, grid layouts, and pagination. The submission will contain the HTML file with all sections properly styled and responsive, demonstrating a deep understanding of Tailwind CSS concepts.