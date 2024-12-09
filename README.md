<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Rotation</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            background-color: #000;
        }

        .rotating-image {
            width: 300px;
            height: 300px;
            background: url('image.png') no-repeat center center;
            background-size: contain;
            animation: rotate 2s infinite linear;
        }

        @keyframes rotate {
            from {
                transform: rotate(0deg);
            }
            to {
                transform: rotate(45deg);
            }
        }
    </style>
</head>
<body>
    <div class="rotating-image"></div>
</body>
</html>


<!---
LACHATAIGN/LACHATAIGN is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
