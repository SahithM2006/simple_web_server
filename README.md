# EX01 Developing a Simple Webserver

# Date:12/10/2024
# AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

# DESIGN STEPS:
## Step 1:
HTML content creation.

## Step 2:
Design of webserver workflow.

## Step 3:
Implementation using Python code.

## Step 4:
Serving the HTML pages.

## Step 5:
Testing the webserver.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web Server</title>
    <style>
        /* Global Styles */
        body {
            font-family: 'Cambria', Cochin, Georgia, Times, 'Times New Roman', serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        h1 {
            color: rgb(0, 37, 60);
            margin-bottom: 30px;
        }

        /* Container for the cards */
        .card-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            width: 90%;
            max-width: 1200px;
            margin: 20px;
        }

        /* Card Styles */
        .card {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border: 1px solid #ddd;
            transition: transform 0.3s ease-in-out;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h3 {
            color: rgb(0, 37, 60);
            font-size: 20px;
            margin-bottom: 10px;
        }

        .card p {
            color: rgb(0, 37, 60);
            font-size: 16px;
            margin: 0;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .card-container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <h1>Laptop Features and Components</h1>

    <div class="card-container">
        <!-- Card for each feature -->
        <div class="card">
            <h3>Processor</h3>
            <p>13th Intel(R) Core(TM) i5-1224P, 1300 MHz, 10 Core(s), 12 Logical Processor</p>
        </div>
        <div class="card">
            <h3>Storage (HDD/SSD)</h3>
            <p>SAMSUNG QXST2708THES-00BL1</p>
        </div>
        <div class="card">
            <h3>Memory</h3>
            <p>800 GB</p>
        </div>
        <div class="card">
            <h3>Graphics Card</h3>
            <p>Intel(R) Iris(R) Xe Graphics, NVIDIA GeForce MX550</p>
        </div>
        <div class="card">
            <h3>Operating System</h3>
            <p>Edition: Linux, Version: 22H2, OS Build: 22621.4169</p>
        </div>
        <div class="card">
            <h3>RAM</h3>
            <p>32.0 GB</p>
        </div>
    </div>

</body>
</html>
```
# OUTPUT:
![Screenshot 2024-12-07 231946](https://github.com/user-attachments/assets/89456b8b-d1a8-4d17-847e-f06f972b3df8)

# RESULT:
The program for implementing simple webserver is executed successfully.
