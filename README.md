<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Transitions </title>
</head>
<style>
*{
box-sizing:border-box;
margin:0px;
padding:0px;
}
body{
margin:20px;
background-color:#f2e49f;
font-family: Arial, sans-serif;
}

        .nav {
            position: absolute;
            top: 70px;
            right: 30%;
            display: inline;
            background-color: #8c9393;
            padding: 10px;
            border-radius: 4px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        .nav a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
            font-weight: bold;
            padding:7px;
            border-radius:7px;
            transition: background-color 1s ease-out;
        }
        .nav a:hover {
           background-color: black;
        }    
        .container{
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-top: 150px;
        }
        .image-container {
            grid-column: 1;
        }
        .text-container {
            grid-column: 2;
        }
        img{
            height:250px;
            width:auto;
            cursor:pointer;
margin-bottom:100px;
            transition: height 1s ease, width 1s ease;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        img:hover{
            height:290px;
            width:440px;
        }
        p{
            background-color:#8c9393;
            color:white;
            margin:15px;
            padding:20px;
            border-radius:6px;
            transition: background-color 0.8s ease, padding 0.7s ease-in;
            cursor:pointer;
            font-size: 18px;
        }
        p:hover{
            background-color:black;
            padding:30px;
        }
        h1, h2 {
            font-weight: bold;
            color: #333;
            margin-bottom: 10px;
        }
        h1 {
            font-size: 36px;
        }
        h2 {
            font-size: 24px;
        }
.foot{
height:180px;
background-color:#8c9393;
color:white;
padding:20px;
line-height:30px;
cursor:pointer;
text-align:center;
position:relative;
transition: background-color 0.9s ease;
}
.foot:hover{
background-color:black;
}
#f1:hover{
color:lightgrey;
transition:0.7s;
}
#f2:hover{
color:lightgrey;
transition:0.7s;
}
#f3:hover{
color:lightgrey;
transition:0.7s;
}
#f4:hover{
color:lightgrey;
transition:0.7s;
}
#f5:hover{
color:lightgrey;
transition:0.7s;
}
@media only screen and (max-width: 768px) {
    .nav {
        position: relative;
        top: 0;
        right: 0;
        display: block;
        background-color: #8c9393;
        padding: 10px;
        border-radius: 4px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }
    .nav a {
        display: block;
        margin: 10px 0;
    }
    .container {
        display: block;
        margin-top: 30px;
    }
    .image-container {
        margin-bottom: 20px;
    }
    .text-container {
        margin-bottom: 20px;
        margin-top:10px;
    }
    img {
        height: 200px;
        width: auto;
    }
    .foot {
        height: 160px;
        padding: 10px;
    }
}
@media only screen and (min-width: 769px) and (max-width: 1024px) {
    .nav {
        position: absolute;
        top: 70px;
        right: 20%;
        display: inline;
        background-color: #8c9393;
        padding: 10px;
        border-radius: 4px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }
    .nav a {
        margin: 0 10px;
    }
    .container {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 20px;
        margin-top: 150px;
    }
    .image-container {
        grid-column: 1;
    }
    .text-container {
        grid-column: 2;
    }
    img {
        height: 250px;
        width: auto;
    }
    .foot {
        height: 180px;
        padding: 20px;
    }
}
@media only screen and (min-width: 1025px) {
    .nav {
        position: absolute;
        top: 70px;
        right: 30%;
        display: inline;
        background-color: #8c9393;
        padding: 10px;
        border-radius: 4px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }
    .nav a {
        margin: 0 10px;
    }
    .container {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 20px;
        margin-top: 150px;
    }
    .image-container {
        grid-column: 1;
    }
    .text-container {
        grid-column: 2;

    }
    img {
        height: 250px;
        width: auto;
    }
    .foot {
        height: 180px;
        padding: 20px;
    }
}
</style>
<body>
         
            <div class="nav">
                <a href="#">Home</a>
                <a href="#">New Updates</a>
                <a href="#">About Us</a>
                <a href="#">Contact Us</a>
            </div>
    <div class="container">
        <div class="image-container">
            <img src="https://allanimalfacts.com/wp-content/uploads/2023/07/Peregrine-Falcon.webp" alt="falcon">
        </div>
        <div class="text-container">
            <h1>Peregrine Falcon</h1>
            <p>Witness the dignity and grace of the peregrine falcon. This extraordinary bird is a master of hunting and soaring in mid-air, its wings spread wide towards its prey. Its powerful claws can capture swiftly even when diving at considerable speeds, demonstrating why it is one of nature’s most formidable predators. Widespread around the world with numerous subspecies existing from Eurasia to North America, discover more about this remarkable creature as we explore how it hunts, reproduces, and adapts to various terrains! </p>
        </div>
        
        <div class="image-container">
            <img src="https://allanimalfacts.com/wp-content/uploads/2023/07/Peregrine-Falcon-Image.webp" alt="falcon">
        </div>
        <div class="text-container">
            <h2>Peregrine Falcon Lifespan</h2>
            <p>The average lifespan of a peregrine falcon is approximately 10 to 15 years, although some birds have been known to live up to 25 years in the wild. In captivity, it is possible for them to live even longer due to the protection and care provided by their handlers. Peregrine falcons reach sexual maturity at around 2 years old and typically reproduce once a year with each pair producing 3 to 4 eggs per clutch. Both parents care for their young until they are able to leave the nest at around 6 weeks old. The chicks then remain with their parents for another couple of months while they learn how to hunt before they are independent enough to venture out on their own. In terms of predation risk, peregrine falcons typically face little danger due to their impressive speed and agility when flying as well as their ability to take on larger prey like ducks or geese, both of which are formidable predators themselves. Human activity such as hunting or poaching can also contribute heavily to decreasing peregrine populations in certain areas. </p>
        </div>
    </div>
<footer>
<div class="foot">
  <div id="f1">Privacy Policy </div>
<div id="f2">License </div>
<div id="f3">Imprint </div>
<div id="f4">Cookies Policy </div>
<div id="f5">© 2024 all rights are reserved Terms of Use </div>
</div>
</footer>
</body>
</html>
