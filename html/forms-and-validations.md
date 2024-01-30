# Forms and Validation

Form validation in HTML is the process of ensuring that user input submitted through HTML forms meets certain criteria or requirements before it is sent to the server for further processing. This helps in preventing erroneous or malicious data from being submitted, improving the overall user experience, and ensuring the integrity of the data collected.

HTML provides basic form validation features, primarily through attributes on form elements and input fields. Here are some common form validation techniques in HTML:

1. **Required Attribute:**
   - The `required` attribute can be added to an input field to make it mandatory. The form cannot be submitted unless the required fields are filled.

   ```html
   <input type="text" name="username" required>
   ```

2. **Pattern Attribute:**
   - The `pattern` attribute allows you to specify a regular expression that the input value must match. This is useful for enforcing specific formats (e.g., email addresses or phone numbers).

   ```html
   <input type="text" name="email" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,}$" required>
   ```

3. **Min and Max Attributes:**
   - For numeric input fields, you can use the `min` and `max` attributes to define a range of acceptable values.

   ```html
   <input type="number" name="age" min="18" max="99" required>
   ```

4. **Length Constraints:**
   - The `minlength` and `maxlength` attributes can be used to define minimum and maximum lengths for text input.

   ```html
   <input type="text" name="password" minlength="8" maxlength="20" required>
   ```

5. **Custom Error Messages:**
   - You can provide custom error messages using the `setCustomValidity` JavaScript method. This allows you to display more user-friendly messages when validation fails.

   ```html
   <input type="text" name="username" pattern="[a-zA-Z0-9]+" required oninvalid="this.setCustomValidity('Please enter a valid username.')">
   ```

6. **Submit Button:**
   - The form's submit button can have the `disabled` attribute initially, and it gets enabled only when the form is valid. This can be achieved using JavaScript in conjunction with the form's `oninput` event.

   ```html
   <input type="submit" value="Submit" id="submitBtn" disabled>
   ```

   ```html
   <script>
   document.querySelector('form').oninput = function() {
       document.getElementById('submitBtn').disabled = !this.checkValidity();
   }
   </script>
   ```

It's important to note that while these HTML attributes can perform basic client-side validation, server-side validation is also crucial to ensure the security and integrity of the submitted data. Client-side validation can be bypassed, so server-side validation acts as a final line of defense.

For more information about form and validation please see: https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation