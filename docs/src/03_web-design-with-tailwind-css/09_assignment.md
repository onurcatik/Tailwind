# Tailwind CSS Web Design Assignment

Hands-on practice is one of the most effective ways to solidify your understanding of any technology, including Tailwind CSS. In this chapter, we present an assignment aimed at reinforcing the concepts you’ve learned so far about Tailwind CSS. This exercise will guide you through the practical application of margin, padding, text decoration, text transformation, width, height, borders, and custom margin utilities in Tailwind CSS.

---

## Objective

The goal of this assignment is to help you gain **practical experience** with Tailwind CSS by using its core utility classes to style various elements. By completing this assignment, you will improve your proficiency in Tailwind CSS and learn how to apply different styles for:
- **Spacing** (margin and padding)
- **Text decoration** (underline, line-through)
- **Text transformation** (uppercase, lowercase)
- **Element sizing** (width and height)
- **Borders** (width, color, and style)
- **Custom margins**

This exercise will help you better understand how to use Tailwind's utility-first approach in real-world projects.

---

## Requirements

The following requirements break down the tasks you will need to complete for this assignment. Each section corresponds to a specific Tailwind CSS utility, helping you build a comprehensive layout.

---

## 1. Margin and Padding

- Use the **m-[size]** utility class to add margin to an element.
  - Example: `m-4`, `m-auto`, `mt-6`
- Use the **p-[size]** utility class to add padding to an element.
  - Example: `p-6`, `pt-8`
- Experiment with different margin and padding sizes to create a well-structured layout.

### Example Code:
```html
<div class="m-6 p-8 bg-gray-100">
  This div has custom margin and padding.
</div>
```

---

## 2. Text Decoration

- Use the **underline** utility class to add an underline to text.
- Use the **line-through** utility class to apply a line-through (strikethrough) effect to text.
- Apply these text decoration classes to different text elements, such as headings, paragraphs, or links.

### Example Code:
```html
<p class="underline">This text has an underline.</p>
<p class="line-through">This text has a line-through.</p>
```

---

## 3. Text Transformation

- Use the **uppercase** utility class to transform text to uppercase.
- Use the **lowercase** utility class to transform text to lowercase.
- Experiment by applying these transformations to various elements like headings and buttons.

### Example Code:
```html
<h1 class="uppercase">This heading is in uppercase.</h1>
<p class="lowercase">this text is in lowercase.</p>
```

---

## 4. Width and Height

- Use the **w-[size]** utility class to set the width of an element.
  - Example: `w-64`, `w-full`, `w-1/2`
- Use the **h-[size]** utility class to set the height of an element.
  - Example: `h-32`, `h-screen`, `h-full`
- Experiment with different width and height sizes to control element dimensions.

### Example Code:
```html
<div class="w-64 h-32 bg-blue-500">
  This div has a width of 16rem and a height of 8rem.
</div>
```

---

## 5. Border with Custom Color

- Use the **border** utility class to add a border to an element.
- Use the **border-[color]** utility class to set a custom border color.
  - Example: `border-red-500`, `border-2`, `border-dashed`
- Experiment by applying borders to various elements, such as buttons, cards, or containers.

### Example Code:
```html
<div class="border-4 border-green-500 p-4">
  This div has a 4px green border.
</div>
```

---

## 6. Custom Margin

- Use the **mt-[size]** utility class to add margin-top to an element.
- Use the **ml-[size]** utility class to add margin-left to an element.
- Combine custom margin classes with other utilities like padding to create precise spacing between elements.

### Example Code:
```html
<div class="mt-10 ml-6 p-4 bg-yellow-200">
  This div has custom top and left margins.
</div>
```

---

## Submission

To complete the assignment, you need to submit the following files:

1. **HTML file**:
   - A single HTML file named `index.html` containing the Tailwind CSS utilities applied to various elements.
   - Include the margin, padding, text decoration, text transformation, width, height, and border utilities.

2. **CSS file**:
   - A CSS file named `styles.css`, where you will extend Tailwind's default configuration if necessary and add any custom utilities or styles.

### Example Project Structure:
```
- index.html
- styles.css
```

---

## Conclusion

This assignment provides you with the opportunity to put your knowledge of Tailwind CSS into practice. By completing the tasks and experimenting with different utilities, you will gain a deeper understanding of how to use Tailwind's utility classes for layout and styling purposes. Once you’ve completed this project, you’ll be equipped with the skills to apply Tailwind CSS efficiently in larger, more complex projects.
