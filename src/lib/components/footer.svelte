<footer class="footer">
    <div class="container">
      <h2>FOR MORE QUESTIONS</h2>
      <ul class="links">
        <li><a href="/"><img src="images/tel.png" alt="Facebook">+31 6 22428876</a></li>
        <li><a href="mailto: info.impactofficials@gmail.com"><img src="images/mail.png" alt="Twitter">info.impactofficials@gmail.com</a></li>
        <li><a href="https://www.instagram.com/impact.officials/"><img src="images/insta.png" alt="Instagram">impact.officials</a></li>
        <li><a href=""><img src="images/tiktok.png" alt="LinkedIn">impact.officials</a></li>
      </ul>
    </div>
  </footer>

  <style>
 .footer {
  color: #fff;
  position: absolute;
  bottom: 0;
  width: 100%;
  border-top: 1px solid #fff; /* Add a thin white line */
}

.container {
  padding: 25px;
  display: flex;
  justify-content: space-between;
}

h2 {
  margin: 0;
}

img {
  width: 25px;
  margin-right: 4px;
  margin-bottom: -4px;
}

.links {
  display: flex;
}

.links a {
  font-size: 18px;
  color: #ffff;
  text-decoration: none;
  margin-right: 20px; /* Spacing between links */
}

ul {
  padding: 0;
  text-align: left;
}
li {
  text-decoration: none;
  list-style: none;
}

/* Media query for mobile */
@media only screen and (max-width: 900px) {
  .container {
    flex-direction: column;
    padding: 10px;
    bottom: 0;
  }

  h2 {
    margin-bottom: 1em;
    text-align: start;
  }

  .links {
    flex-direction: column;
  }

  /* .links a {
    margin: 5px 0;
  } */
}

  </style>