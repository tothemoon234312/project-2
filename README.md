<!DOCTYPE html>
<html>
<head>
    <title>Ks Registration</title>

    <style>
        html, body {
            min-height: 100%;
        }

        body, div, form, input, select, p {
            padding: 0;
            margin: 0;
            outline: none;
            font-family: Roboto, Arial, sans-serif;
            font-size: 16px;
            color: #eee;
        }

        h1, h2 {
            text-transform: uppercase;
            font-weight: 400;
        }

        h2 {
            margin: 0 0 0 8px;
        }

        .main-block {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 25px;
            background: #B0B3D6;
        }

        .left-part, form {
            padding: 25px;
        }


        form {
            background: rgba(0, 0, 0, 0.7);
        }

        .title {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }

        .info {
            display: flex;
            flex-direction: column;
        }

        input, select {
            padding: 5px;
            margin-bottom: 30px;
            background: transparent;
            border: none;
            border-bottom: 1px solid #eee;
        }

        input::placeholder {
            color: #eee;
        }

        option {
            background: black;
            border: none;
        }

        .checkbox input {
            margin: 0 10px 0 0;
            vertical-align: middle;
        }

        .checkbox a:hover {
            color: #85d6de;
        }

        .btn-item, input[type=submit], input[type=reset] {
            padding: 10px 5px;
            margin-top: 20px;
            border-radius: 5px;
            border: none;
            background: #26a9e0;
            text-decoration: none;
            font-size: 15px;
            font-weight: 400;
            color: #fff;
        }

        .btn-item {
            display: inline-block;
            margin: 20px 5px 0;
        }

        input[type=submit], input[type=reset] {
            width: 100%;
        }

        input[type=submit]:hover,
        input[type=reset]:hover,
        .btn-item:hover {
            background: #85d6de;
        }

        @media (min-width: 568px) {
            html, body {
                height: 100%;
            }

            .main-block {
                flex-direction: row;
                height: calc(100% - 50px);
            }

            .left-part, form {
                flex: 1;
                height: auto;
            }
        }
    </style>
</head>

<body>
    <div class="main-block">

        <form>
            <div class="title">
                <h2>
                    <span>Register here <ion-icon name="person-circle"></ion-icon></span>
                </h2>
            </div>

            <div class="info">
                <input type="text" name="fullname" placeholder="Full Name" required>
                <input type="text" name="email" placeholder="Email Address" required>
                <input type="text" name="phone" placeholder="Phone Number" maxlength="10">
                <input type="password" name="pwd" placeholder="Password" required>
            </div>

            <div class="checkbox">
                <input type="checkbox" name="agree" required>
                <span>Remember me</span>
            </div>

            <input type="submit" value="Submit">

            <br>

            <p style="text-align:left; font-size:10pt; color:#787CB5;">
                Designed by kaosuay
            </p>

        </form>
    </div>

    <!--  -->
    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>

</body>
</html>
