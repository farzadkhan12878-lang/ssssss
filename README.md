<!DOCTYPE html>
<html>
<head>
    <title>Social Media Cards</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: Arial, sans-serif;
            background: white;
        }

        .container {
            display: flex;
            gap: 25px;
        }

        .card {
            width: 190px;
            height: 272px;
            border: 1px solid black;
            text-align: center;
            padding: 25px 13px;
        }

        .instagram {
            background: #e52b6b;
            color: white;
            border: none;
        }

        .icon {
            font-size: 45px;
            margin-bottom: 15px;
        }

        .card h2 {
            font-size: 20px;
            margin: 0 0 12px;
        }

        .card p {
            font-size: 12px;
            line-height: 1.35;
            margin: 0 0 15px;
        }

        .btn {
            width: 100%;
            height: 32px;
            border: none;
            border-radius: 20px;
            background: black;
            color: white;
            cursor: pointer;
        }

        .instagram .btn {
            background: white;
            color: #e52b6b;
        }
    </style>
</head>

<body>

    <div class="container">

        <!-- Twitter -->
        <div class="card">
            <div class="icon">🐦</div>

            <h2>TWITTER</h2>

            <p>
                Lorem ipsum dolor sit amet,
                consectetur adipisicing elit.
                Expedita ullam aliquid non
                eligendi, nemo est neque
                reiciendis error?
            </p>

            <button class="btn">READ MORE</button>
        </div>


        <!-- Instagram -->
        <div class="card instagram">
            <div class="icon">◎</div>

            <h2>INSTAGRAM</h2>

            <p>
                Lorem ipsum dolor sit amet,
                consectetur adipisicing elit.
                Expedita ullam aliquid non
                eligendi, nemo est neque
                reiciendis error?
            </p>

            <button class="btn">READ MORE</button>
        </div>


        <!-- YouTube -->
        <div class="card">
            <div class="icon">▶</div>

            <h2>YOUTUBE</h2>

            <p>
                Lorem ipsum dolor sit amet,
                consectetur adipisicing elit.
                Expedita ullam aliquid non
                eligendi, nemo est neque
                reiciendis error?
            </p>

            <button class="btn">READ MORE</button>
        </div>

    </div>

</body>
</html>
