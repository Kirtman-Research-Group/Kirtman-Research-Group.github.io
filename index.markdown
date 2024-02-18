---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Page</title>
    <style>
        .container {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh; /* Adjust the height as needed */
            padding: 20px;
        }
        .photo {
            flex: 1;
            max-width: 50%;
        }
        .photo img {
            width: 100%;
            height: auto;
        }
        .text {
            flex: 1;
            max-width: 50%;
            padding-left: 20px; /* Adjust the spacing between text and photo */
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="photo">
            <img src="/assets/images/kirtman_pic.jpg" alt="Descriptive Alt Text">
        </div>
        <div class="text">
            <h1>Welcome to My Website</h1>
            <p>This is a brief introduction or description that you want to show beside your photo. You can customize this text to fit your needs.</p>
            <!-- Add more text or elements as needed -->
        </div>
    </div>
</body>
</html>


---
