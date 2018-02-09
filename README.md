<!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
	<link href="https://fonts.googleapis.com/css?family=Lato:400,700" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css?family=Open+Sans:400,600" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css?family=Comfortaa:400,700" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css?family=Abel" rel="stylesheet">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
	<script>
	$(document).ready(function(){
	  $("a").on('click', function(event) {
	    if (this.hash !== "") {
	      event.preventDefault();
	      var hash = this.hash;
	      $('html, body').animate({
	        scrollTop: $(hash).offset().top
	      }, 800, function(){

	        window.location.hash = hash;
	      });
	    }
	  });
	});
	</script>
	<style type="text/css">
		#content {
			text-align:center;
			padding:10%;
		}
		body{
			width:100%;
			height:100%;
		}
		hr {

		    height: 2px;
		    width:800px;
		    color: white;
		    border-top: 1px solid #f8f8f8;
		    border-bottom: 1px solid rgba(0,0,0,0.1);
		}
		html, body{
			height:100%;
			width:100%;
		}
		#kost{
			height:30px;
			width:7.5px;
		}
		.sect{
			height: 100%;
			background-size: cover;
			background-repeat: no-repeat;
			background-attachment: fixed;
		}
		.sectOne{
			background: url(https://www.retailnews.asia/wp-content/uploads/2017/01/Game-Developper.jpg);
			background-attachment:fixed;
		}
		#content1{
			color:white;
			font-family:Lato;
			font-weight:700;
			font-size:4em;
			text-shadow:0px 4px 3px rgba(0,0,0,0.4);
			            0px 8px 13px rgba(0,0,0,0.1),
			            0px 18px 23px rgba(0,0,0,0.1);
		}
		#content2{
			color:white;
			font-family:Lato;
			font-weight:400;
			font-size:1.5em;
			text-shadow:0px 4px 3px rgba(0,0,0,0.4);
			            0px 8px 13px rgba(0,0,0,0.1),
			            0px 18px 23px rgba(0,0,0,0.1);
		}
		.subSect1{
			background-color:#F0F8FF;
			height:100%;
			width:100%;
			padding-top:60px;
			padding-left:55px;
		}
		h1.helv{
			text-align:center;
			font-weight:700;
			font-family:Lato;
			font-size:3em;
			padding-right:60px;
			text-shadow:0px 4px 3px rgba(0,0,0,0.2);
			            0px 8px 13px rgba(0,0,0,0.1),
			            0px 18px 23px rgba(0,0,0,0.1);
		}
		.sectTwo{
			height:95%;
			width:100%;
			background-image:url(https://vignette.wikia.nocookie.net/fantendo/images/4/43/Mario_Bros_Map.jpg/revision/latest?cb=20140504182518);
			background-size:cover;
			background-repeat:no-repeat;
			padding-top:40px;
		}
		table.jk{
			margin-right:auto;
			margin-left:auto;
			margin-top:auto;
			margin-bottom:auto;
			font-family:Abel;
			font-weight:400;
		}
		h3.helv1{
			font-size:1em;
			font-weight:bold;
		}
		h1.helv2{
			font-family:Lato;
			font-weight:700;
			text-align:center;
			font-size:4em;
			color:	#FFF0F5;
			padding-top:50px;
			text-shadow:0px 4px 3px rgba(0,0,0,0.4);
			            0px 8px 13px rgba(0,0,0,0.1),
			            0px 18px 23px rgba(0,0,0,0.1);

		}
		.hln {
		    border-radius: 25px;
		    border: 7.5px solid #73AD21;
		    padding: 20px; 
		    width: 1000px;
		    height: 137.5px;
		    margin-right:auto; 
		    margin-left:auto;
		    margin-bottom:auto;
		    margin-top:40px;
		    color:#FFF0F5;
		    text-shadow:0px 4px 3px rgba(0,0,0,0.3);
			            0px 8px 13px rgba(0,0,0,0.1),
			            0px 18px 23px rgba(0,0,0,0.1);
		}
		.subSect2{
			height:120%;
			width:100%;
			background-color:#F0F8FF;
			padding-top:80px;
		}
		.box{
			border: 12px solid black;
		    padding: 20px; 
		    width: 500px;
		    height: 150px;
		    margin-right:auto;
		    margin-left:auto;
		    margin-bottom:auto;
		}
		h1.helv4{
			text-align:center;
			font-weight:bolder;
			font-size:3.5em;
			margin-bottom:30px;
			color:black;
		}
		.hn{
			margin:auto;
			padding-top:40px;
			padding-left:330px;
		}
		td.jk1{
			padding-bottom:60px;
		}
		table.jk2{
			margin-right:auto;
			margin-left:auto;

		}
		hr.jk22{
			width:100%;
		}
		.subSect3{
			width:100%;
			height:22%;
			background-color:#2F4F4F;
			padding-top:30px;
			text-align:center;
			font-size:0.9em;
		}
		p.jk3{
			padding-top:5px;
		}
		.esh{
			margin-left:250px;
	</style>
	<title>JiTest</title>
</head>
<body>
	<nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
		  	<a class="navbar-brand" href="#"><img src="https://jtcanvasprints.com/wp-content/uploads/2015/11/jt.png" width='35' height='35'>
		  	</a>
		  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
		    <span class="navbar-toggler-icon"></span>
		  </button>

		  <div class="collapse navbar-collapse" id="navbarSupportedContent">
		    <ul class="navbar-nav mr-auto">
		      <li class="nav-item active">
		        <a class="nav-link" href="#content">Home</a>
		      </li>
		      <li class="nav-item">
		        <a class="nav-link" href="#subSect1">Latest Achievments</a>
		      </li>
		      <li class="nav-item">
		        <a class="nav-link" href="#sectTwo">About</a>
		      </li>
		      <li class="nav-item">
		        <a class="nav-link" href="#subSect2">Contact</a>
		      </li>
		    </ul>
		    <ul class='nav navbar-nav navbar-right'>
		    	<li class="nav-item">
		        	<a class="nav-link" href="#" data-toggle='modal' data-target='#popUpwindow1'>Join Us</a>
		       	</li>
		       	<li class="nav-item">
		        	<a class="nav-link" href="#" data-toggle='modal' data-target='#popUpwindow'>Login</a>
		       	</li>
		    </ul>   	
	      </div>
	</nav>
<div class='modal fade' id='popUpwindow'>
	<div class='modal-dialog'>
		<div class='modal-content'>
			<div class='modal-header'>
				<button type='button' class='close' data-dismiss='modal'>&times;</button>
			</div>	
			<div class='modal-body'>
				<form role='form'>
					<div class='form-group'>
						<input type='email' class='form-control' placeholder='Email'>
					</div>	
					<div class='form-group'>
						<input type='password' class='form-control' placeholder='Password'>
					</div>
				</form>		
			</div>	
			<div class='modal-footer'>
				<button class='btn btn-primary btn-block'>Log in</button>
			</div>	
		</div>
	</div>
</div>
<div class='modal fade' id='popUpwindow1'>
	<div class='modal-dialog'>
		<div class='modal-content'>
			<div class='modal-header'>
				<button type='button' class='close' data-dismiss='modal'>&times;</button>
			</div>	
			<div class='modal-body'>
				<form>
				  <div class="form-row">
				    <div class="form-group col-md-6">
				      <label for="inputEmail4">Email</label>
				      <input type="email" class="form-control" id="inputEmail4" placeholder="Email">
				    </div>
				    <div class="form-group col-md-6">
				      <label for="inputPassword4">Password</label>
				      <input type="password" class="form-control" id="inputPassword4" placeholder="Password">
				    </div>
				  </div>
				  <div class="form-group">
				    <label for="inputAddress">Address</label>
				    <input type="text" class="form-control" id="inputAddress" placeholder="1234 Main St">
				  </div>
				  <div class="form-group">
				    <label for="inputAddress2">Address 2</label>
				    <input type="text" class="form-control" id="inputAddress2" placeholder="Apartment, studio, or floor">
				  </div>
				  <div class="form-row">
				    <div class="form-group col-md-6">
				      <label for="inputCity">City</label>
				      <input type="text" class="form-control" id="inputCity">
				    </div>
				    <div class="form-group col-md-4">
				      <label for="inputState">State</label>
				      <select id="inputState" class="form-control">
				        <option selected>Choose...</option>
				        <option>...</option>
				      </select>
				    </div>
				    <div class="form-group col-md-2">
				      <label for="inputZip">Zip</label>
				      <input type="text" class="form-control" id="inputZip">
				    </div>
				  </div>
				</form>
			</div>	
			<div class='modal-footer'>
				<button class='btn btn-primary btn-block'>Sign Up</button>
			</div>	
		</div>
	</div>
</div>				

	<div class="sect sectOne" id='content'>
		<div id='content1'
			<h1>JiTest</h1>
		</div>	
		<div id='content2'>
			<h3>Welcome to the world's most reputable Game Testing platform!</h3>
		</div>	
		<hr>
		<button type="button" class="btn btn-primary btn-lg" data-toggle='modal' data-target='#popUpwindow1'>Become a JiTester!</button>
	</div>	
	<div  class='subSect1' id='subSect1'>
		<h1 class='helv' id='helv'>Latest Achievments</h1>
		<table cellpadding='55px' class='jk'>
			<tr>
				<td>
					<p>
						<img src='http://www.sticker.com/picture_library/product_images/award-ribbons/72430_1st-first-place-award-ribbon-stickers-and-labels.png' height='250px' width='250px'>
					</p>
					<h3 class='helv1'>1st place in Geneva Testing Masters (GTM)</h3>	
				</td>	
				<td>
					<p>
						<img src='http://www.homerunderbyus.com/images/2nd.png' height='250px' width='250px'>
					</p>
					<h3 class='helv1'>2nd place in Indian's Gamers Lounge (IGL)</h3>	
				</td>
				<td>
					<p>
						<img src='https://www.sticker.com/picture_library/product_images/award-ribbons/72440_3rd-third-place-award-ribbon-stickers-and-labels.png' height='250px' width='250px'>
					</p>
					<h3 class='helv1'>3rd place in World's Game Testing Olympics (WGTO)</h3>
				</td>
			</tr>
		</table>			
	</div>
	<div class='sect sectTwo' id='sectTwo'>
		<h1 class='helv2'>About Us</h1>
		<div class='hln'><h3 class='helv3'>JiTest is one of the most powerful Game Testing platforms world wide, you get to develop your games and we rate your progress magnitude!
		</h3></div>
	</div>
	<div class='subSect2' id='subSect2'>
		<div class='box'><h1 class='helv4'>GET IN TOUCH!
		</h3></div>
		<div class='hn'>
			<table cellpadding='10px'>
				<td class='jk1'>
					<p>500 Terry Francois Street San Francisco, CA 94158</p>
					<p>info@mysite.com</p>
					<p>Tel:1 23-456-789</p>
					<p>OPENING HOURS:</p>
					Mon - Fri: 7am - 10pm
					<br>
					Saturday: 8am - 10pm
					<br>
					Sunday: 8am - 11pm
				</td>
				<td>
					<p>
						<input class="form-control form-control-sm" type="text" placeholder="Name">
					</p>
					<p>
						<input class="form-control form-control-sm" type="text" placeholder="Email">
					</p>
					<p>
						<input class="form-control form-control-sm" type="text" placeholder="Subject">
					</p>
					<p>
						<div class="form-group">
	    					<label for="exampleFormControlTextarea1"</label>
	   						<textarea class="form-control" id="exampleFormControlTextarea1" placeholder="Message" rows="4" width='200px'></textarea>
	  					</div>
	  				</p>		

	  			</td>		
	  		</table>
	  		<button type="button" class="btn btn-dark esh">Send</button>
	  	</div>				
	</div>
	<div class='subSect3'>
		<table class='jk2' cellpadding='7px'>
	  		<td>
	  			<a href='https://www.facebook.com/JiTest'> <img src='https://www.tapwithbrad.com/wp-content/uploads/2015/06/Facebook-Black-Circle-Icon.png'  height='30px' width='30px'></a>
	  		</td>
	  		<td>	
	  			<a  href='https://www.twitter.com/JiTest'><img src='http://www.pvhc.net/img149/osripvlnhbutiakubpzp.png' height='30px' width='30px'></a>
	  		</td>
	  		<td>
	  			<a  href='https://www.pinterest.com/JiTest'><img src='http://sguru.org/wp-content/uploads/2018/01/instagram-logo-A807AD378B-seeklogo.com_.png' height='30px' width='30px'></a>
	  		</td>
	  	</table>
	  	<p class='jk3'>© 2018 by Ahmad Ashraf</p>		
	</div>	
	<script
  src="http://code.jquery.com/jquery-3.3.1.min.js"
  integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8="
  crossorigin="anonymous"></script>
    <script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
</body>
</html>
