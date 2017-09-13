

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>

  <!-- Latest compiled and minified CSS -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
  <!-- Latest compiled and minified JavaScript -->
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>

</head>
<body>
  

  <div class="container">

    <h1>TANG Text and Image Formatting</h1>
    <hr>
    <p>Table of Contents</p>
    <ul>
      <li><a href="#1">1. Single Image</a></li>
      <ul>
        <li><a href="#11">1.1 Single Image Defaults</a></li>
        <li><a href="#12">1.2 Single Image Inside LI elements</a></li>
        <li><a href="#13">1.3 Single Image Inside TD elements</a></li>
      </ul>
      <li><a href="#2">2. Multiple Images</a></li>
      <ul>
        <li><a href="#">2. Multiple Images</a></li>
      </ul>
    </ul>
    <hr>


    <h2 id="1">1. Single Image</h2>

    <h3 id="11">1.1 Single Image Default</h3>

    <p class="lead">Single Image around P and H tags</p>

    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni corporis in reprehenderit illum neque fuga minus nemo deleniti porro reiciendis nesciunt accusamus temporibus a, facere iusto id ad ut assumenda?</p>

    <!-- Single Image around P and H tags BEGIN =========================== -->
    <div class="tang_figure_container tang_figure_container__single text-center">
      <figure class="tang_figure">
        <img src="http://via.placeholder.com/440x440" class="tang_figure__image img-responsive center-block" alt="The Pulpit Rock" width="440" height="440">
        <figcaption>Fig1. - A view of the pulpit rock in Norway.</figcaption>
      </figure> 
    </div>
    <!-- Single Image around P and H tags END =========================== -->
    

    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni corporis in reprehenderit illum neque fuga minus nemo deleniti porro reiciendis nesciunt accusamus temporibus a, facere iusto id ad ut assumenda?</p>

    <hr>
    <hr>
    ...
    <hr>
    <hr>

    <h3>1.2 Single Image Inside LI elements</h3>

    <ul class="">
      <li>List item 1</li>
      <li>List item 2</li>
      <li>List item 3</li>

      <!-- List item with Image BEGIN =========================== -->
      <li class="tang_figure_li tang_figure_li__single">
        List item 4
          <figure class="tang_figure">
            <img src="http://via.placeholder.com/440x440" class="tang_figure__image img-responsive" alt="The Pulpit Rock">
            <figcaption>Fig1. - A view of the pulpit rock in Norway.</figcaption>
          </figure> 
      </li>
      <!-- List item with Image END =========================== -->

      <li>List item 5</li>
      <li>List item 6</li>
      <li>List item 7</li>
    </ul>

    <hr>
    <hr>
    ...
    <hr>
    <hr>

    <h3 id="13">1.3 Single Image Inside TD elements</h3>

    <table class="table">
      <caption>Optional
      table
      caption.</caption>
      <thead>
        <tr>
          <th>#</th>
          <th>First Name</th>
          <th>Last Name</th>
          <th>Username</th>
        </tr>
      </thead>
        <tbody>
        <tr>
          <th scope="row">1</th>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
        </tr>
      <tr>
        <th scope="row">2</th>
        <td>Jacob</td>
        <!-- TD item with Image BEGIN =========================== -->
        <td class="tang_figure_td tang_figure_td_single">
          <figure class="tang_figure">
            <img src="http://via.placeholder.com/144x144" class="tang_figure__image img-responsive center-block" alt="The Pulpit Rock">
          </figure> 
        </td>
        <!-- TD item with Image END =========================== -->
        <td>@fat</td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td>Larry</td>
        <td>the
        Bird</td>
        <td>@twitter</td>
      </tr>
    </tbody>
    </table>


    <hr>
    <hr>
    ...
    <hr>
    <hr>

    <h2 is="2">2. Multiple Image</h2>

    <h3 id="21">2.1 Double Image</h3>

    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni corporis in reprehenderit illum neque fuga minus nemo deleniti porro reiciendis nesciunt accusamus temporibus a, facere iusto id ad ut assumenda?</p>

      <!-- Multiple Image around P and H tags BEGIN =========================== -->
      <div class="tang_figure_container tang_figure_container__multiple text-center">
        <div class="row">
          <div class="col-sm-6">
            <figure class="tang_figure">
              <img src="http://via.placeholder.com/440x440" class="tang_figure__image img-responsive center-block" alt="The Pulpit Rock" width="440" height="440">
              <figcaption>Fig1. - A view of the pulpit rock in Norway.</figcaption>
            </figure>
          </div>

          <div class="col-sm-6">
            <figure class="tang_figure">
              <img src="http://via.placeholder.com/440x440" class="tang_figure__image img-responsive center-block" alt="The Pulpit Rock" width="440" height="440">
              <figcaption>Fig1. - A view of the pulpit rock in Norway.</figcaption>
            </figure>
          </div>
        </div>
      </div>
      <!-- Multiple Image around P and H tags END =========================== -->

      <hr>
      <hr>
      ...
      <hr>
      <hr>

      
      <h3 id="22">2.2 Triple Images</h3>
      
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni corporis in reprehenderit illum neque fuga minus nemo deleniti porro reiciendis nesciunt accusamus temporibus a, facere iusto id ad ut assumenda?</p>

      <div class="tang_figure_container tang_figure_container__multiple text-center">
          <div class="row">
            <div class="col-sm-4">
              <figure class="tang_figure">
                <img src="http://via.placeholder.com/440x440" class="tang_figure__image img-responsive center-block" alt="The Pulpit Rock" width="440" height="440">
                <figcaption>Fig1. - A view of the pulpit rock in Norway.</figcaption>
              </figure>
            </div>
  
            <div class="col-sm-4">
              <figure class="tang_figure">
                <img src="http://via.placeholder.com/440x440" class="tang_figure__image img-responsive center-block" alt="The Pulpit Rock" width="440" height="440">
                <figcaption>Fig1. - A view of the pulpit rock in Norway.</figcaption>
              </figure>
            </div> 

            <div class="col-sm-4">
              <figure class="tang_figure">
                <img src="http://via.placeholder.com/440x440" class="tang_figure__image img-responsive center-block" alt="The Pulpit Rock" width="440" height="440">
                <figcaption>Fig1. - A view of the pulpit rock in Norway.</figcaption>
              </figure>
            </div>

          </div>
        </div>
        <!-- Multiple Image around P and H tags END =========================== -->

  </div>

  <br>
  <br>
  <br>
  <br>
  <br>

</body>
</html>
