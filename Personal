<section>
  <h2>Contact Me Directly</h2>
  <p>
    <a href="https://wa.me/2348137958112" target="_blank">Chat on WhatsApp</a> |
    <a href="mailto:victorifeanyichukwu456@gmail.com">Send an Email</a> |
    <a href="tel:+2348137958112">Call Me</a>
  </p>
</section>
DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Victor Ifeanyichukwu - Contact</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      background-color: #1f3b57;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    header p {
      margin: 0.5rem 0 0;
      font-size: 1.1rem;
    }

    main {
      max-width: 800px;
      margin: 2rem auto;
      padding: 1rem;
    }

    section {
      margin-bottom: 2rem;
    }

    h2 {
      color: #1f3b57;
      margin-bottom: 0.5rem;
    }

    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 0.75rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    .contact-form button {
      background-color: #1f3b57;
      color: white;
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: 4px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .contact-form button:hover {
      background-color: #163047;
    }

    .success-message {
      display: none;
      color: green;
      font-style: italic;
      margin-top: 1rem;
    }

    footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #777;
    }

    .social-links {
      margin: 1rem 0;
    }

    .social-links a {
      margin: 0 10px;
      text-decoration: none;
      color: #1f3b57;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    .social-links a:hover {
      color: #0d1c2b;
    }
  </style>
</head>
<body>

  <header>
    <h1>Victor Ifeanyichukwu</h1>
    <p>Get in touch with me</p>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>Hello! I'm Victor Ifeanyichukwu, a passionate and dedicated individual focused on growth, communication, and making meaningful connections. I believe in professionalism, clarity, and staying organized in everything I do. Feel free to reach out through the form below.</p>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <form class="contact-form" method="POST" action="https://formspree.io/f/xkgbbwze">
        <label for="name">Your Name</label>
        <input type="text" id="name" name="name" required />

        <label for="email">Your Email</label>
        <input type="email" id="email" name="email" required />

        <label for="message">Message</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit">Send Message</button>
        <p class="success-message" id="success-message">Thank you! Your message has been sent.</p>
      </form>
    </section>
  </main>

  <footer>
    <div class="social-links">
      <a href="#" target="_blank">LinkedIn</a>
      <a href="#" target="_blank">Twitter</a>
      <a href="#" target="_blank">GitHub</a>
      <a href="#" target="_blank">Instagram</a>
    </div>
    &copy; 2025 Victor Ifeanyichukwu. All rights reserved.
  </footer>

  <script>
    // Optional: handle success message without leaving page
    const form = document.querySelector('.contact-form');
    const successMessage = document.getElementById('success-message');

    form.addEventListener('submit', async (e) => {
      e.preventDefault();
      const formData = new FormData(form);

      try {
        const response = await fetch(form.action, {
          method: form.method,
          body: formData,
          headers: {
            'Accept': 'application/json'
          }
        });

        if (response.ok) {
          form.reset();
          successMessage.style.display = 'block';
        } else {
          alert('Something went wrong. Please try again.');
        }
      } catch (error) {
        alert('Error submitting form. Please try again later.');
      }
    });
  </script>

</body>
</html>
