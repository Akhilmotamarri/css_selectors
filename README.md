# css_selectors
internal style syntax
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>selectors</title>
    <style>
        /* id selector */
        #redelement
        {
            color: red;
        }
        /* class selector */
        .neat
        {
            border-radius: 30px;
            color: rgba(13, 13, 14, 0.753);
        }
        /* element selector */
        h3
        {
            color: green; 
        }
        /* class selector */
        .bgblue
        {
            border: 2px solid red;
            background-color: rgb(235, 29, 39);
        }
        /* grouping selector */
        div,span,footer{
            color:rgb(252, 0, 147)
        }

    </style>
</head>
<body>
    <marquee behavior="" direction="left
    "><h3>css selector</h3></marquee>
    <p>this is the Lorem ipsum dolor sit.
    </p>
    <p id="redelement">Lorem ipsum dolor sit amet.</p>
    <p class="neat bgblue">Lorem ipsum dolor sit amet consectetur adipisicing elit. Optio!</p>
    <span>hi akhil</span>
    <div>
        <span>greet</span>
    </div>
    <footer>
        this is footer
    </footer>
</body>
</html>
