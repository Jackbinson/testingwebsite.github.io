<!DOCTYPE html>
<html>

<head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Pixelify+Sans:wght@400;600&display=swap" rel="stylesheet">



    <meta charset="UTF-8">
    <meta http-equiv="X-UA-compatible" content="IE=edge">
    <meta name="viewport" content="wide=device-width,initial-scale=1.0">
    <link rel="stylesheet" href="style/style.css">
    </link>
    <title>Pokedex</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Pixelify+Sans:wght@400;500;600&family=Roboto:ital,wght@1,300&display=swap"
        rel="stylesheet">
    <style>
        body {
            font-family: 'Pixelify Sans', sans-serif;

        }

        ul {
            list-style: none;
            display: flex;

        }


        li {
            list-style: none;
        }

        #Pokedex {
            width: 22rem;
            height: 35rem;
            background-color: white;
            border-radius: 8px;
            border: 10px solid white;

            background-size: 460px;
        }

        .name {

            margin: auto;
            color: black;
            font-family: 'Pixelify Sans', sans-serif;
            text-align: center;
            font-size: 200%;
            text-transform: uppercase;
            border: 10px solid black;




        }

        .image {

            display: flex;
            margin: auto;




            height: 170px;
        }

        .subtitle {
            justify-content: center;
            margin: auto;
            display: flex;
            font-family: 'Pixelify Sans', sans-serif;
            font-size: 20px;
            font-weight: lighter;
            border: 10px solid black;
            height: 100%;
            font-weight: lighter;
            padding: 3%;
            height: 1cm;
            text-transform: uppercase;
            border-inline-color: green;
            background-color: purple;


        }

        h1 {


            font-family: 'Pixelify Sans', sans-serif;
            font-size: 60px;
            text-align: center;
            background-color: white;
            border: 10px solid black;

        }

        p {
            border-top: 10px solid white;
            padding: 0%;
        }

        .l1 {
            background-color: white;
            border: 10px solid black;
            border-inline-color: green;
            height: 7, 5cm;
            border-width: 10px;
            width: 30%;
            margin-right: 2%;
            



        }

        


        

       
    </style>
</head>

<body>

    <h1> Pokedex </h1>
    <ul>

        <li class="l1">
            <p class="name"> bulbasaur </p>

            <img class="image" src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/1.png"
                alt="bulbasaurimg">
            <p class="subtitle"> Type: grass, poison </p>
        </li>
        <li class="l1">
            <p class="name"> ivysaur </p>
            <img class="image" src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/2.png"
                alt="ivysaur">
            <p class="subtitle"> Type: grass, poison</p>
        </li>
    </ul>





</body>

</html>
