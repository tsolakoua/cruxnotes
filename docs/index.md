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
      background-color: #d6d1de;
      background-blend-mode: multiply;
      color: #333;
      line-height: 1.6;
    }

    body::before {
      content: "";
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      background-color: rgba(152, 119, 171, 0.3); /* Deep purple overlay */
      z-index: -1;
    }

    .container {
      max-width: 800px;
      margin: 4rem auto;
      padding: 2rem;
      background-color: rgba(255, 255, 255, 1);
      border-radius: 12px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
    }


    /* Optional: Hide navigation if using within MkDocs template */
    .md-nav__list {
      display: none !important;
    }

    .md-sidebar.md-sidebar--primary {
        display: none !important;
    }

   </style>
</head>
<body>
  <div class="container">
    <h1>Welcome to the Crux Notes</h1>
    <blockquote>Knowledge and stories for climbers by climbers.</blockquote>

    <h2>What you will find</h2>
    <ul>
      <li><strong>Climbing advice and knowledge</strong> based on books and official resources.</li>
      <li><strong>Blog posts and stories from climbers</strong> who’ve been through their own crux moments.</li>
      <li><strong>Gear reviews</strong> based on personal opinions.</li>
    </ul>

    <h2>Join the project</h2>
    <p>
      This website is <a href="https://github.com/tsolakoua/crux-notes.git" target="_blank">open source</a>.
      If you have your own story to share or any feedback, contributions are more than welcome!
    </p>
  </div>
</body>
</html>
