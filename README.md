# mini-project
<!DOCTYPE html>
<html lang="en">

<head>
  <title>HA</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <style>
    .container {
      position: relative;
      width: 50%;
    }

    .image {
      opacity: 1;
      display: block;
      width: 100%;
      height: auto;
      transition: .5s ease;
      backface-visibility: hidden;
    }

    .middle {
      transition: .5s ease;
      opacity: 0;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      -ms-transform: translate(-50%, -50%);
      text-align: center;
    }

    .container:hover .image {
      opacity: 0.3;
    }

    .container:hover .middle {
      opacity: 1;
    }

    .text {
      color: green;
      font-size: 16px;
      padding: 16px 32px;
    }
  </style>
</head>

<body>
  <div class="jumbotron text-center">
    <h1>Welcome to Home control</h1>
    <p>way to smart home</p>
  </div>
  <div class="container">
    <div class="column">
      <div class="col-sm-4 col-md-4">
        <div class="thumbnail"><a href="file:///home/adhityan/livingroom.html"><img src="https://images.homify.com/c_fill,f_auto,q_auto:eco,w_440/v1513668138/p/photo/image/2363797/living_room_01.jpg" alt="living room"></a>
          <div class="caption">
            <h3>living room</h3>
          </div>
        </div>
      </div>
    </div>
    <div class="column">
      <div class="col-sm-4 col-md-4">
        <div class="thumbnail"><a href="content://com.whatsapp.provider.media/item/55096"><img src="https://images.homify.com/c_fill,f_auto,q_auto:eco,w_440/v1517481818/p/photo/image/2417619/KITCHEN-01.jpg" alt="kitchen"></a>
          <div class="caption">
            <h3>kitchen</h3>
          </div>
        </div>
      </div>
    </div>
    <div class="column">
      <div class="col-sm-4 col-md-4">
        <div class="thumbnail"><a href="file:///home/adhityan/mini2.html"><img src="https://www.furnituremanila.com.ph/wp-content/uploads/2015/08/ORLANDO-SET-1.jpg" alt="bed room"></a>
          <div class="caption">
            <h3>bed room</h3>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container">
    <div class="column">
      <div class="col-sm-4 col-md-4">
        <div class="thumbnail"><a href="file:///home/adhityan/mini2.html"><img src="https://www.cleanlink.com/resources/editorial/2018/public-restroom-22173.jpg" alt="rest room"></a>
          <div class="caption">
            <h3>Rest room</h3>
          </div>
        </div>
      </div>
    </div>
</body>

</html>
