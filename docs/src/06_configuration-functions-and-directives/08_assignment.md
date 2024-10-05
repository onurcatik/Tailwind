# Advanced Tailwind CSS Configuration, Functions, and Directives

---

## **Objective:**

This assignment focuses on advanced topics in **Tailwind CSS** configuration, including **theming and dark mode**, **customizing the Tailwind CSS configuration**, **plugins**, and **functions and directives**. You will practice applying these advanced configuration techniques to enhance your understanding of Tailwind's capabilities in real-world projects.

---

## **Assignment Structure:**

### **1. Theming and Dark Mode:**
   - Implement a **dark mode** in your project by customizing Tailwind’s configuration.
   - Create **light** and **dark** themes for your website, ensuring that the transition between themes is smooth.
   - Use the Tailwind **dark variant** (`dark:`) to customize elements for dark mode.
   
   **Requirements**:
   - Enable **dark mode** using Tailwind’s configuration (`darkMode: 'media'` or `darkMode: 'class'`).
   - Apply different background and text colors for light and dark themes (`bg-gray-900`, `text-white` for dark mode, and `bg-white`, `text-gray-900` for light mode).
   - Add a button to **toggle** between light and dark modes using JavaScript (`darkMode: 'class'` setup).

---

### **2. Customizing Tailwind CSS Configuration:**
   - Customize the **Tailwind configuration file** (`tailwind.config.js`) to add custom colors, fonts, spacing, and breakpoints.
   - Extend the default Tailwind configuration by adding **custom utility classes**.
   
   **Requirements**:
   - Modify the `tailwind.config.js` file to add custom color schemes and font families.
   - Add **new spacing utilities** to the configuration, such as `spacing: { '72': '18rem', '84': '21rem', '96': '24rem' }`.
   - Include custom **breakpoints** for responsive design (e.g., `xl: '1440px'`).

---

### **3. Tailwind CSS Plugins:**
   - Integrate **Tailwind CSS plugins** into your project to extend functionality.
   - Use a plugin such as `@tailwindcss/forms`, `@tailwindcss/aspect-ratio`, or `@tailwindcss/typography` to style forms, images, or content blocks.
   
   **Requirements**:
   - Install a Tailwind CSS plugin using npm (e.g., `@tailwindcss/forms`).
   - Configure the plugin in the `tailwind.config.js` file.
   - Apply the plugin’s utilities in your HTML or CSS files to style specific sections, such as forms or typography blocks.

---

### **4. Popular Tailwind CSS Plugins:**
   - Research and integrate a **popular Tailwind CSS plugin** into your project, such as **Tailwind UI**, **Flowbite**, or **DaisyUI**.
   - Customize the plugin’s components to match your project’s theme and style.
   
   **Requirements**:
   - Install a popular Tailwind plugin like **DaisyUI** or **Flowbite**.
   - Use the plugin’s prebuilt components, such as buttons, modals, or cards, in your project.
   - Customize the components by overriding Tailwind’s default styles.

---

### **5. Functions and Directives:**
   - Use Tailwind's built-in **functions and directives** to create dynamic styles in your project.
   - Implement the `@apply` directive to reuse Tailwind’s utility classes and reduce code duplication.
   
   **Requirements**:
   - Use the `@apply` directive to group common utility classes in a custom CSS file.
   - Apply **Tailwind CSS functions** (like `theme()`, `colors()`, and `spacing()`) in your configuration file to manage your design tokens efficiently.

---

### **6. Optimizing Production:**
   - Learn how to optimize your project for production by **removing unused CSS** with Tailwind’s `purge` option.
   - Configure the `purge` property in `tailwind.config.js` to remove unused styles in production, keeping your CSS file size small.
   
   **Requirements**:
   - Set up **purge** in your `tailwind.config.js` file to remove unused CSS.
   - Ensure the project is optimized by only including CSS used in the final production build.

---

## **Submission Requirements:**

1. A single **HTML file** named `index.html` that demonstrates the use of dark mode, custom configurations, plugins, and Tailwind directives.
2. A **Tailwind configuration file** (`tailwind.config.js`) that includes all the customizations mentioned above (e.g., custom themes, spacing, colors, plugins).
3. A **CSS file** that includes any custom styles or utility classes created using the `@apply` directive.

---

## **Grading Criteria:**

1. **Theming and Dark Mode**:
   - Proper implementation of dark mode.
   - Smooth transition between light and dark themes.

2. **Customization of Tailwind CSS Configuration**:
   - Successfully extended the default configuration with custom colors, fonts, and utilities.

3. **Plugins**:
   - Correct integration of plugins and use of their utilities in the project.

4. **Functions and Directives**:
   - Efficient use of `@apply` to create reusable classes.
   - Proper usage of Tailwind CSS functions to manage design tokens.

5. **Production Optimization**:
   - Correct setup of Tailwind’s `purge` option to minimize the CSS file size.
