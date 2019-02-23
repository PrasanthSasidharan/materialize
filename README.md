# materialize
Material design with razor cshtml files

---- Code goes here

<!DOCTYPE html>
<html>

<head>
  <style>
    header,
    main,
    footer {
      padding-left: 300px;
    }

    @media only screen and (max-width : 992px) {

      header,
      main,
      footer {
        padding-left: 0;
      }
    }
  </style>
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css" media="screen,projection">
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</head>

<body>
  <div id="horizontal-nav-bar">
    <nav>
      <div class="nav-wrapper">
        <a href="#!" class="brand-logo">Logo</a>
        <ul class="right hide-on-med-and-down">
          <li><a href="sass.html">Sass</a></li>
          <li><a href="badges.html">Components</a></li>
          <li><a href="collapsible.html">Javascript</a></li>
          <li><a href="mobile.html">Mobile</a></li>
        </ul>
      </div>
    </nav>
  </div>
  <div class="container">
    <h1>Colors</h1>
    <div class="purple-text">
      Dive with color class
    </div>
    <h1>Buttons</h1>

    <button class="btn waves-effect">Read more</button>
    <button class="btn disabled ">Edit</button>
    
    <button class="btn add">
      <i class="material-icons left">warning</i> Upload
    </button>

    <!-- Floating button -->
    <a href="#" class="btn-floating blue large"> <i class="large material-icons ">add</i></a>
    <!-- Fixed action button  -->
    <div class="fixed-action-btn">
      <a class="btn-floating btn-large red">
        <i class="large material-icons">mode_edit</i>
      </a>
      <ul>
        <li><a class="btn-floating red"><i class="material-icons">insert_chart</i></a></li>
        <li><a class="btn-floating yellow darken-1"><i class="material-icons">format_quote</i></a></li>
        <li><a class="btn-floating green"><i class="material-icons">publish</i></a></li>
        <li><a class="btn-floating blue"><i class="material-icons">attach_file</i></a></li>
      </ul>
    </div>
  </div>
  <!--JavaScript at end of body for optimized loading-->
  <!-- <script type="text/javascript" src="js/materialize.min.js"></script> -->
  <script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
  <script>
    // Or with jQuery
    $(document).ready(function () {
      $('.fixed-action-btn').floatingActionButton();
      $('.sidenav').sidenav();
    });
  </script>
</body>

</html>

