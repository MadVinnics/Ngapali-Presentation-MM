# Ngapali-Presentation-MM
ngapali_presentation.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ngapali Beach - Photo Presentation</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2f86c7;
            color: white;
            text-align: center;
            padding: 20px;
        }
        section {
            padding: 20px;
        }
        h1, h2 {
            color: #2f86c7;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .gallery-item {
            margin: 15px;
            text-align: center;
        }
        .gallery-item img {
            max-width: 300px;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .gallery-item p {
            margin-top: 8px;
            font-size: 14px;
            color: #555;
        }
        footer {
            background-color: #2f86c7;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Ngapali Beach</h1>
    <p>Photo Presentation by Min Thet Khaing</p>
</header>

<section>
    <h2>Ngapali Beach Gallery</h2>
    <div class="gallery">
        <div class="gallery-item">
            <img src="https://example.com/ngapali-beach1.jpg" alt="Sunset at Ngapali Beach">
            <p>Sunset at Ngapali Beach</p>
        </div>
        <div class="gallery-item">
            <img src="https://example.com/ngapali-beach2.jpg" alt="Palm trees along the shore">
            <p>Palm Trees along the Shore</p>
        </div>
        <div class="gallery-item">
            <img src="https://example.com/ngapali-beach3.jpg" alt="Fishing boats at Ngapali">
            <p>Traditional Fishing Boats</p>
        </div>
        <div class="gallery-item">
            <img src="https://example.com/ngapali-beach4.jpg" alt="Crystal-clear waters">
            <p>Crystal-clear Waters of Ngapali</p>
        </div>
        <div class="gallery-item">
            <img src="https://example.com/ngapali-beach5.jpg" alt="Seafood market at the beach">
            <p>Fresh Seafood Market by the Beach</p>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Min Thet Khaing</p>
</footer>

</body>
</html>
