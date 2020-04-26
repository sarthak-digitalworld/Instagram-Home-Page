# Instagram-Home-Page
Created a Home page of Instagram by the help of Html and Css coding
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Instagram</title>
  <link rel="stylesheet" href="css/1.css"/>
  <link rel="icon" href="https://i.imgur.com/rQg7BPw.png" type="image/x-icon">
  <style>
      #cursive{
	     margin-top:27px;
       }

       #containers{
	     font-family:arial;
	     width:150px;
        }

      .ded{
	    display:flex;
	    width:auto;
	    height:500px;
	    text-align:center;
      }
 
      .ded{
        padding:0px 300px;
	    background-color:#fff
	    margin-bottom:50px;
      }	

     .ex{
	   border:1px solid lightgray;
	   height:auto;
	   width:100%px;
      }

     .scan{
	    height:10px;
	    padding-right:120px;
      }

     #image{
	    padding-right:40px;
	    width:80%;
     }

     #in hover{
	      background-color:skyblue;
      }

     #in{
	   text-align:center;
	   padding-left:40px;
     }

      .it{
	     margin-top:25px;
	     padding-left:35px;
       }

      #fb{
	    margin-top:25px;
      }

      #forgot{
	    padding-left:40px;
       }

      #acc {
	    margin-left:20px;
	     padding-left:20px;
      }

      #app{
	    padding-left:20px;
        }

      .column {
          float: left;
           width: 40%;
         padding: 5px;
      }

        .row::after {
           content: "";
          clear: both;
           display: table;
        }

      footer{
	    display:flex;
	      justify-content:space-around;
	     margin-top:280px;
       }

        #last{
	     text-align:center;
	      background-color:skyblue;
	      color:black;
        }
  </style>
 
 </head>
 <body>
     <nav class="ded">
         <div id="image">
             <img src="https://i.imgur.com/6gzOmhL.png"/>
         </div>
	     <header class="ex" >
             <div id="cursive">
                 <img src="https://i.imgur.com/em5WAkvt.jpg" alt="Instagram"/>
	         </div>
	         <br />
	         <br />
	         <div id="containers" class="scan" >
			 <ul>
		         <form method="post" action="process.php"/>
			         <label>Username :- </label>
				     <input></input>
				     <br />
				     <label> Password :- </label>
				     <input></input>
					 <br />
					 <br />
					 <div id="in">
					     <input type="submit" value="Log In" />
					 </div>
					 <div class="it">
					      <u><strong><em>OR</em></strong></u>
					 </div>
					 <div id="fb">
					     <img src="https://i.imgur.com/W9dbjOBt.jpg" alt="Facebook" />
						 
					 </div>
					 <div id="forgot">
					     <p>Forgot Password?</p>
					 </div>
					 <div id="acc">
					     <p>Don't have an account?Sign up</p>
					 </div>
					 <br />
					 <div id="app">
					      <p>Get the app.</p>
					 </div>
					 <div class="row">
                          <div class="column">
                               <img src="https://i.imgur.com/w0S5Xbgt.png" alt="Play store" style="width:100%">
                          </div>
                           <div class="column">
                             <img src="https://i.imgur.com/17A2Ab1t.png" alt="app store" style="width:100%">
                         </div>
					  </div>	 
		       </div>
          </header>  		  
     </nav>	  
	 <div>
	 <footer>
	      <p>About</p>
		  <p>Help</p>
		  <p>Press</p>
		  <p>Api</p>
		  <p>Jobs</p>
		  <p>Privacy</p>
		  <p>Terms</p>
		  <p>Locations</p>
		  <p>Top Accounts</p>
		  <p>Hastags</p>
		  <p>Language</p>
	</footer>
	<div id="last">
	   <p>Thanks for visiting!!!</p>
	   <p>Page Created by Sarthak Agrawal</p>
	</div>
 </body>
 </html> 
