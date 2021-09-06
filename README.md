<h1>Designer With Animations</h1>

![menu1](https://user-images.githubusercontent.com/90210126/132253077-08fae5de-0013-4cdd-a5da-e4ae53158310.png)

<h3>HTML</h3>



```
<!DOCTYPE html>
<html lang="br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="designer.css">
    <title>SEGURANÇA CIBERNÉTICA</title>



</head>
<body>

    <div class="">

        <nav id="menu-h">

            <ul>
                <li><a href="#">CYBER SECURITY</a></li>
                <li class="esquerda"><a href="#">ÍNICIO</a></li>
                <li class="esquerda"><a href="#">NOTÍCIAS</a></li>
                <li class="esquerda"><a href="#">YOUTUBE</a></li>
                <li class="esquerda"><a href="#">CONTATO</a></li>
                <li><a href="#">ENTRAR</a></li>
    
            </ul>

        </nav>
        

    </div>
    
</body>
</html>
```


<h3>CSS</h3>

```
* {
    margin: 0 auto;

    box-sizing: border-box;
    font-family: 'Open Sans', sans-serif;
}

body {

    background-image: linear-gradient(to right, rgb(75, 170, 233), rgb(2, 45, 100));

}

#menu-h{
    background-color: rgb(37, 37, 39);
    text-align: center;
    
    
}

#menu-h ul {
    max-width: px;
    list-style: none;
    padding: 0;
    
}

#menu-h ul li {
    display: inline;
    
}

#menu-h ul li a {
    color: #FFF;
    padding: 20px;
    display: inline-block;
    text-decoration: none;
    transition: background .4s;
}

#menu-h ul li a:hover {
    background-image: linear-gradient(to right, rgb(30, 139, 212), rgb(2, 45, 100));
}

#menu-h ul li:last-child a {
    float: right;
    color:white;
}


#menu-h ul li:first-child a{

    float: left;

}
```
