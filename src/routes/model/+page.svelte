<script>
    import Navigation from "$lib/components/2navigation.svelte";
    import Form from "$lib/components/2form.svelte";
</script>

<body>
    <Navigation></Navigation>
    <div class="row">
        <div class="column">
          <h1>IMPACT</h1>
            <h3>*When registering, it's crucial to keep in mind that you won't be automatically enrolled. Instead, there's a selection process that you'll need to undergo.</h3>

        </div>
        <div class="column">
         <Form></Form>
        </div>
      </div>
    </body>
    <style>
        * {
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
        }
    
        
    
        body {
        margin: 0;
        background-image: url("/images/model.png");
        min-height: 100vh;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        position: relative;
        text-align: center;
        }
    
        * {
      box-sizing: border-box;
      margin: 0;
    }
    
    h1 {
        color: var(--impact-yellow);
        font-size: 120px;
    }
    
    h2 {
      color: white;
    }
    h3 {
    font-family: MADE Future x;
    font-size: 12px;
    color:  var(--impact-light-grey);
    padding: 1em;
    padding-top: 0;
}
    
    
    /* Create two equal columns that floats next to each other */
    .column {
      float: left;
      width: 50%;
      padding: 10px;
    }
    
    /* Clear floats after the columns */
    .row:after {
      content: "";
      display: table;
      clear: both;
    }
    
    /* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
    @media screen and (max-width: 720px) {
      .column {
        width: 100%;
      }
    }

    @media only screen and (min-width: 750px) {
        h1 {
            color: var(--impact-yellow);
        font-size: 15vw;
    }
    }
    </style>