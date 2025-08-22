# websiteVynSky

    Nano index.html                                                      
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Website</title>
<style>
body { font:16px/1.5 Arial,sans-serif; text-align:center; background:#f0f0f0; margin:0; padding:20px; }
.container { background:#fff; padding:20px; border-radius:15px; display:inline-block; }
img { width:200px; height:200px; border-radius:50%; margin:10px 0; }
</style>
</head>
<body>
<div class="container">
<h1>Halo, Selamat Datang!</h1>
<img src="https://raw.githubusercontent.com/NdikzDatabase/Database/main/Database/1755612711971-5jl9vx.jpg" alt="Foto Saya">
<p>Website sederhana tapi keren dengan foto dari GitHub.</p>
</div>
</body>
</html>


    nano style.css
body {
    font-family: Arial, sans-serif;
    font-size: 16px;
    line-height: 1.5;
    text-align: center;
    background-color: #e0f7fa;
    margin: 0;
    padding: 20px;
}

.container {
    background-color: #ffffff;
    padding: 25px;
    border-radius: 20px;
    display: inline-block;
    box-shadow: 0 6px 12px rgba(0,0,0,0.15);
    transition: transform 0.3s, box-shadow 0.3s;
}

.container:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.25);
}

img {
    width: 220px;
    height: 220px;
    border-radius: 50%;
    margin: 15px 0;
    object-fit: cover;
    transition: transform 0.3s;
}

img:hover {
    transform: scale(1.05);
}

h1 {
    font-size: 32px;
    color: #00796b;
    margin-bottom: 15px;
}

p {
    font-size: 18px;
    color: #555555;
    margin: 10px 0;
}
