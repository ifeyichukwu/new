<!DOCTYPE html>
<html lang="en-us">
  <head>
    <style>
        *{
            margin: 0;
            padding: 0;
            background-color: whitesmoke;
        }
        header{
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            align-items: center;
            padding: 10px 10px 10px 10px;
            margin: 0 0;
            background-color: white;
            height: 60px;
            font-size: 12px;
        }

        ul li a .login{
            background-color: black;
            border-color: purple ;
            border: solid;



        }


        .logo{
            padding: 0 0;
            font-size: 30px;
            text-transform: lowercase;
            background-color: white;
            font-weight: bolder;
            font-family: arial, Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;

        }
        ul{
            list-style-type: none;
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            align-items: center;
            text-decoration: none;
            background-color: white;
            color: black;
            font-family:Arial, Helvetica, sans-serif ;
            margin: 0 0;
            padding:0 0;
            

        }

        .catsearch{
            padding: 0 30px;
            background-color: white;
            color: black;
            


        }

        ul li a{
            display: inline-block;
            justify-content: space-between;
            padding: 0 10px;
            text-decoration: none;
            background-color: white;
            color: black;

        }
        
        #search{
            height: 50px;
            border-radius: 30px;
            width: 40pc;
            background-color: whitesmoke;
            margin: 0 0;
            padding: 0 10px;
            
        }

        .content-left{
            margin: 10px 14px;
            width: 25%;
            font-size: larger;
            border: transparent;
            padding: 10px 30px 10px 10px ;
            background-color: white;
            background-blend-mode:darken;
        }
        
            
        
        .content-left p{
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }

        #promo{
        margin: 10px 10px 10px 5px;
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-items:flex-start;
        padding: 5px;
    }

        
        div img{ 
            width: 200px;
            height: 400px;
            margin: 0 0;
        }
    
     @media only screen and (max-width: 560px)   {
        header{background-color: gold;}
     }

    </style>
  </head>
  <body>
    <header>
        <div class="logo">Udemy</div>
        <nav>
            <ul>
                <a class="catsearch" href="#" style="text-decoration: none;">Categories</a>
                <input id="search" class="catsearch" type="text" placeholder="Search for anything"/>
           <li><a href="#">Udemy Business</a>  </li>
           <li ><a href="#">Teach on Udemy</a> </li>
           <li><a href="#">Cart</a> </li>
           <li class="login" style="background-color: black;
            border-color: purple ;
            border: solid;"><a href="#">Log In</a> </li>
           <li style="border-width: 60px; text-align: justify; border: solid;"><a href="#">Sign Up</a> </li>
           <li><a href="#">continentalsign</a> </li>


   
    </nav>
</ul>
</header>
<main>
    <div  id="promo">
<div   class="content-left">
    <h1 style="background-color: white;">New to Udemy? Lucky you.</h1>
    <p style="background-color: white;">Courses start at <del style="text-decoration-style: double;">N</del>3500. Get your new-student offer before it expires.</p>
</div>  

<div>
    <img src="clock.jpg" alt="a clock">
</div>
</div>
<div id="main-content">
<h1>A Broad  selection of Courses</h1>
<p>Choose from 213,000 online video courses with new additions published every month</p>
</div>
</main>
</body>
</html>
