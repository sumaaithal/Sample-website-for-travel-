# Sample-website-for-travel-
A sample website which uses HTML5 and CSS3 scripting language for beautifying the website. It just displays the type of hotels and destination for traveling. However, there is no functionality to it.
#here is the code to a project:
<!DOCTYPE html>
	<html>
		<head>
			<title>final-project</title>
			<style>
				body{
					background-image:url("airbnb.png");
					background-size:1400px 800px;
					background-repeat:no-repeat;
				}
				nav{

					height:30%;
					width:auto;
				}
				nav ul li a{
					color:white;
					text-decoration:none;
				}
				nav ul li{
					list-style:none;
					float:right;
					padding-right:30px;
					font-size:20px;
				}
				li a:hover{
					text-decoration:underline;
			}
			  .section-left {
				float:right;
				height:600px;
				width:450px;
				background:white;
				margin-top:90px;
				margin-left:50px;
				font-size:40px;
				color:1px,solid black;
				font-family:verdana; 
				border-radius:10px;
			}
			.section-left form p{
				margin-top:10px;
			}
			form label{
				font-size:15px;
				padding-left:40px;
				margin-right:80px;
				text-shadow:2px 2px 4px lightgray;
			}
			form input{
				width:30%;
				height:30%;
				margin-left:40px;
				border-radius:5px;
				
			}
			form select{
				width:30%;
				height:10%;
				margin-left:40px;
				border-radius:5px;
				
			}
			form button{
				width:100px;
				height:50px;
				margin-left:300px;
				border-radius:5px;
				background:red;
			}
			.article{
				width:100%;
				height:200px;
				background:white;
				float:right;
				margin-top:110px;
			}
			.article h1{
				padding-left:80px;
			}
			.article ul li img{
				width:160px;
				height:120px;
				border-radius:5px;
				box-shadow:10px 10px 5px lightgray;
			}
			.article ul li {
				list-style:none;
				float:left;
				padding-left:40px;
				padding-right:80px;
			}
			.article ul li a{
				text-decoration:none;
				color:black;
				font:20px arial;
			}
			.article-one
			{
				width:100%;
				height:400px;
				background:white;
				margin-left:80px;
				font-size:18px;
				margin-top:30px;
				float:right;
			}
			.article-one a
			{
				text-decoration:none;
				color:black;
			}
			.article-one ul li
			{
				list-style:none;
				float:left;
				padding-right:30px;
			}
			.article-one ul p
			{
				padding-left:40px;
			}
			.article-one ul li img
			{
				border-radius:5px;
				width:150px;
				height:160px;
				padding-left:40px;
			}
			.article-one ul a
			{
				text-decoration:none;		
				color:black;
			}
			.article-one li#bg-gray a:hover
			{
				margin-top:10px;
				background:lightgrey;
				border-radius:5px;
				text-decoration:underline;
			}
			.article-one li#bg-gray
			{
				padding-left:40px;
				margin-top:30px;
			}
			.article-two
			{
				width:100%;
				height:780px;
				background:white;
				margin-left:80px;
				font-size:18px;
				margin-top:80px;
				float:right;
			}
			.article-two a
			{
				text-decoration:none;
				color:black;
			}
			.article-two ul li
			{
				list-style:none;
				float:left;
				padding-right:30px;
			}
			.article-two ul li img
			{
				border-radius:5px;
				width:250px;
				height:190px;
				padding-left:40px;
			}
			.article-two ul p
			{
				padding-left:40px;
			}
			.article-two ul li a
			{
				text-decoration:none;
				color:black;
			}
			.article-two > ul li p.lightgrey
			{
				color:darkgrey;
			}	
			.article-two ul li#show
			{
				text-decoration:underline;
				padding-left:40px;
			}
			.popular-destinations
			{
				width:100%;
				height:300px;
				background:white;
				margin-left:40px;
				font-size:18px;
				margin-top:80px;
				float:left;
			}
			.popular-destinations ul li a
			{
				text-decoration:none;
				color:black;
			}
			.popular-destinations ul li p
			{
				color:darkgrey;
			}
			.popular-destinations ul li
			{
				list-style:none;
				float:left;
				padding-right:100px;

			}
			.popular-destinations > ul li p.lightgray
			{
				color:darkgrey;
			}
			.featured-destinations
			{
				width:100%;
				height:380px;
				background:white;
				margin-left:40px;
				font-size:18px;
				margin-top:30px;
				float:left;
			}
			.featured-destinations ul li
			{
				list-style:none;
				float:left;
				padding-right:80px;
			}
			.featured-destinations ul li img
			{
				border-radius:5px;
				width:250px;
				height:190px;
				padding-left:5px;
			}
			.featured-destinations p.purplish
			{
				padding-left:5px;
				color:#7F525D;
			}	
			.featured-destinations ul li a
			{
				text-decoration:none;
				color:black;
			}	
			.featured-destinations ul li#grey-bg:hover
			{
				background:lightgrey;
				border-radius:5px;
			}
			.superhost
			{
				width:100%;
				height:750px;
				background:white;
				margin-left:40px;
				font-size:18px;
				margin-top:80px;
				float:left;
			}
			.superhost a
			{
				color:black;
				text-decoration:none;
			}		
			.superhost ul li
			{
				list-style:none;
				float:left;
			}
			.superhost ul li a:hover
			{
				text-decoration:none;
			}
			.superhost ul li a img
			{
				width:200px;
				height:190px;		
				border-radius:5px;
				padding-right:120px;
			}
			.superhost ul li#shownext:hover
			{
				text-decoration:underline;
			}
			.superhost ul li#shownext>a
			{
				color:white;
			}	
			.unique-places
			{
				width:100%;
				height:450px;
				background:white;
				margin-left:40px;
				font-size:18px;
				margin-top:80px;
				float:left;
			}
			.unique-places ul li
			{
				list-style:none;
				float:left;
			}
			.unique-places ul li a
			{
				text-decoration:none;
				color:black;
			}
			.unique-places ul li a p.bg
			{
				color:darkgrey;
			}
			.unique-places ul li img
			{
				border-radius:5px;
				width:300px;
				height:200px;
				padding-right:120px;
			}
			.foot
			{
				width:100%;
				height:250px;
				background:white;
				margin-left:40px;
				font-size:18px;
				margin-top:80px;
				float:left;
			}
			.foot hr
			{
				width:95%;
				margin-left:5px;
				margin-right:auto;
				opacity:0.5;
				background:#ffff;
			}
			.foot ul li
			{
				list-style:none;
			}
			.foot ul li a
			{
				text-decoration:none;
				color:black;
			}
			.foot ul,ul#f1,ul#f2,ul#f3
			{
				float:left;
				padding-right:90px;
			}
			.foot ul li a:hover
			{
				text-decoration:black underline;
			}
			.foot2
			{
				width:100%;
				height:250px;
				background:white;
				margin-left:40px;
				font-size:18px;
				margin-top:50px;
				float:left;
			}
			.foot2 hr
			{
				width:95%;
				margin-left:5px;
				margin-right:auto;
				opacity:0.5;
				background:#ffff;
			}
			.foot2 ul li
			{
				list-style:none;
			}
			.foot2 ul#f4 li
			{
				float:left;		
				padding-right:10px;
			}
			.foot2 ul#f4 a
			{
				color:black;
			}
			.foot2 ul#f5 li
			{
				padding-left:10px;
				float:right;
			}
			.foot2 ul#f5 li a
			{
				text-decoration:none;	
			}
			</style>
		</head>
		<body>
			<nav>
				<ul>
					<li><a href="goto.html">login</a></li>
					<li><a href="goto.html">Sign Up</a></li>
					<li><a href="goto.html">Help</a></li>
					<li><a href="goto.html">Host an Experience</a></li>
					<li><a href="goto.html">Host Home</a></li>
					<li><a href="goto.html">&#8377; INR</a></li>
					<li><a href="goto.html">English</a></li>
				</ul>
			</nav>
			<section class="section-left"> 
			 	<form action="/form_action.php">
					<p style="padding-left:20px;text-shadow:2px 2px 4px #000000;" >Book unique places to
					stay and do unique things</p>
					<label for="where">WHERE</label>
					<br>
					<input type="text" id="where" placeholder="anywhere"><br>
					<label for="check-in">CheckIn</label>
					<label for="check-out">CheckOut</label>
					<input type="date" id="check-in" placeholder="dd/mm/yyyy">
					<input type="date" id="check-out" placeholder="dd/mm/yyyy">
					<label for="guests">Guests</label>
					<br>
					<select id="guests" name="guests">
						<option value=" ">guests</option>
						<option value="adults">adults</option>
						<option value="children">children</option>
						<option value="infants">infants</option>
					</select>
					<br>	
					<button id="search" name="button">search</button>		
				</form>
			</section>
			<article class="article">
				<h1>Explore AirBnb</h1>
				<ul>
					<li><a href="/goto.html"><img src="stays.jpg">Stays>></a></li>
					<li><a href="/goto.html"><img src="experience.jpg">Experience>> </a></li>
					<li><a href="/goto.html"><img src="adventure.jpg">Adventure>> </a></li>
				</ul>
			</article>
			<article class="article-one">
				<a href="/goto.html"><h2 style="padding-left:80px;text-shadow:2px 2px 4px lightgrey">Introducing Airbnb Adventures</h2>
				<p style="padding-left:80px;">Muti-day trips led by local experts-activities,meals and stays included &gt;</p></a>
				<ul>
					<li><a href="/goto.html"><img src="one.jpg">
					<p>Ghost towns and Saloons</p>
					<p>&#8377;45,789/Person</p>
					<p>&#10025;&#10025;&#10025;(13)</p></a></li>

					<li><a href="/goto.html"><img src="two-norway.jpg">
					<p>MystificMansauhsen Island</p>
					<p>&#8377;50,000/Person</p>
					<p>&#10025;&#10025;&#10025;&#10025;&#10025;(3,190)</p></a></li>

					<li><a href="/goto.html"><img src="three-morocco.jpg">
					<p>Enchanting Maze of Souks</p>
					<p>&#8377;70,000/Person</p>
					<p>&#10025;&#10025;&#10025;(110)</p></a></li>

					<li><a href="/goto.html"><img src="kenya.jpg">
					<p>The lakehouse Tigoni</p>
					<p>&#8377;56,000/Person</p>
					<p>&#10025;&#10025;(46)</p></a></li>

					<li><a href="/goto.html"><img src="indonesia.jpg">
					<p>Koziyu Living Area</p>
					<p>&#8377;15,890/Person</p>
					<p>&#10025;&#10025;&#10025;(60)</p></a></li>

					<li id="bg-gray"><a href="/goto.html">Show all adventures ></a></li>
				</ul>
			</article>


			<article class="article-two">
				<a href="/goto.html"><h2 style="padding-left:80px;text-shadow:2px 2px 4px lightgrey">Places to Stay Around The World</h2></a>
				<ul>
					<li><a href="/goto.html"><img src="zeist-netherland.jpg">
					<p class="lightgrey">Netherland</p>
					<p>Zeist-Netherland</p>
					<p>From &#8377;25,789/Person(4Days)</p>
					<p>&starf;&starf;(47)</p></a></li>

					<li><a href="/goto.html"><img src="badaluna-spain.jpg">
					<p class="lightgrey">Spain</p>
					<p>Badaluna Stays</p>
					<p>From &#8377;52,000/Person(3 Days)</p>
					<p>&starf;&starf;&starf(262)</p></a></li>

					<li><a href="/goto.html"><img src="sebutal-portugal.jpg">
					<p class="lightgrey">Portugal</p>
					<p>Sebutal luxury homes</p>
					<p>From &#8377;5,000/Person</p>
					<p>&starf;(12)</p></a></li>

					<li><a href="/goto.html"><img src="cabin-usa.jpg">
					<p class="lightgrey">United States</p>
					<p>Cabin home stays</p>
					<p>From &#8377;4,5000/Person(4)</p>
					<p>&starf;&starf;(5)</p></a></li>

					<li><a href="/goto.html"><img src="batam-indonesia.jpg">
					<p class="lightgrey">Indonesia</p>
					<p>Batam villas</p>
					<p>&#8377;35,000/Person</p>
					<p>&starf;&starf;&starf;(679)</p></a></li>

					<li><a href="/goto.html"><img src="ibiza-spain.jpg">
					<p class="lightgrey">Spain</p>
					<p>Neon stays ibiza</p>
					<p>&#8377;15,048/Person</p>
					<p>&starf;&starf;&starf;&starf;&starf;(6,949)</p></a></li>

					<li><a href="/goto.html"><img src="russia.jpg">
					<p class="lightgrey">Russia</p>
					<p>Russian Delightful homestays</p>
					<p>&#8377;35,000/Person</p>
					<p>&starf;&starf;&starf;(35)</p></a></li>

					<li><a href="/goto.html"><img src="santorini-greece.jpg">
					<p class="lightgrey">Greece</p>
					<p>Santaroni stays and resorts</p>
					<p>&#8377;38,000/Person</p>
					<p>&starf;&starf;&starf;(460)</p></a></li>

					<li id="show"><a href="/goto.html">Show(2000+)  > </a></li>
				</ul>

			</article>
			<article class="popular-destinations">
				<h2 style="padding-left:40px;text-shadow:2px 2px 4px lightgrey">Popular Destinations in the United States</h2>
				<ul>
					<li><a href="/goto.html">
					<h3>San Farancisco</h3>
					<p class="lightgray">$216/night Average</p>
					</a></li>
	
					<li><a href="/goto.html">
					<h3>Los Angeles</h3>
					<p class="lightgray">$213/night Average</p>
					</a></li>

					<li><a href="/goto.html">
					<h3>New York</h3>
					<p class="lightgray">$159/night Average</p>
					</a></li>

					<li><a href="/goto.html">
					<h3>Seattle</h3>
					<p class="lightgray">$134/night Average</p>
					</a></li>

					<li><a href="/goto.html">
					<h3>Denver</h3>
					<p class="lightgray">$128/night Average</p>
					</a></li>

					<li><a href="/goto.html">
					<h3>Washington D.C</h3>
					<p class="lightgray">$166/night Average</p>
					</a></li>
	
					<li><a href="/goto.html">
					<h3>Phoenix</h3>
					<p class="lightgray">$232/night Average</p>
					</a></li>

					<li><a href="/goto.html">
					<h3>Austin</h3>
					<p class="lightgray">$242/night Average</p>
					</a></li>

					<li><a href="/goto.html">
					<h3>Houston</h3>
					<p class="lightgray">$361/night Average</p>
					</a></li>

					<li><a href="/goto.html">
					<h3>New Orleans</h3>
					<p class="lightgray">$210/night Average</p>
					</a></li>
			</article>
			<article class="featured-destinations">
				<h2 style="padding-left:40px;text-shadow:2px 2px 4px lightgrey">Featured Airbnb Destinations Across the World</h2>
				<p style="padding-left:40px;color:darkgrey">Browse beautiful places to stay with all the comforts of home,plus more</p>
				<ul>
					<li><a href="/goto.html"><img src="airbnbusa.jpg">
					<p class="purplish">420+ VERIFIED STAYS</p>
					<p style="padding-left:5px;color:darkgrey">Stay in United States</p>
					</a></li>
					<li><a href="/goto.html"><img src="airbnblondon.jpg">
					<p class="purplish">260+ VERIFIED STAYS</p>
					<p style="padding-left:5px;color:darkgrey">Stay in London</p>
					</a></li>
					<li><a href="/goto.html"><img src="airbnbparis.png">
					<p class="purplish">367+ VERIFIED STAYS</p>
					<p style="padding-left:5px;color:darkgrey">Stay in Paris</p>
					</a></li>
					<li id="grey-bg" style="padding-left:5px"><a href="/goto.html">Show more airbnb plus Destinations >> </a></li>
				</ul>
			</article>
			<article class="superhost">
				<a href="/goto.html"><h2 style="padding-left:40px;text-shadow:2px 2px 4px lightgrey">Stay with a Superhost</h2>
				<p style="padding-left:40px">Make yourself at home with these experience hosts >></p></a>
				<ul>
					<li><a href="/goto.html"><img src="mexico-new.jpg">
					<p class="bg">Mexico  &starf;&starf;(56)</p>
					<p>Luxuy Stays @ Mexico</p>
					<p>&#8377;3,000/group(7)</p>
					</a></li>

					<li><a href="/goto.html"><img src="indonesia-new.jpg">
					<p class="bg">Indonesia  &starf;&starf;&starf;&starf;(399)</p>
					<p>Charming @ Indonesia<br>
					w/ free spas and wifi</p>
					<p>&#8377;30,000/group(3)</p>
					</a></li>

					<li><a href="/goto.html"><img src="columbia-new.jpg">
					<p class="bg">Columbia &starf;&starf;&starf;&starf;(75)</p>
					<p>Luxuy Stays @ Columbia<br>
					(free Bf&wifi)</p>
					<p>&#8377;25,000/group(10)</p>
					</a></li>

					<li><a href="/goto.html"><img src="usa-new.jpg">
					<p class="bg">United States  &starf;&starf;(36)</p>
					<p>Luxuy Stays @ United States<br>
					(spa&wifi)</p>
					<p>&#8377;56,000/group(7)</p>
					</a></li>

					<li><a href="/goto.html"><img src="usa-new1.jpg">
					<p class="bg">United States  &starf;&starf;&starf;(20)</p>
					<p>Luxuy Stays @ United States<br>
					(w/ 3 complementary meals)</p>
					<p>&#8377;10,000/group(6)</p>
					</a></li>
					
					<li><a href="/goto.html"><img src="usa-new2.jpg">
					<p class="bg">United States  &starf;&starf;&starf;&starf;(50)</p>
					<p>Luxuy Stays @ United States</p>
					<p>&#8377;3789/group(8)</p>
					</a></li>

					<li><a href="/goto.html"><img src="uk-new.jpg">
					<p class="bg">United Kingdom  &starf;(40)</p>
					<p>Luxuy Stays @ United Kingdom<br>
					(complemetary bf&wifi)</p>
					<p>&#8377;30,000/group(10)</p>
					</a></li>

					<li><a href="/goto.html"><img src="iceland-new.jpg">
					<p class="bg">IceLand   &starf;&starf;&starf;(567)</p>
					<p>Luxuy Stays @ Iceland<br>
					with complimentary breakfast</p>
					<p>&#8377;3,000/Person</p>
					</a></li>

					<li id="shownext"><a href="/goto.html">Show(2000+)</a></li>
				</ul>
			</article>
			<article class="unique-places">
				<h2 style="padding-left:40px;text-shadow:2px 2px 4px lightgrey">Unique Places to stay for the next trip</h2>
				<p style="padding-left:40px">Book one of these spots to escape the ordinary</p>
				<ul>
					<li><a href="/goto.html"><img src="treehouse.jpg">
					<p class="bg">1900+ TREE HOUSES</p>
					<p>Get Some Perspective</p>
					<p class="bg">Take this trip to new Kind of<br>
					heights with this tree-house</p>
					</a></li>
	
					<li><a href="/goto.html"><img src="boathouse.jpg">
					<p class="bg">2000+ BOAT-HOUSES</p>
					<p>Sail the high seas</p>
					<p class="bg">Follow the advernturers foot<br>
					steps back of all shapes and sizes of boats</p>
					</a></li>
					
					<li><a href="/goto.html"><img src="yurts.jpg">
					<p class="bg">590+ YURTS</p>
					<p>Made just for glamping</p>
					<p class="bg">Embracd the mixture of Indoor<br>
					and also the great green outdoors</p>
					</a></li>

				</ul>
			</article>
			<footer class="foot">
			<hr></hr>
			<ul>
				<li><h3>About</h3></li>
				<li><a href="/goto.html">Diversity&Belonging</a></li>
				<li><a href="/goto.html">Accessibility</a></li>
				<li><a href="/goto.html">Trust&Safety</a></li>
				<li><a href="/goto.html">Airbnb Citizen</a></li>
				<li><a href="/goto.html">Newsroom</a></li>
				
			</ul>
			<ul id="f1">
				<li><h3>Community</h3></li>
				<li><a href="/goto.html">Airbnb Magazing</a></li>
				<li><a href="/goto.html">Airbnb for work</a></li>
				<li><a href="/goto.html">Invite friends</a></li>
				<li><a href="/goto.html">Career</a></li>
			</ul>
			<ul id="f2">
				<li><h3>Host</h3></li>
				<li><a href="/goto.html">Host Your Home</a></li>
				<li><a href="/goto.html">Host your experience</a></li>
				<li><a href="/goto.html">Responsible Hosting</a></li>
				<li><a href="/goto.html">Open Homes</a></li>
				<li><a href="/goto.html">Olympics</a></li>
				<li><a href="/goto.html">Resources</a></li>
			</ul>	
			<ul id="f3">
				<li><h3>Support</h3></li>
				<li><a href="/goto.html">Help Center</a></li>
				<li><a href="/goto.html">Neighborhood Support</a></li>
			</ul>
			</footer>
			<footer class="foot2">
				<hr></hr>
			<ul id="f4">
				<li>&copy; 2020 Airbnb, Inc. All rights reserved</li>
				<li><a href="/goto.html">. Privacy </a></li>
				<li><a href="/goto.html">. Terms </a></li>
				<li><a href="/goto.html">. Site Map </a></li>
			</ul>

			<ul id="f5">
				<li><a href="/goto.html">🌐</a></li>
				<li><a href="/goto.html">English</a></li>
				<li><a href="/goto.html">&#8377;INR</a></li>
				<li><a href="/goto.html"><img src="twitter.png" style="width:20px;height:20px;"></a></li>
				<li><a href="/goto.html"><img src="facebook.png"style="width:20px;height:20px;"></a></li>
			</ul>
			</ul>
			</footer>
		</body>
		
		
		
