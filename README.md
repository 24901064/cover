# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
# book.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Money and the Power - Bharani Kumar S</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Roboto:wght@300;400&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background-color: #0b0b0b;
            color: #fff;
            overflow-x: hidden;
        }

        .hero {
            position: relative;
            height: 100vh;
            background: url('https://images.unsplash.com/photo-1561414927-6d86591d0c4f?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.6);
        }

        .content {
            position: relative;
            text-align: center;
            max-width: 700px;
            padding: 20px;
        }

        .content h1 {
            font-family: 'Playfair Display', serif;
            font-size: 4rem;
            color: #d4af37; /* gold tone */
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 20px;
        }

        .author {
            font-size: 1.2rem;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .author img {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            object-fit: cover;
            border: 2px solid #f0c929;
        }

        .author span {
            color: #f0c929;
            font-weight: bold;
        }

        .tagline {
            font-style: italic;
            color: #ccc;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            padding: 12px 30px;
            background: linear-gradient(135deg, #d4af37, #f0c929);
            color: #000;
            text-decoration: none;
            font-weight: bold;
            border-radius: 30px;
            transition: 0.3s ease;
        }

        .btn:hover {
            background: linear-gradient(135deg, #f0c929, #ffd700);
            transform: scale(1.05);
        }

        /* Responsive */
        @media (max-width: 768px) {
            .content h1 {
                font-size: 2.5rem;
            }
            .btn {
                padding: 10px 25px;
            }
            .author img {
                width: 40px;
                height: 40px;
            }
        }
    </style>
</head>
<body>
    <div class="hero">
        <div class="overlay"></div>
        <div class="content">
            <h1>Money and the Power</h1>
            <p class="author">
                <img src="myphoto.jpg" alt="Author photo">
                by <span>Bharani Kumar S</span>
            </p>
            <p class="tagline">“Control the money, command the power.”</p>
            <a href="#" class="btn">Explore More</a>
        </div>
    </div>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-10-30 204203.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
