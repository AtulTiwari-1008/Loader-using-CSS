# Loader-using-CSS
//Simple webpage Loader

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loader</title>
     <style>
        div {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 20px solid #FFE66D;
            border-top: 20px solid #4ECDC4;
            animation: spinAnimate 3s ease-in 0s infinite normal;
        }
         @keyframes spinAnimate{
            from{
                trsnsform: rotate(0deg);
            }
            to{
                transform: rotate(360deg)
            }
        }
    </style>
</head>
<body>
    <div class="loader"></div>
</body>
</html>
