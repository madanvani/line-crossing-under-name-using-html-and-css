# line-crossing-under-name-using-html-and-css

#HTML:=

     <!DOCTYPE html>
<html>

<head>
      <link rel="stylesheet" href="madan.css">
</head>
<body>
<input type="text" class="text" placeholder="MADAN"/>
    </body>



    </html>
    
    #CSS:=
    
       .text{
    background-image: 
    linear-gradient(
        transparent 0%,
        transparent 90%,
        hotpink 90%,
       rgb(15, 102, 22)
    );
 background-repeat: no-repeat;
 background-size: 0% 100%;
 background-position-x: 300ms;
 transition: background-size 300ms;
 color: aqua;
 width: 200px;

 margin-left: 330px;
 padding: 25px;
 border-radius: 15px;
}
.text:hover{
    background-size: 100% 100%;
    background-position-x: left;
}



