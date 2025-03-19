# html-interview-questions
html-interview-questions for larners and earners.
1. What is HTML?
Answer: HTML (HyperText Markup Language) is the standard language used for creating web pages, defining the structure and content of websites.

Real-time Example:
Every web page you see online is built using HTML, such as your company's homepage.

2. Explain semantic HTML.
Answer: Semantic HTML uses meaningful tags that clearly define their content and purpose, improving SEO and accessibility.

Real-time Example:

html
Copy
Edit
<header>
  <h1>Amazon</h1>
</header>
<main>
  <article>
    <h2>Product Reviews</h2>
  </article>
</main>
<footer>
  <p>Contact us</p>
</footer>
3. Difference between <div> and <span> tags?
Answer:

<div> is a block-level element used for grouping larger content sections.
<span> is an inline element used for smaller, inline portions of text or styling.
Example:

html
Copy
Edit
<div class="card">
  <span class="highlight">Only $10!</span>
</div>
HTML Elements and Attributes
4. What's the difference between HTML elements and tags?
Answer: Tags (<p>) define the beginning and end of elements. An element includes tags and the content between them.

Example:
<p>Hello World</p>

Tags: <p> and </p>
Element: Entire line above.
5. How do you insert images in HTML?
Answer: Use the <img> tag with the src attribute specifying the image path.

Example:

html
Copy
Edit
<img src="logo.png" alt="Company Logo" />
Forms
6. How do you create an HTML form?
Answer: Using the <form> tag, input fields (<input>), labels (<label>), and buttons.

Example:

html
Copy
Edit
<form action="/submit" method="post">
  <label>Name:</label>
  <input type="text" name="username" />
  <button type="submit">Submit</button>
</form>
7. Explain the method attribute in form submission.
Answer: The method specifies how form data is sent (GET or POST).

GET: Data sent via URL (search query).
POST: Data securely sent in request body (login form).
Real-time Example:
Google search uses GET; Bank login uses POST.

HTML5 Features
8. Name some HTML5 semantic tags and their real-time examples.
Answer:

<header>: Site's header/logo.
<nav>: Navigation menu.
<footer>: Footer content.
Real-time Example:

html
Copy
Edit
<header>
  <nav>Home | Products | About Us</nav>
</header>
9. How to embed videos using HTML5?
Answer: Using <video> tag.

Example:

html
Copy
Edit
<video width="320" height="240" controls>
  <source src="video.mp4" type="video/mp4">
</video>
Links and Navigation
10. How do you create hyperlinks in HTML?
Answer: Using the <a> tag with href.

Example:

html
Copy
Edit
<a href="https://www.google.com">Visit Google</a>

