---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ site.title }}</title>
    <style>
        .container {
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh; /* Adjust based on your preference */
            padding: 20px;
        }
        .image-container {
            flex: 1; /* Adjust the flex value if you need */
            max-width: 40%; /* You can adjust the width */
        }
        .image-container img {
            width: 100%;
            height: auto;
        }
        .text-container {
            flex: 1; /* Adjust the flex value if you need */
            max-width: 60%; /* You can adjust the width */
            padding-left: 20px; /* Adjust the spacing between image and text */
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="image-container">
            <img src="{{ '/assets/images/kirman_pic.jpg' | relative_url }}" alt="Dr. Benjamin Kirtman">
        </div>
        <div class="text-container">
            <h1>Welcome to Dr. Benjamin Kirtman Research Group</h1>
            <p>Welcome to the website dedicated to Dr. Benjamin Kirtman and his research group. Here you can find information on the research him and his group take part in, as well as learn more about Dr. Kirtman and his colleagues and students.</p>
            <!-- Add more text or elements as needed -->
        </div>
    </div>
</body>
</html>

---
