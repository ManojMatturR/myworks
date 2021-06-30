<html>
    <head>
        <title> Responsive login </title>
        <link href="https://fonts.google.com/share?selection.family=Merriweather:wght@300">
        <style>
            body{
                display: flex;
                align-items: center;
                justify-content: center;
                flex-direction: row;
                background-image: url(https://images.unsplash.com/photo-1531278329486-539bf3bd6d5e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxleHBsb3JlLWZlZWR8N3x8fGVufDB8fHx8&w=1000&q=80);
                
            }
            
            .container{
                display: flex;
                align-items: center;
                justify-content: center;
                flex-direction: column;
                border: 1px solid rgb(227, 231, 227);
                padding: 50px;
                background: #dde1e7;
                box-shadow: 3px 3px hsla(189, 89%, 83%, 0.937);
            }
            .name{
                margin: 2px;   
                padding: 10px;
                background: #ffffff;
	            box-shadow: -3px -3px 7px #ffffffef, 3px 3px 5px rgba(94, 104, 121, 228);
	            border-radius: 3px;
                border: none;
                background: #dde1e7;
            }
            .mail{
                margin: 2px;                
                padding: 10px;
                background: #ffffff;
	            box-shadow: -3px -3px 7px #fffffff8, 3px 3px 5px rgba(94, 104, 121, 228);
	            border-radius: 3px;
                border: none;
                background: #dde1e7;
            }
            .password{
                margin: 2px;                
                padding: 10px;
                background: #ffffff;
	            box-shadow: -3px -3px 7px #fffffff8, 3px 3px 5px rgba(94, 104, 121, 228);
	            border-radius: 3px;
                border: none;
                background: #dde1e7;
            }
            .btn{
                font-family: sans-serif;
                margin-top: 20px;
                margin-right: 10px;
                font-size: 12px;
                padding-top: 2px;
                padding-bottom: 2px;
                color:rgb(255, 255, 255);
                background: rgb(97, 194, 32);
                border: none;
            }
            .btn:hover {background-color: green}
            .btn:active {
            background-color: #52b655;
            box-shadow: 3px 3px rgb(147, 153, 155);
            transform: translateY(4px);
            outline: none;
            }
            label{
                color:rgb(59, 55, 55);
                border-radius: 3px;
                margin: 5px;
                padding: 1px;
            }
            h1{
                font-style: Merriweather;
                color: rgb(63, 63, 235);
                margin-top: 0px;
            }
            input[type=text]:focus, input[type=password]:focus, input[type=email]:focus {
            background-color: #ffffff;
            outline: none;
            }
        </style>
    </head>
    <body>
        <div class="bg-image"></div>
    <div class="container">
        <h1>Login</h1>
        <label for="username">Username:</label>
        <input class="name" type="text" placeholder="your name">
        <label for="email">Email:</label>
        <input class="mail" type="email" placeholder="eg:-manoj@gmaol.com">
        <label for="password">Passsword:</label>
        <input class="password" type="password" placeholder="enter password">
        <div class="buttons">
        <button class="btn">Login</button>
        <a href="#">forget password</a>
    </div>
    </div>  
    </body>
</html>
