

# **Assignment: Web API Integration and Dark Mode Implementation with Tailwind CSS**

---

# **Objective:**

The goal of this assignment is to build a responsive web page that integrates with a third-party **Web API** to display dynamic content and implement a **dark mode** toggle feature. You will also explore advanced **Tailwind CSS** features, such as theming, dark mode, and custom plugins, to enhance the user experience.

---

# **Requirements:**

In this assignment, you will focus on achieving the following two key tasks:

1. **Integration of a Web API**:
   - You will use the **Rick and Morty API** to dynamically fetch and display a list of characters from the show.
   - API URL: `https://rickandmortyapi.com/api/character`.
   - Display details such as the character's name, image, species, and status (alive, dead, or unknown).

2. **Implementing Dark Mode**:
   - Add a **dark mode toggle** feature, allowing users to switch between light and dark themes using Tailwind’s built-in **dark mode utilities**.
   - The dark mode should be toggled by a button and should persist when the user revisits the page (using localStorage).

3. **Custom Tailwind CSS Configuration**:
   - Customize your **Tailwind configuration** (`tailwind.config.js`) to extend colors, dark mode, and add any necessary **Tailwind plugins**.

4. **Responsive Design**:
   - Ensure the web page is **fully responsive** across mobile, tablet, and desktop devices.

---

# **Detailed Instructions:**

1. **Tailwind CSS Setup**:
   - Include Tailwind CSS in your project either by using a **CDN** or setting it up via **npm**.
   - Extend your **tailwind.config.js** to add custom themes and enable dark mode features.

2. **Building the Layout**:
   - Create a clean and responsive layout to display the list of characters from the **Rick and Morty API**.
   - Utilize **Tailwind CSS utility classes** to design a visually appealing layout with proper spacing, borders, and a responsive grid.
   - Implement a **grid** or **flexbox layout** for the dynamic character cards.

3. **Web API Integration**:
   - Fetch data from the **Rick and Morty API** using **JavaScript** (`fetch()` or **Axios**).
   - Dynamically generate and display character details (name, image, species, status) in cards.
   - Ensure the layout is responsive and adjusts appropriately based on screen size.

4. **Dark Mode Toggle**:
   - Add a **dark mode toggle button** in the navigation bar.
   - Use Tailwind’s **dark mode utilities** to switch between themes (e.g., `dark:bg-gray-900`).
   - Save the dark mode preference in **localStorage** so that the user’s theme persists between page visits.

5. **Custom Tailwind CSS Plugins**:
   - Add and configure Tailwind CSS plugins such as `@tailwindcss/typography` or `@tailwindcss/forms` to enhance form elements or typography.
   - Customize **color schemes**, **padding**, or **borders** by extending the Tailwind CSS configuration.

---

# **Bonus Tasks (Optional):**

- **Pagination**: Add pagination to load more characters from the Rick and Morty API (the API allows for paginated data).
- **Search Functionality**: Implement a search feature to filter characters by name or species.

---

# **Submission Requirements:**

1. **HTML File**:
   - Submit a single HTML file named `index.html` containing your Tailwind CSS project. It should include API integration and the dark mode toggle feature.

2. **CSS File**:
   - Submit a CSS file named `styles.css` where you include custom styles or overrides for your project, and apply Tailwind CSS utilities.

3. **JavaScript File**:
   - Include a JavaScript file named `app.js` to handle API requests, the dark mode toggle, and any other JavaScript logic (such as pagination or search).

---

# **Evaluation Criteria:**

- **API Integration**: Successfully fetch and display data from the **Rick and Morty API**.
- **Dark Mode**: The dark mode toggle works correctly and persists between page reloads.
- **Tailwind CSS Customization**: Correct use of Tailwind’s **theming**, **dark mode**, and **plugins**.
- **Responsive Design**: The web page is fully responsive, providing an optimal experience on mobile, tablet, and desktop devices.
- **Visual Appeal**: The design is clean, modern, and visually consistent across both light and dark themes.

---

# **Conclusion:**

By completing this assignment, you will gain experience with practical **API integration**, **responsive design**, and **dark mode implementation**. You will also learn how to configure **Tailwind CSS** to create custom themes and use **plugins** to extend functionality.
