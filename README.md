<!DOCTYPE html>

<head></head>

<body>

    <body style="font-family:Arial, Helvetica, sans-serif;background-color: rgb(255, 255, 255);background-color:Azure">
        <!-- Navbar -->
        <div style="border: solid black;padding: 15px;background-color:rgb(144, 159, 159) ;">
            <div class="AnecdoteCom">
                <span style="color: black;border: solid black ;padding: 5px;">Anecdote</span>
            </div>

            <div class="AllNavbar">
                <ul class="UL">
                    <!-- <select>
                        <option>
                            <li>Services</li>
                        </option>
                        <option>
                            <li>Anecdote</li>
                        </option> -->
                    </select>
                    <p class="AboutMe">About Me</p>
                    <p class="Anecdotee">Anecdote</p>
                    <p class="register">Register</p>
                </ul>
            </div>
        </div>
        <style>
            *,

            html {
                padding: 0;
                margin: 0;
            }


            .Anecdotee {
                border: 2px solid black;
                padding: 10px;
                font-size: 30px;
                font-style: italic;
                background-color: white;
                border-radius: 1px;
                cursor: pointer;
                margin-bottom: 20px;
                transition: background 0.3s, transform 0.9s;
            }

            .Anecdotee:hover {
                background: rgb(179, 179, 179);
                transform: scale(1.05);
            }

            .AboutMe {
                border: 2px solid black;
                padding: 10px;
                font-size: 30px;
                font-style: italic;
                background-color: white;
                border-radius: 1px;
                cursor: pointer;
                margin-bottom: 20px;
                transition: background 0.3s, transform 0.9s;
            }

            .AboutMe:hover {
                background: rgb(179, 179, 179);
                transform: scale(1.05);
            }

            .AnecdoteCom {
                display: flex;
                justify-content: flex-start;
                font-size: 30px;
            }

            UL {
                display: flex;
                gap: 30px;
                align-items: center;
                cursor: pointer;

            }

            .register {
                border: 2px solid black;
                padding: 10px;
                font-size: 30px;
                font-style: italic;
                background-color: white;
                border-radius: 1px;
                cursor: pointer;
                margin-bottom: 20px;
                transition: background 0.3s, transform 0.5s;
            }

            .register:hover {
                background: rgb(179, 179, 179);
                transform: scale(1.05);
            }

            .AllNavbar {
                font-size: 20px;
                display: flex;
                justify-content: center;
                gap: 50px;
                margin-right: 50px
            }
        </style>

        <!-- content -->

        <div class="contentNav1">
            <a href="#">Page 1</a>
            <a href="#">Page 2</a>
            <a href="#">Page 3</a>
            <a href="#">Page 4</a>
            <a href="#">Page 5</a>
        </div>

        <div class="contentNav2">
            <a href="#">Page 6</a>
            <a href="#">Page 7</a>
            <a href="#">Page 8</a>
            <a href="#">Page 9</a>
            <a href="#">Page 10</a>
        </div>

        <div class="contentNav3">
            <a href="#">Page 11</a>
            <a href="#">Page 12</a>
            <a href="#">Page 13</a>
            <a href="#">Page 14</a>
            <a href="#">Page 15</a>
        </div>

        <style>
            .contentNav1 {
                display: flex;
                justify-content: space-evenly;
                border: solid black;
                margin-top: 80px;
                margin-left: 10px;
                margin-right: 10px;
            }

            .contentNav2{
                display: flex;
                justify-content: space-evenly;
                border: solid black;
                margin-top: 80px;
                margin-left: 10px;
                margin-right: 10px;
            }
            
            .contentNav3{
                display: flex;
                justify-content: space-evenly;
                border: solid black;
                margin-top: 80px;
                margin-left: 10px;
                margin-right: 10px;
            }
        </style>
        <!-- content end  -->
    </body>
