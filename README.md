# Calculadora
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora</title>
    <style>
        *{
            margin: 0;
            padding: 0;

        }
        .fundo{
            background-image:linear-gradient(45deg,rgb(14, 4, 4), rgb(185, 26, 26));
            height: 100vh;
            color:rgb(216, 204, 204);
            font-family: arial,Arial, Helvetica, sans-serif;
            text-align: center;
        }
        
        .Calculadora{
            position: absolute;
            background-color: rgba(0, 0, 0, 0.8);
            top: 50%;
            left: 50%; 
            transform: translate(-50%,-50%);
            border-radius: 15px;
            padding: 15px;
        }

            .botão{
                width: 50px;
                height: 50px;
                font-size: 25px;
                cursor: pointer;
                margin: 3px; 
                background-color:rgb(61, 45, 45);
                border: none;
                color:antiquewhite;
                   

            }
            .botão:hover{
                background-color: black;
            }
            #resultado{
                background-color: white;
                width: 207px; 
                height: 30px; 
               
                font-size: 25px;
                color: rgb(201, 72, 72); 
                text-align: right;
                
              
            }
    </style>
</head>
<body>
    
    <div class="fundo">
        <h1>Isaias Carlos</h1>
        <div class="Calculadora">
        <h1>Calculadora</h1>
        <p id="Resultado">Resultado</p>
        
        
    
        <table>
            
             <tr>
                <tr><button class="botão">C</button></button></tr>
                <tr><button class="botão"><</button></tr>
                <tr><button class="botão">/</button></tr>
                <tr><button class="botão">X</button></tr>
             </tr>
                <hr>
             <tr>
                 <tr><button class="botão">7</button></tr>
                 <tr><button class="botão">8</button></tr>
                 <tr><button class="botão">9</button></tr>
                 <tr><button class="botão">-</button></tr>
            </tr>
                <hr>
                    <tr>
                <tr><button class="botão">4</button></tr>
                <tr><button class="botão">5</button></tr>
                <tr><button class="botão">6</button></tr>
                <tr><button class="botão">+</button></tr>
            
            </t>

                <hr>
                    <tr>
                 <tr><button class="botão">1</button></tr>
                 <tr><button class="botão">2</button></tr>
                 <tr><button class="botão">3</button></tr>
                 <td rowspan="2"><button class="botão" style="width: 106px;">0</button></td>
                
                </tr>   
                    <tr>
                    
                <td colspan="2"><button class="botão" style="width:106px;">=</button></td>
                <tr><button class="botão">.</button></tr>
                
            </table>
        </div>
    </div>
</body>

</html>
