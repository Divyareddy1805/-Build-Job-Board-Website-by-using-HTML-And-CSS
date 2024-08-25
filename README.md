# -Build-Job-Board-Website-by-using-HTML-And-CSS
\<!DOCTYPE html> 
<html lang="en"> 

<head> 
	<meta charset="UTF-8"> 
	<meta name="viewport" content= 
		"width=device-width, initial-scale=1.0"> 
	<title> 
		Design a Job Board
		using HTML and CSS 
	</title> 
	
	<link rel="stylesheet" href="style.css"> 
</head> 

<body> 
	<header> 
		<h1>Job Board</h1> 
	</header> 
	<nav> 
		<ul> 
			<li><a href="#">Home</a></li> 
			<li><a href="#">Jobs</a></li> 
			<li><a href="#">Companies</a></li> 
			<li><a href="#">About Us</a></li> 
			<li><a href="#">Contact</a></li> 
		</ul> 
	</nav> 
	<section class="search"> 
		<h2>Find Your Dream Job</h2> 
		<form action="#" method="get"> 
			<input type="text" name="keywords"
				placeholder="Keywords"> 
			<input type="text" name="location"
				placeholder="Location"> 
			<input type="text" name="company"
				placeholder="Company"> 
			<button type="submit"> 
				Search 
			</button> 
		</form> 
	</section> 

	<section class="job-listings"> 
		<h2>Latest Job Listings</h2> 
		<ul> 
            <li> 
                <h3>Web Developer</h3> 
                <p>Company: SDC Tech</p> 
                <p>Location: India</p> 
                <p>Description:Web Developer</p> 
                <a href="#">Apply Now</a> 
            </li> 
            <li> 
                <h3>Graphic Designer</h3> 
                <p>Company: CGY Design</p> 
                <p>Location: India </p> 
                <p>Description:Graphic Designer</p> 
                <a href="#">Apply Now</a> 
            </li> 
    
		</ul> 
	</section> 
	
	<footer> 
		<p>© 2024 Job Board</p> 
	</footer> 
</body> 

</html>
