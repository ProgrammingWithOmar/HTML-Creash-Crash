# Chapter 3: HTML Attributes

  HTML attributes provide additional information about HTML elements. They are key-value pairs that modify an  element's behavior, appearance, or provide other relevant information. Attributes are specified within the opening tag of an element and can be used to customize and control elements in various ways. Let's explore  some essential attributes and how they can be used:


  ## 1. id Attribute:

- The id attribute is used to uniquely identify an HTML element on a web page. It provides a way to reference and target the element for styling or scripting purposes. IDs must be unique within the entire document

   Example:

   ```html
    <p id="intro">This is the introduction paragraph.</p>
   ```

   ## 2. Class Attribute:

    - he class attribute is used to assign one or more class names to an HTML element. It allows you to apply the same styles or behavior to multiple elements. Unlike IDs, classes can be used on multiple elements within a document

   

     Example:
   

   ```html
     <p class="highlight">This is a paragraph with a highlighted class.</p>
     <p class="highlight">This is another paragraph with the same highlighted class.</p>
    ```

    In this example, both paragraphs share the class "highlight," allowing you to apply specific styling or behavior to all elements with that class.🧑🏾‍💻🧑🏾‍💻


    ## 3. Src Attribute:

    - The src attribute is used with certain elements to specify the source (URL) of external content, such as images, audio, video, iframes, and more.

   
     Example:

     ```html
     <img src="image.jpg" alt="A beautiful image">
    ```

    in this example, the src attribute specifies the URL of the image file to be displayed



   ## 4. href Attribute:
    
     - The href attribute is used with the anchor ```<a>``` element to specify the destination URL that the link should navigate to when clicked.

    
    Example:

    ```html

    <a href="https://www.example.com">Visit Example Website</a>
   ```

   In this example, the href attribute specifies the destination URL for the link.

   By using attributes like id, class, src, and href, you can customize and control the behavior and appearance of HTML elements on your web page. Additionally, JavaScript can use these attributes to interact with and manipulate elements dynamically at runtime. Properly using attributes is crucial for creating well-structured and maintainable HTML code while providing additional information and functionality to your web page's elemen


   ## 5. alt Attribute:

     - The alt attribute is used with the ```<img>``` element to provide alternative text for images. It is displayed if the image cannot be loaded or for accessibility purposes (e.g., screen readers).

    Example:

    ```html
    <img src="image.jpg" alt="A beautiful sunset">
    ```