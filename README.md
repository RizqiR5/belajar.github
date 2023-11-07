<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
        .rectangle-container {
            display: flex;
            align-items: center;
            background-color: red;
            padding: 20px;
        }

        .logo {
            font-size: 36px;
            font-weight: bold;
            color: white;
            margin-right: 10px;
            font-family: 'Cutive';
        }

        .text {
            font-size: 24px;
            font-family: 'Cutive';
            color: black;
        }

        .share-bar {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }

        .share-button {
            margin-right: 10px;
            padding: 10px 20px;
            text-decoration: none;
            color: #fff;
            border-radius: 5px;
            cursor: pointer;
        }

        .share-button.WhatsAap {
            background-color: #1877f2;
        }

        .share-button.Instagram {
            background-color: #1da1f2;
        }
    </style>
    <title>Murayama IMG</title>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item active">
                        <a class="nav-link" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="https://web.whatsapp.com/">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <div class="container mt-5">
        <div class="row">
            <div class="col-12">
                <div class="rectangle-container">
                    <span class="logo">M</span>
                    <span class="text">Murayama IMG</span>
                </div>
            </div>
        </div>
    </div>
    <div class="container mt-3">
        <h5>
            <p>Anda dapat menemukan banyak inspirasi!</p>
        </h5>
        <div class="image-rotation">
            <img src="5.JPG" class="img-fluid" alt="10">
            <img src="2.JPG" class="img-fluid" alt="2">
            <img src="10.JPG" class="img-fluid" alt="10">
            <img src="3.JPG" class="img-fluid" alt="3">
            <img src="4.JPG" class="img-fluid" alt="4">
        </div>
    </div>
    <div class="share-bar">
        <a class="share-button WhatsAap"
            href="https://www.WhatsAap.com/sharer/sharer.php?u=URL_TO_SHARE&text=Check%20out%20this%20awesome%20content"
            target="_blank">WhatsAap</a>
        <a class="share-button Instagram"
            href="https://www.Instagram.com/intent/tweet?url=URL_TO_SHARE&text=Check%20out%20this%20awesome%20content"
            target="_blank">Instagram</a>
    </div>
    <div id="about" class="container mt-3">
        <h5>Tentang Kami</h5>
        <p>
            Hallo, Selamat datang di web kami semoga anda dapat menemukan banyak inovatif dan inspirasi. Jika anda penasaran dengan web Murayama IMG mari saya jelaskan.
            Murayama IMG sendiri adalah sebuah web yang menyajikan berbagai foto yang menarik dan inovatif, dan juga jika anda mau melihat atau mencari info yang lebih lanjut silahkan klik WhatsApp saya atau bisa menghubungi nomor yang tertera disamping ini
            +6285931380940
        </p>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>
</body>
</html>
