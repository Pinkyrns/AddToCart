# AddToCart

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Add to cart</title>

    <style>

        @import url('https://fonts.googleapis.com/css2?family=Aboreto&family=Open+Sans&family=PT+Sans&family=Poppins:ital,wght@1,500&display=swap');

        * {

            font-family: 'PT Sans', sans-serif;

            margin:23px;

            padding:0;

            box-sizing: border-box;

            outline: none;

            border: none;

            text-decoration: none;

            text-transform: capitalize;

            transition: .2s linear;

            border-radius: 6px;

        

            

        }

        .Container {

            background: linear-gradient(55deg, rgb(252, 252, 246), white);

            padding: 15px 9px;

            padding-bottom: 23px;

            display: grid;

            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));

            gap: 5px;

            overflow:auto;

            row-gap: -2px;

            border:1px solid beige;

            float:top;

        }

        .Container .Yellow-Cinthol {

            box-shadow: 2px 4px 5px 4px rgb(207, 197, 184);

            border-radius: 5px;

            background: white;

            text-align: center;

            padding: 30px 20px;

            width: 236px;

            height: 369px;

        

        }

        .Yellow-Cinthol img {

            height:px;

            width: 120px;

        }

        .Yellow-Cinthol{

            box-shadow:56px ;

        }

        .Yellow-Cinthol:hover{

transform: translateY(5px);

        }

        .btn{

            width: 100px;

            height: 33px;

            border:2px solid red;

            background-color:rgb(255, 254, 254);

            color:red;

            border-radius: 4px;

            letter-spacing: 2px;

        }

        .btn:hover{

        background-color: crimson;

        color:white;

        box-shadow: 0 10px 15px;

        transform: scale(1.03);

        letter-spacing: 2px;

        }

        .rupee{

            width:13px;

            height:23 px;

            padding: 0;

            margin: 0;

          }

          @media(max-width:545px)

          {

              .Container{

                  padding: 20px;

              }

          }

          b{

              letter-spacing: 1px;

          }

          

    </style>

</head>

<body>

    <div class="Container">

        <div class="Yellow-Cinthol">

            <img src="Yellow-cinthol.jpg" class="  " alt="">

            <b>Godrej Cinthol<br>Lime Soap  75*3<br><span>114.00</span></b>

        

            <button class="btn">Add</button>

        </div>

        <div class="Yellow-Cinthol">

            <img src="Blue cinthol.jpg" class=" " alt="">

            <b>Godrej Cinthol Cool <br> Soap 75*3gm<br> <span>98.00</span></b><br>

            <button class="btn"> Add </button>

        </div>

        <div class="Yellow-Cinthol">

            <img src="Yellow-cinthol.jpg" class=" " alt="">

            <b>Godrej Cinthol<br>Lime Soap 100*4<br><span>150.00</span></b>

            <button class="btn">Add</button>

        </div>

        <div class="Yellow-Cinthol">

            <img src="Yellow-talc.webp" class=" " alt="" width="110px" height="174px">

            <b>Cinthol talc Lime<br>300g<br><span>130.00</span></b>

            <button class="btn">Add</button>

        </div>

        <div class="Yellow-Cinthol">

            <img src="Red talc.jpg" class=" " alt="">

            <b>Cinthol Talc<br>Original 100gm<br><span>54.00</span></b><br><br>

            <button class="btn">Add</button>

        </div>

        <div class="Yellow-Cinthol">

            <img src="Blue talc.jpg" class=" " alt="">

            <b>Cinthol Cool Talc<br>100 G<br><span>53.00</span></b>

            <button class="btn">Add</button>

        </div>

    </div>

</body>

</html>
