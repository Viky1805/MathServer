# Ex.05 Design a Website for Server Side Processing
## Date:
24/11/24
## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
P = I<sup>2</sup>R
<br> P --> Power (in watts)
<br> I --> Intensity
<br> R --> Resistance

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<head>
</head>
<body align="center" style="background: linear-gradient(to right, #2f7336, #aaefa3);display: grid; place-items: center; height: 90vh; margin: 0;   ">

    <div style="width: 300px; height: 170px; background-color: lightblue; border-radius: 15px; border: 2px ; text-align: center; border: 1px solid black;background: linear-gradient(to right,rgb(84, 123, 222),rgb(55, 165, 205));">
        <h2>Calculator</h2>
        <input type="number" id="i" placeholder="Intensity" style="width: 70;height: 20;">
        <br>
        <input type="number" id="r" placeholder="Resistance">
        <br>
        <button onclick="check()">Check</button>
        <br>
        <output id="o"></output>
    </div>

    <script>
        function check() {
            var current = Number(document.getElementById('i').value);
            var resistance = Number(document.getElementById('r').value);
            var power=(current**2)*resistance
            document.getElementById("o").innerText="Power = "+power;
        }
    </script>
</body>
</html>
```

## SERVER SIDE PROCESSING:
![alt text](<Screenshot 2024-11-26 131508.png>)
## HOMEPAGE:
![alt text](<Screenshot 2024-11-26 130735-2.png>)

## RESULT:
The program for performing server side processing is completed successfully.
