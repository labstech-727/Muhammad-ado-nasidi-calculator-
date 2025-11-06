<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>calculator</title>
    <link rel="stylesheet" href="STYLE.CSS">
</head>
  <style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
    background-color: rgb(142, 105, 105);
    color: white;
     align-content:center;
    justify-content: center;

}

.container{
    width: 100%;
    height: 100vh;
    background-color: rgb(142, 105, 105);
    color: brown;
    display: flex;
    align-content:center;
    justify-content: center;
    h1,h3,h4 {
        text-align: center;
    }
}
.calculator{
    background-color: white;
    border-radius: 10px;
    border: 1px solid grey;
    padding: 30;
    margin-top: 30px;
    margin-bottom: 190px;
}
.calculator form input{
border: none;
outline: 0;
width: 60px;
height: 60px;
border-radius: 10px;
margin: 3px;
font-size: 17px;
color: rgb(244, 235, 235);
background-color: rgb(40, 40, 53);
cursor: pointer;
}
.calculator form .display{
    display: flex;
    margin: 5px 0px 15px 0px;
    justify-content: center;
}
.calculator form .display{
    text-align: right;
    flex: 1;
    font-size: 20px;
    background-color: rgb(41, 41, 50);
    border-radius: 10px;
    margin: 10px;
}
form  input.equal{
    width: 130px;
    font-size: 30;
}
.calculator form input[type="button"]:active{
    background-color: aqua;

}
  </style>
<body>
     <h1>ND IIA COMPUTER SCIENCE GROUP B CALCULATOR 2023/2024</h1>
    <div class="container">
        <div class="calculator">
           <h3>CALCULATOR</h3>
            <form action="">
                <div class="display">
                    <input type="text"name="display">
                </div>
                <div>
                     <input type="button"value="reset"onclick="display.value=''">
                      <input type="button"value="DEL"onclick="display.value=display.value.toString().slice(0,-1)">
                       <input type="button"value="."onclick="display.value +='.'">
                        <input type="button"value="/"onclick="display.value +='/'">
                </div>
                  <div>
                     <input type="button"value="7"onclick="display.value +='7'">
                      <input type="button"value="8"onclick="display.value +='8'">
                       <input type="button"value="9"onclick="display.value +='9'">
                        <input type="button"value="*"onclick="display.value +='*'">
                </div>
                  <div>
                     <input type="button"value="4"onclick="display.value +='4'">
                      <input type="button"value="5"onclick="display.value +='5'">
                       <input type="button"value="6"onclick="display.value +='6'">
                        <input type="button"value="-"onclick="display.value +='-'">
                </div>
                  <div>
                     <input type="button"value="1"onclick="display.value +='1'">
                      <input type="button"value="2"onclick="display.value +='2'">
                       <input type="button"value="3"onclick="display.value +='3'">
                        <input type="button"value="+"onclick="display.value +='+'">
                </div>
                  <div>
                     <input type="button"value="0"onclick="display.value +='0'">
                      <input type="button"value="00"onclick="display.value +='00'">
                       <input type="button"class="equal"value="="onclick="display.value=eval(display.value)">
                       
                </div>
                
            </form>
        </div>
    </div>
 <h4>   AUWAL BUSIRI SALISU         ND/COM/23/0086 <br>
FARUK DAUDA SALISU           ND/COM/23/0132 <br>
MUHAMMAD ADO NASIDI          ND/COM/23/0014 <br>
IBRAHIM SANI IBRAHIM         ND/COM/23/0169 <br>
MA ARUF MA ARUF              ND/COM/23/0175 <br>
YUSUF SULAIMAN MUSA          ND/COM/23/0206 <br>
SANI SULAIMAN ISHAQ          ND/COM/23/0082 <br>
LAWAN IBRAHIM                ND/COM/23/0227 <br>
MUHAMMAD AUWAL ISHAQ         ND/COM/23/0033 <br>
HAMZA ADAMU ALIYU            ND/COM/23/0164 <br>
MAHMUD USMAN                 ND/COM/23/0047 <br>
     Kabir muktar            ND com 23/0207 <br>
</h4> 
</body>

</html>
