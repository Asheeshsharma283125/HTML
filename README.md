//Lecture1 and Lecture2 (In which we learn b(bold),i(italic),u(Underline),p(paragraph) and h(heading) tags)
<html>
	<body>
		Hello World...<br>
		<b>Bold text</b>
		<i>Italic Text</i>
		<u>Underline Text</u>
		<h1>Heading H1</h1>
		<h2>Heading H2</h2>
		<p>Paragraph</p>
  </body>
</html>

//Lecture3 and Lecture4 and Lecture5(In which we learn hr(Horizontal Line) a(anchor) img(image) font tags)
<html>
	<body>
		<h1>Heading H1</h1>
		<hr>
		Contact us:8126228537
		<hr>
		<font size=30 color="red" face="verdana">Asheesh sharma</font>
		<a href="lecture2.html">Go to th next page</a>
		<img src="ayu.jpg" width="100" height="100" alt="Error">
		<a href="ayu.jpg"><img src="ayu.jpg" width="100" height="100" alt="Error"></a>
	</body>
</html>
//Lecture6 (In which we learn table,tr,td(table data),input tags)
<html>
	<body>
		<table border=3 bgcolor="yellow" align="center" width="50">
			<tr>
				<td>Number</td>
				<td>asheesh</td>
			</tr>
			<tr>
				<td>Rollno</td>
				<td>64</td>
			<tr>
			<tr>
				<td><input type="text"></td>
				<td><input type="text"></td>
			</tr>
		</table>
	</body>
</html>
// Lecture7
<html>
	<body>
		Username: <input type="text"><br>
		Password: <input type="password"><br>
		<input type="submit" value="Login">
		Gender: <input type="radio" name="r" checked>Male<br>
						<input type='radio' name='r1'>Female<br>
		Language: <input type="checkbox" name="r">English<br>
			<input type="checkbox" name="r1">Hindi<br>
		Address: <textarea></textarea><br>
						<input type="submit" value="Submit">
						<input type="reset">
	</body>
</html>
//lecture8
<html>
	<body>
		<center><embed src="my.mp4" alt="Error" width=100 height=100></center>   //old tag
		<video src="my.mp4" width=100 height=100 alt="Error" controls="controls" autoplay="autoplay" loop=3>     //new tag
		<audio src="my.mp3" autoplay controls>
		<bgsound src="my.mp3">
	</body>
</html>
//Lecture10
<html>
	<body>
		a<sup>2</sup>+b<sup>2</sup>=c<sup>2</sup><br>
		log<sub>10</sub>+log<sub>10</sub>=1<br>
		hello&nbsp;&nbsp;&nbsp;&nbsp;World
		<&lt>
			<&gt; &quot; &apos; &reg; a&laar;b
			      &uarr; &darr; &Delta; &Gamma;
			      </body>
			</html>
//lecture11
<html>
        <body>
                <form>
                select color<input type="color"><br>
                select date<input type="date"><br>
                select number<input type="number" min=1 max=10 step=1><br>
                Username: <input type="text"><br>
                Select Email<input type="email">
                URL<input type="URL">
                </form>
        </body>
                </html>
//lecture12
<html>
<body>
Department
<ul type="circle">
	<li>asheesh</li>
		<ol type="i">
			<li>noida</li>
		</ol>
	<li>aayushi</li>
		<ol type="i">
			<li>agra</li>
			
		</ol>
</ul>
</body>
</html>

//lecture13
<html>
    <head><title>Asheesh</title></head>
    <body>Meter <meter low = "30" "min ="10" max = "100" value = "20"></meter>
    Color is <del>Red</del></body>
</html>
	    
//lecture14
<! <!DOCTYPE html>
<html lang="en">
<head>
  
    <title>Document title</title>
</head>
<body>Asheesh sharma<br>
    Text formatting html tags<br>
    <em>Em Text format</em><br>
    <strong>Em Text format</strong><br>
    <code>Em Text format</code><br>
    <samp>Em Text format</samp><br>
    <kbd>Em Text format</kbd><br>
    <var>Em Text format</var><br>
    <tt>Em Text format</tt><br>
    this is <mark>red</mark> color
</body>
</html>

//lecture15
<html>
    <body>
        <fieldset style="width:300px;"><legend>Login form</legend><form>
        username<input type="text"><br>
        Passwoord<input type="password"><br>
        <input type="submit" value="login">
        </form></fieldset>
    </body>
