<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Adopt a Kitten</title>
  <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Quicksand', sans-serif;
      margin: 0;
      background: #fffafc;
      color: #333;
    }
    header {
      text-align: center;
      padding: 2rem;
      background-color: #ffe0f0;
      border-bottom: 3px dashed #ffb3cc;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: #d63384;
    }
    header p {
      margin: 0.5rem 0 0;
      font-size: 1.2rem;
    }
    .kittens {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1.5rem;
      padding: 2rem;
    }
    .kitten {
      background: #fff;
      border: 2px solid #ffe0f0;
      border-radius: 1rem;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      text-align: center;
      padding: 1rem;
      max-width: 250px;
    }
    .kitten img {
      width: 100%;
      border-radius: 0.5rem;
    }
    .kitten h2 {
      margin-top: 0.5rem;
      color: #d63384;
    }
    .contact {
      background-color: #ffe0f0;
      padding: 2rem;
      text-align: center;
    }
    .contact form {
      max-width: 400px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    .contact input, .contact textarea {
      padding: 0.75rem;
      border-radius: 0.5rem;
      border: 1px solid #ffb3cc;
      font-size: 1rem;
    }
    .contact button {
      background-color: #d63384;
      color: white;
      border: none;
      padding: 0.75rem;
      border-radius: 0.5rem;
      cursor: pointer;
      font-size: 1rem;
      transition: background-color 0.3s;
    }
    .contact button:hover {
      background-color: #c2185b;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #fff0f5;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>🐾 Adopt a Kitten 🐾</h1>
    <p>Find your purr-fect companion today!</p>
  </header>

  <section class="kittens">
    <div class="kitten">
      <img src="https://placekitten.com/300/200" alt="Milo" />
      <h2>Milo</h2>
    </div>
    <div class="kitten">
      <img src="https://placekitten.com/301/200" alt="Luna" />
      <h2>Luna</h2>
    </div>
    <div class="kitten">
      <img src="https://placekitten.com/302/200" alt="Whiskers" />
      <h2>Whiskers</h2>
    </div>
    <div class="kitten">
      <img src="https://placekitten.com/303/200" alt="Bella" />
      <h2>Bella</h2>
    </div>
    <div class="kitten">
      <img src="https://placekitten.com/304/200" alt="Oliver" />
      <h2>Oliver</h2>
    </div>
  </section>

  <section class="contact">
    <h2>Contact Me</h2>
    <p>If you're interested in adopting one of these sweet kittens, just send me a message!</p>
    <form action="mailto:MFALON339@gmail.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>Made with ❤️ for kitten lovers</p>
  </footer>
</body>
</html>
