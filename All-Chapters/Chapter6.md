# Chapter 6: Links and Navigation


1. **Simple Links:**
   The most common way to create a link is by using the `<a>` (anchor) element. This element defines a hyperlink and allows you to link to other web pages or resources. The `href` attribute specifies the URL of the destination.

   ```html
   <a href="https://www.example.com">Visit Example Website</a>
   ```

   When a user clicks on "Visit Example Website," the browser will navigate to "https://www.example.com."

2. **Internal Links (Anchor Links):**
   To create internal links within the same page or to specific sections of the page, use the `<a>` element with the `href` attribute set to an anchor name preceded by a hash symbol (`#`).

   ```html
   <a href="#section2">Jump to Section 2</a>
   ```

   In this example, the link will navigate to the element with the ID "section2" on the same page.

3. **Relative Links:**
   Instead of specifying the full URL, you can use relative URLs for internal navigation. Relative URLs are URLs that are relative to the current page's URL.

   ```html
   <a href="page2.html">Go to Page 2</a>
   ```

   If the current page is "https://www.example.com/page1.html," clicking the link will navigate to "https://www.example.com/page2.html."

4. **Linking to Email Addresses:**
   You can use the `mailto:` scheme to create links that open the user's default email client to compose a new email.

   ```html
   <a href="mailto:info@example.com">Send Email</a>
   ```

   When a user clicks on "Send Email," it will open their email client with the recipient email address pre-filled.

5. **Linking to Files:**
   You can use links to provide downloadable files, such as PDFs, images, or documents.

   ```html
   <a href="files/document.pdf" download>Download PDF</a>
   ```

   The `download` attribute prompts the user to download the linked file instead of navigating to it.

6. **Navigation Menus:**
   Navigation menus are typically created using lists (`<ul>` and `<li>`). Each list item contains a link to the desired page or section.

   ```html
   <ul>
     <li><a href="home.html">Home</a></li>
     <li><a href="about.html">About</a></li>
     <li><a href="contact.html">Contact</a></li>
   </ul>
   ```

   The above example creates a simple horizontal navigation menu with links to the "Home," "About," and "Contact" pages.