</html>

//lecture16
<html>
    <body>
        <abbr title='this is Html'>HTML</abbr>
        <abbr title="this is PHP">PHP</abbr>
        <input list = "my">
        <datalist id="my">
            <option value="computer">
                <option value="informatio">
                    <option value ="mechanical">
                    </option>
                </option>
            </option>
           

    </body>
</html>

//lecture17
<html>
    <body>
        <details>
            <summary>show my detail</summary>
            <p>My name is asheesh </p>
        <p>Contact number</p>
    <p>Email address</p>
        </detail>
    </body>
</html>

//lecture18
<html>
    <body>
         <table border="2">
             <thead bgcolor="red">
                 <tr>
                     <td>Month</td>
                     <td>Saving</td>
                     </tr>
                     </thead>
            <tfoot>
                <tr>
                    <td>july</td>
                    <td>$100</td>
                </tr>
            </tfoot>
            <tbody>
                <tr>
                    <td>jan</td>
                    <td>$20</td>
                </tr>
            </tbody>

         </table>
    </body>
</html>

//lecture19
<html>
    <body>
        <img usemap="#map" src="ayu.jpg" width="600" height="500" border="3" alt="Error">
        <map name="map">
            <area shape="rect" coords="100,100,300,300" href="kach.jpg">
            <area shape="circle" coords="500,500,50" href="kahc.jpg">
            <area shape="poly" coords="200,200,300,300,200,400" href="kach">
            </map>
        </body>
        </html>
//lecture20
<html>
    <body>
        <table>
            <tr>
                <td><figure>
                    <img src="ayu.jpg" width="200" height="300" alt="Error">
                    <figcaption>
                        Figure 1 wonderful desert
                    </figcaption>
                    </figure></td>
                <td><figure>
                    <img src="ayu.jpg" width="200" height="300" alt="Error">
                    <figcaption>
                        Figure 2
                    </figcaption>
        
                </figure></td>
            </tr>
        </table>
        
        
        </body>
        </html>
	
//lecture21
<html>
    <body>
        <bdp dir="rtl">Hello World</bdp>
        <table border=2 align="center">
            <caption align="left">This is my table</caption>
            <tr>
                <td>asheesh</td>
                <td>64</td>
            </tr>
            <tr>
                <td>riya</td>
                <td>37</td>
            </tr>
        </table>
    </body>
</html>

//lecture22
<html><body><center>
    Hello Asheesh Sharma</center>
<hr color="red" width="300">
<center><a  href="Priyankafiles.docx" color=blue> Lession 1</a><br>
<a  href="lecture2.html" color="blue">Lession 2</a></center>
<hr color="red" width="300">
<br><br><br><br>
<hr noshade>
<marquee>Html in hindi Youtube channel..!</marquee>
<hr>

</body></html>

//lecture23
<html>
    <body>
        <pre >
            this is my book
            ok byy
            tell me one this
        </pre>
        <template>
            <img src="ayu.jpg">
        </template>

    </body>
</html>

//lecture24
<html>
    <body>
        <svg width="200" height="200">
            <circle cx="100" cy="100" r=80 stroke="black" stroke-width="5" fill="red"/>
            </svg>
            <svg width="200" height="200">
            <rect width="100" height="100" stroke="black" stroke-width="5" fill="red"/>
            </svg>
            <svg width="200" height="200">
                <line x1="2" y1="2" x2="50" y2="20" stroke="black" stroke-width="5"/>
            </svg>
        
    </body>
</html>

//lecture25
<html>
    <head>
        <style>
            pre{
                background-color:rgba(200, 221, 13, 0.863);
            }
            body{
                background-color:rgba(1, 17, 1, 0.932);
            }
         </style>
    </head>
    <body>
        <pre><b><i>Hey! i am asheesh 
Sorry for waiting</i></b>
            </pre>
    </body>
</html>

//lecture26
<html>
    <head>
        <style>
            p{
                background-color: pink;
            }
        </style>
    </head>
    <body>
        <p>Inline CSS</p>
        <p style="background-color:green">html</p>
	</body></html>


//lecture27
<html>
    <head>
        <link rel="stylesheet" type="text/css" href="CSS27.css">

    </head>
    <body>
<p> this is my book</p>
<h1>this is heading</h1>
    </body>
