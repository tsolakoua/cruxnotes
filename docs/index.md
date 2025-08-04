<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Welcome to the Crux Notes</title>
<style>
  body {
    margin: 0;
    font-family: system-ui, sans-serif;
    background-image: url('static/images/climbing.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    background-color: white;
    background-blend-mode: multiply;
    color: black;
    line-height: 1.5;
  }

  body::before {
    content: "";
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    z-index: 0;
    pointer-events: none; /* Allow clicks to pass through */
  }

  .container {
    max-width: 800px;
    margin: 4rem auto;
    padding: 2rem;
    background-color: white;
    border-radius: 12px;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
  }

  /* Hide sidebar on desktop only */
  @media screen and (min-width: 769px) {
    .md-sidebar.md-sidebar--primary {
      display: none !important;
    }
  }

  .get-started-btn {
    display: inline-block;
    margin-top: 2rem;
    padding: 0.75rem 1.5rem;
    font-size: 1.125rem;
    font-weight: bold;
    background: linear-gradient(135deg, #a678b4, #845ec2);
    border: none;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
    text-decoration: none;
    transition: transform 0.2s, box-shadow 0.2s;
  }

  .get-started-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 16px rgba(0, 0, 0, 0.25);
  }

</style>

</head>
<body>
  <div class="container">
    <h1>Welcome to the Crux Notes</h1>

  <h2>What you will find</h2>
  <ul>
    <li><strong>Climbing advice and knowledge</strong> based on books and official resources.</li>
    <li><strong>Blog posts and stories from climbers</strong> who’ve been through their own crux moments.</li>
    <li><strong>Gear reviews</strong> based on personal opinions.</li>
  </ul>

<div style="text-align: center;">
  <a href="https://tsolakoua.github.io/crux-notes/strength/" class="get-started-btn" style="color: white;">Get Started</a>
</div>


  <h2>Join the project</h2>
  <p>
    This website is <a href="https://github.com/tsolakoua/crux-notes.git" target="_blank">open source</a>.
    If you have your own story to share or any feedback, contributions are more than welcome!
  </p>

  </div>
</body>
</html>
