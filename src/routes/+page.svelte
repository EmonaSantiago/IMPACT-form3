<body>
    <div class="row">
        <div class="column">
          <h1>IMPACT</h1>
          <h3>WELCOME TO THE IMPACT <span>APPLICATION FORM</span></h3>
        </div>
    
        <div class="column">
             <ul class="link-list">
                <li><a href="/">CREATIVE</a></li>
                <li><a href="/">MODEL</a></li>
                <li><a href="/">CREW</a></li>
            </ul>
        </div>
</body>


<style>
* {
    margin: 0;
    box-sizing: border-box;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}

    :root {
        --impact-yellow: #F8F053;
    }

body {
    margin: 0;
    background-image: url("/images/TEAMimpact.png");
    height: 100vh;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    text-align: center;
}

.column {
  float: left;
  width: 50%;
  padding: 10px;
  padding-top: 30px;
  height: 300px;
  
}


.row:after {
  content: "";
  display: table;
  clear: both;
}

h1 {
    color: var(--impact-yellow);
    font-size: 120px;
}

span { 
        color: var(--impact-yellow);
    }

h3 {
    color: white;
}

h3, span {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 20px;
}
.link-list {
    list-style-type: none;
    padding: 0;
}

.link-list li {
    margin-bottom: 10px;
}

.link-list li a {
    display: block;
    text-decoration: none;
    color: #333;
    background-color: var(--impact-yellow);
    padding: 10px 20px; 
    border-radius: 5px; 
}

.link-list li a:hover {
    background-color: transparent; 
    color: var(--impact-yellow);
    border: solid 2px black;
}


@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>