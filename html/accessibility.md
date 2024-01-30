# Accessibility

Accessibility in HTML refers to designing and developing web pages and applications in a way that makes them usable and understandable by as many people as possible, including those with disabilities. The goal is to ensure that all users, regardless of their abilities or disabilities, can perceive, understand, navigate, and interact with the content effectively.

Here are key aspects of accessibility in HTML:

### 1. **Semantic HTML:**
   - Use semantic HTML elements to provide a clear structure and meaning to the content. Semantically correct tags such as `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<footer>`, etc., enhance the understanding of the page's structure by both users and assistive technologies.

### 2. **Text Alternatives for Images:**
   - Always provide descriptive text alternatives for images using the `alt` attribute in the `<img>` tag. This helps users who rely on screen readers to understand the content of images.

   ```html
   <img src="example.jpg" alt="A description of the image">
   ```

### 3. **Proper Heading Structure:**
   - Use heading tags (`<h1>`, `<h2>`, etc.) in a hierarchical manner to organize content. This helps screen reader users and provides a clear structure for all users.

   ```html
   <h1>Main Heading</h1>
   <h2>Subheading</h2>
   <p>Paragraph text here...</p>
   ```

### 4. **Descriptive Link Text:**
   - Write meaningful link text that describes the purpose or destination of the link. Avoid using generic phrases like "click here" or "read more."

   ```html
   <a href="https://example.com">Visit Example Website</a>
   ```

### 5. **Accessible Forms:**
   - Label form controls properly using the `<label>` element. Provide additional instructions or error messages for form validation. Ensure that form controls are keyboard accessible.

   ```html
   <label for="username">Username:</label>
   <input type="text" id="username" name="username" required>
   ```

### 6. **Keyboard Accessibility:**
   - Ensure that all interactive elements can be accessed and operated using a keyboard. This is crucial for users who cannot use a mouse.

### 7. **Contrast and Color:**
   - Maintain sufficient contrast between text and background colors to make content readable for users with low vision or color blindness.

### 8. **Video and Audio Accessibility:**
   - Provide captions and transcripts for videos. Include subtitles and audio descriptions for users who are deaf or blind.

### 9. **Responsive Design:**
   - Ensure that your website is responsive and works well on various devices, including smartphones and tablets. This benefits users with different abilities and devices.

### 10. **ARIA (Accessible Rich Internet Applications):**
   - Use ARIA attributes to enhance the accessibility of dynamic content and interactive elements. ARIA roles and properties help convey information to assistive technologies.

   ```html
   <div role="button" tabindex="0" onclick="doSomething()">Click me</div>
   ```

### 11. **Testing with Assistive Technologies:**
   - Regularly test your website with screen readers and other assistive technologies to ensure that all users can navigate and interact with your content effectively.

By incorporating these practices, you contribute to creating a more inclusive and accessible web environment, allowing everyone, regardless of their abilities, to access and engage with your content.

For more information about accessiblity in HTML please see: https://developer.mozilla.org/en-US/docs/Web/Accessibility