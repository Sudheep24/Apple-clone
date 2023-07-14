<!DOCTYPE html>

<html>
<head>

    <title>login</title>
    <link href="login.css" rel="stylesheet" />
    <script src="https://kit.fontawesome.com/56f8f15525.js" crossorigin="anonymous"></script>
</head>
<body>
    <section>
        <div class="form-box">
            <div class="form-value">
                <form class="login_form" action="apple.html" method="post" name="form" onsubmit="return validated()">
                    <h2>Login</h2>
                    <div class="inputbox">
                        <ion-icon name="mail-outline"></ion-icon>
                        <input type="email" name="email" required />
                        <label for="" >Email</label>
                    </div>
                    <div class="inputbox">
                        <ion-icon name="lock-closed-outline"></ion-icon>
                        <input type="password" name="password " required />
                        <label for=" ">Password</label>
                       
                        <button>Login</button>
                        <div class="register">
                            <p>Don't have a acoount</p>
                        </div>
                    </div>
                </form>
            </div>
        </div>
    </section>
    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>
    <script src="valid.js"></script>
</body>
</html>
