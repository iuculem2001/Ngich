<!DOCTYPE html>
<html>
    <head>
        <title>
            đây là tiêu đề
        </title>
        <style>
            body {
              background-image: url('xivir pentakill.png');
              background-repeat: no-repeat;
              background-attachment: fixed;  
              background-size: 100%,100%;
            }
            h1 { margin-right: 100px;
            border-style: solid;
            border-radius: 5px;
            border-color: red;
            background-color:rgba(89, 0, 255, 0.74); }
            p {border-style: solid;
               border-color: red;
               border-radius: 5px;
               margin-right: 300px;}
        </style>
    </head>
    <body>
        <form action="">
            <h1 style="background-color:rgb(255, 255, 255);">Tính toán tiểu học</h1>
            a = <input id="xxxx" type="number">
            b = <input id="yyyy" type="number">
            <button type="button" onclick="tinhtong()">tinh tong</button>
            <p id="tong" style="background-color: rgba(0, 255, 200, 0.329);">nhập giá trị a và b:</p>
        </form>
        <script>
            function tinhtong(){
                var x = document.querySelector("#xxxx").value;
                var y = document.querySelector("#yyyy").value;
                x = parseFloat(x); 
                y = parseFloat(y);
                var tong = x + y;
                document.getElementById("tong").innerHTML = tong;
            }
        </script>
    
    </body>
</html>
