<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projections</title>
</head>
<body>
    <h1>Homework 3: Experimenting with Projections</h1>
    
    <h2 style="color:red">In this project I learned how to display images in different projections</h2>
    <p>For this project, I modified vector data downloaded from Natural Earth of a world map. After I unzipped the file, I was able to 
        import the same base shapefile into QGIS for each of my projections. Then, I changed the CRS, or Coordinate Reference
        System, that the map was being projected with. To do this, I inputted the specified ESRI or ESPG projection identifications (think "EPSG:3857" for the 
        Psuedo-Mercator projection). From there, I applied the Indicatrix Mapper plugin to my project which put a layer of ellipsoidal caps over
        my map to visualize the inherent distortions caused by that certain projection. Finally, I fit my map into the print layout and exported it as a PNG. I 
        repeated this process for all projections.  </p>
    

    <h2>WGS84 Projection</h2>
    <h3>This projection is widely used as the standard for GPS. Although it nearly perfect at the equator,
        there is major area, distance, and shape distortion occurs at the poles. 
    </h3>
    <a href=".//maps/4326.png">
    <img src=".//maps/4326.png" alt="WGS84" width='500px'>
    </a>


    <h2>Aitoff Projection</h2>
    <h3>This projection has the most correct scale along the central meridian and equator.
        It also has value in being an ellipsoidal shape, which is reminiscent of 
        the original sphereical shape of the earth. However, the peripheral regions of the map have
        the most distortion, of direction, distance, area and shape. 
    </h3>
    <a href=".//maps/54043.png">
    <img src=".//maps/54043.png" alt="Aitoff" width='500px'>
    </a>


    <h2>Pseudo-Mercator Projection: EPSG-3857</h2>
    <h3>Although this projection preserves shapes and especially direction, 
        it greatly distorts area and distance! This is evidenced by the Atlantic Ocean looking much smaller 
        and land masses near the poles, such as Antarctica and Greenland looking gigantic 
        in juxtaposition to other continents. 
    </h3>
    <a href="/hw3-3857.png">
    <img src="/hw3-3857.png" alt="Pseudo-Mercator" width='500px'>
    </a>


    <h2 style="color:red">Now, you should <u>add the following projections on your own:</u></h2>
    <h3>EPSG: 3857, 53018, 54034, 54027, 102016, and two additional projections that you choose.</h3>
    <p></p>
    <h2>Data used for this project</h2>
    <a href="https://www.naturalearthdata.com/http//www.naturalearthdata.com/download/10m/cultural/ne_10m_admin_0_countries.zip"> Download Natrual Earth 1:10m Cultural Vector </a>
</body>
</html>