</html>

//lecture28
<html>
    <head>
        <style>
            p{
                background-color: green;
                color: pink;
            }
            #heading1{
                color:blueviolet;
            }
            #para1{
                text-align:center;
                color:pink;
                background:red;
            }
        </style>
    </head>

<body>
<p>
    hello
</p>
<h1 id="Heading1"></h1>
<p id="para1">asheesh sharma</p>
</body>
</html>

//lecture29
<html>
    <head>
        <style>
            .cen{
                background-color:red;
                
                text-align:center;

            }
            .style{
                color:pink;
            }

            </style>
    </head>
    <body> 
        <p class="cen">helllo world</p>
        <p class="cen">Asheesh</p>
        <h1 class="cen style" >Ashu</h1>
        <h4 class="cen" >Ashu</h4>
        <h2 class="cen">Rahul</h2>
        <h3 class="cen style" >TELL ME ABOUT YOURSELF</h4>
            
    </body>
</html>

//lecture30
<html>
    <head>
        <style>
                p,h1,h2{
                    color:red;
                    background-color:blue;
                    text-align:center;
                }
                #h1,#h2,#h3{
                    color:red;
                    background-color:blue;
                    text-align:center;
                }

                h1{
                    color:red;
                }
                h2{
                    color:red;
                }
        </style>
    </head>

    <body>
        <p>HTML Program</p>
        <h1>
            India
        </h1>
        <h2>Gujarat</h2>
    </body>

</html>

//lecture31
<html>
    <head>
        <style>
            div{
                width:175px;
                height:20px;
                background-color: lightblue;
                border-radius:20px;
            }
        </style>
    </head>
    <body>
        <table border=1>
            <tr>
                <td> 
                    <div><input list="my">
                        <datalist id=my>
                            <option value="Heloo">
                                Computer<br> 
                                <option value=Asheesh>
                                    IT Sector<br>
                </div>


                </td>
                <td> <div>
                    
                        Computer<br>
                        
        
                   
                    
                </div>

                </td>
            </tr>
        </table>
       
        </body>
</html>


//lecture32
<html>
    <head>
        <style>
            body{
                background-image: url("image2.jpg");
                background-repeat: no-repeat;  //repeat-x
                background-position: right top;
                background-attachment:fixed;
                background-color: lightgreen;
            }

        </style>

    </head>
    <body>

    </body>
</html>

//lecture33
<html>
    <head>
        <style>
            body{
                background-image:repeating-linear-gradient(to right, red 20%,green 30%);
                background-image:repeating-radial-gradient(circle, red 20%,green 30%);
                background-image:repeating-linear-gradient(70deg,blue, red 20%,green 30%);
            }
        </style>
    </head>
    <body>

    </body>
</html>
//lecture34
<html>
    <heaad>
        <style>
            p.p1{
                border-style:solid;
                border-color:red blue yellow pink;
                border-width:2px 10px 5px 25px;
            }
            p.p2{
                border-top-style:outset;
                border-bottom-style:solid;
                border-right-style:solid;
                border-left-style:outset;

            }
            p.p3{
                border-style:dashed ;
            }
            p.p4{
                border-style:double ;
            }
            p.p5{
                border-style:groove ;
            }
            p.p6{
                border-style:ridge ;
            }
            p.p7{
               
                border-right: solid 6px red ;

            }
            p.p8{
                border-style:outset ;
            }
        </style>
</heaad>
    <body>
<p class='p1'>Html and css in hindi</p>
<p class='p2'>Html and css in hindi</p>
<p class='p3'>Html and css in hindi</p>
<p class='p4'>Html and css in hindi</p>
<p class='p5'>Html and css in hindi</p>
<p class='p6'>Html and css in hindi</p>
<p class='p7'>Html and css in hindi</p>
<p class='p8'>Html and css in hindi</p>
    </body>

</html>

//lecture35
<html>
    <head>
        <style>
            div{
                width:200px;
                height:100px;
                border:5px outset ;
                background-color:lightblue;
                margin:30px 90px 79px 40px;
                padding:50px
            }
            input{
                margin:3px;
                padding:5px;
            }
            </style>

    </head>
    <body>
<div><b>
    Username:<input type="text"><br>
    Password:<input type="password"><br>
    <input type="submit" value=Login></b>
    
</div>
    </body>
</html>

//lecture36

