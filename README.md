<html>

<head>
    <meta charset="utf-8" />
    <title>Map Animation</title>
    <meta name="viewport" content="initial-scale=1,maximum-scale=1,user-scalable=no" />
    <script src="https://api.mapbox.com/mapbox-gl-js/v1.11.0/mapbox-gl.js"></script>
    <link href="https://api.mapbox.com/mapbox-gl-js/v1.11.0/mapbox-gl.css" rel="stylesheet" />
    <link href="./styles.css" rel="stylesheet" />
</head>

<body>
    <div id="map"></div>
    <div class="map-overlay top">
        <button style="font-size: 2em" onclick="move()">
            Show stops between MIT and Harvard
        </button>
    </div>
    <script src="./mapanimation.js"></script>
</body>

</html>
