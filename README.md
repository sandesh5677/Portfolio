<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Sandesh Shinde Portfolio</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    
    <link href="https://fonts.googleapis.com/css?family=Poppins:100,200,300,400,500,600,700,800,900" rel="stylesheet">

    <link rel="stylesheet" href="css/open-iconic-bootstrap.min.css">
    <link rel="stylesheet" href="css/animate.css">
    
    <link rel="stylesheet" href="css/owl.carousel.min.css">
    <link rel="stylesheet" href="css/owl.theme.default.min.css">
    <link rel="stylesheet" href="css/magnific-popup.css">

    <link rel="stylesheet" href="css/aos.css">

    <link rel="stylesheet" href="css/ionicons.min.css">
    
    <link rel="stylesheet" href="css/flaticon.css">
    <link rel="stylesheet" href="css/icomoon.css">
    <link rel="stylesheet" href="css/style.css">



<style>

/*======================================
//--//-->   ABOUT
======================================*/

.about-mf .box-shadow-full {
  padding-top: 4rem;
  padding-bottom: 4rem;
}

.about-mf .about-img {
  margin-bottom: 2rem;
}

.about-mf .about-img img {
  margin-left: 10px;
}


.skill-mf .progress {
  /* background-color: #cde1f8; */
  margin: .5rem 0 1.2rem 0;
  border-radius: 0;
  height: .7rem;
}

.skill-mf .progress .progress-bar {
  height: .7rem;
  background-color: #ffbd39;
}


/* Animation styles */
#typing-animation {
  position: relative;
  font-size: 30px;
  font-weight: bold;
  color: rgb(255, 255, 255);
  overflow: hidden;
  white-space: nowrap;
  animation: typing 3s steps(20, end) infinite;
}

#typing-animation:before {
  content: "";
  /* position: absolute; */
  top: 0;
  left: 0;
  width: 0;
  height: 100%;
  background-color: #ccc;
  animation: typing-cursor 0.5s ease-in-out infinite;
}

@keyframes typing {
  from {
    width: 0;
  }
  to {
    width: 100%;
  }
}

@keyframes typing-cursor {
  from {
    width: 5px;
  }
  to {
    width: 0;
  }
}


/* project image zoom effect */

.zoom-effect {
  overflow: hidden;
  transition: transform 0.3s ease-out;
}

.zoom-effect:hover {
  transform: scale(1.1);
}


</style>


  </head>
  <body data-spy="scroll" data-target=".site-navbar-target" data-offset="300">
	  
	  
    <nav class="navbar navbar-expand-lg navbar-dark ftco_navbar ftco-navbar-light site-navbar-target" id="ftco-navbar">
	    <div class="container">
	      <a class="navbar-brand" href="index.html">Sandesh Shinde</a>
	      <button class="navbar-toggler js-fh5co-nav-toggle fh5co-nav-toggle" type="button" data-toggle="collapse" data-target="#ftco-nav" aria-controls="ftco-nav" aria-expanded="false" aria-label="Toggle navigation">
	        <span class="oi oi-menu"></span> Menu
	      </button>

	      <div class="collapse navbar-collapse" id="ftco-nav">
	        <ul class="navbar-nav nav ml-auto">
	          <li class="nav-item"><a href="#home-section" class="nav-link"><span>Home</span></a></li>
	          <li class="nav-item"><a href="#about-section" class="nav-link"><span>About</span></a></li>
	          <li class="nav-item"><a href="#resume-section" class="nav-link"><span>Resume</span></a></li>
	          <li class="nav-item"><a href="#project-section" class="nav-link"><span>Projects</span></a></li>
	          <li class="nav-item"><a href="#contact-section" class="nav-link"><span>Contact</span></a></li>
	        </ul>
	      </div>
	    </div>
	  </nav>
	  <section id="home-section" class="hero">
		  <div class="home-slider  owl-carousel">
	       <div class="slider-item ">
	      	<div class="overlay"></div>
	         <div class="container">
	          <div class="row d-md-flex no-gutters slider-text align-items-end justify-content-end" data-scrollax-parent="true">
	          	<div class="one-third js-fullheight order-md-last img" style="background-image:url(images/sandesh.);">
	          	 <div class="overlay"></div>
	          	</div>
		          <div class="one-forth d-flex  align-items-center ftco-animate" data-scrollax=" properties: { translateY: '70%' }">
		          	<div class="text">
		          		<span class="subheading">Hello!</span>
			            <h1 class="mb-4 mt-3">I'm <span>Sandesh Shinde</span></h1>

						<!-- Element to contain animated typing -->
						<span id="typing-animation"></span>

						<script>

						// Initialize the typing animation
						const typingAnimationElement = document.getElementById('typing-animation');

						// Create an array of typing text
						const typingTexts = [
						'Software Developer',
						' ',
						
						];

						// Create a function to display the typing animation for a given text
						function playTypingAnimation(text) {
						// Loop through each character and add it to the element
						for (let i = 0; i < text.length; i++) {
							setTimeout(() => {
							typingAnimationElement.textContent += text[i];
							}, i * 200); // Increase the delay to slow down the typing animation
						}

						// Once the animation is complete, reset the text and start over
						setTimeout(() => {
							typingAnimationElement.textContent = '';
							playTypingAnimation(typingTexts[(typingTexts.indexOf(text) + 1) % typingTexts.length]);
						}, text.length * 200);
						}

						// Start the typing animation loop
						playTypingAnimation(typingTexts[0]);

						</script>

						<br>
						<br>
			            <h2>A junior software  developer</h2>
						<!-- <h2 class="d-flex" style="margin-bottom: 0">With over 5 years of experience</h2> -->
						<!-- <br> -->
			            <p><a href="https://www.linkedin.com/in/sandesh-shinde-94455623b/" class="btn btn-primary py-3 px-4">linkedin</a> 
							<a href="https://github.com/sandesh5677?tab=repositories" class="btn btn-white btn-outline-white py-3 px-4">My works</a></p>
		            </div>
		          </div>
	        	</div>
	        </div>
	      </div>
		</div>
    </section>



    <section class="ftco-about img ftco-section ftco-no-pb" id="about-section">
    	<div class="container">
			<div class="row">
				<div class="row d-flex align-items-stretch">
				<!-- <div class="row d-flex"> -->
					<div class="col-md-6 col-lg-5 d-flex">
						<div class="img-about img d-flex align-items-stretch">
							<div class="overlay">
								<div class="row">
									<div class="col-sm-6 col-md-5">
									  <div class="about-img">
										<img src="images/InShot_20240307_005013709.png" class="img-fluid rounded b-shadow-a" alt="">
									  </div>
									</div>
									<!-- Details next to profile image -->
									<div class="col-sm-6 col-md-7">
									  <div class="about-info">
										<p><span class="title-s">Name: </span> <span>Sandesh Shinde</span></p>
										<p><span class="title-s">Job Role: </span> <span>junior Developer</span></p>
										<p><span class="title-s">Experience: </span> <span>6 Months</span></p>
										<p><span class="title-s">Address: </span> <span>Maharashtra, India</span></p>
									  </div>
									</div>
								  </div>

								<div class="skill-mf">
									<p class="title-s">Skills</p>
									<span>SQL</span> <span class="pull-right">95%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 95%;" aria-valuenow="95" aria-valuemin="0"
											aria-valuemax="100"></div>
									</div>
									
									<span>PYTHON</span> <span class="pull-right">85%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 85%" aria-valuenow="85" aria-valuemin="0"
											aria-valuemax="100"></div>
									</div>

									<span>Java</span> <span class="pull-right">85%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 85%" aria-valuenow="85" aria-valuemin="0"
											aria-valuemax="100"></div>
									</div>

									<span>Angular</span> <span class="pull-right">90%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 90%" aria-valuenow="90" aria-valuemin="0"
											aria-valuemax="100"></div>
									</div>
									
									<span>API Testing & Manual Testing</span> <span class="pull-right">50%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 90%" aria-valuenow="90" aria-valuemin="0"
											aria-valuemax="100"></div>
									</div>									
									
									<span>Nest-Js</span> <span class="pull-right">80%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 80%" aria-valuenow="80" aria-valuemin="0"
											aria-valuemax="100"></div>
									</div>
								</div>
							</div>
						</div>
					</div>
					
					<div class="col-md-6 col-lg-7 pl-lg-5 pb-5">
						<div class="row justify-content-start pb-3">
							<div class="col-md-12 heading-section ftco-animate">
								
								<h1 class="big">About</h1>
								<h2 class="mb-4">About Me</h2>
								
								<p>With over 6 Month of comprehensive experience in the field of Angular & Nest-Js, accompanied by a Master's degree in compuer Applications. 
									Proficient in Software Development Lifecycle:, problem solving, Debugging and Testing, Database Management, &amp; Object-Oriented Design. 
									Demonstrated success in leading impactful projects and providing effective mentorship.</p>
								<ul class="about-info mt-4 px-md-0 px-2">
									<li class="d-flex"><span>Profile:</span> <span>Software Developer and Tester</span></li>
									<li class="d-flex"><span>Domain:</span> <span>Retail, Ecommerce, BFSI &amp; Digital Marketing</span></li>
									<li class="d-flex"><span>Education:</span> <span>Master of computer Applications</span></li>
									<li class="d-flex"><span>Language:</span> <span>English, Hindi</span></li>
									<li class="d-flex"><span>Frame works:</span> <span>Angular, React js ,Nest-Js</span></li>
									<li class="d-flex"><span>Other Skills:</span> <span>Mysql & MSsql, API integration, Excel, Git, UI/UX Design, Microservices. &amp; SEO</span></li>
									<li class="d-flex"><span>Interest:</span> <span>Traveling, Trekking, Gaming</span></li>
									
								</ul>
							</div>
						</div>


						<div class="counter-wrap ftco-animate d-flex mt-md-3">
							<div class="text">
								<p class="mb-4">
									 <span class="number" data-number="3">0</span> <!-- <span>+</span> -->
									<span>&nbsp; Projects completed</span>
								</p>
								<p><a href="https://www.linkedin.com/in/sandesh-shinde-94455623b/" class="btn btn-primary py-3 px-3">LinkedIn</a></p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
    </section>



	
    <section class="ftco-section ftco-no-pb" id="resume-section">
    	<div class="container">
    		<div class="row justify-content-center pb-5">
          <div class="col-md-10 heading-section text-center ftco-animate">
          	<h1 class="big big-2">Resume</h1>
            <h2 class="mb-4">Resume</h2>
            <p>Seasoned Senior Data Analyst with 5+ years of experience driving business strategies through data-driven insights. Proven expertise in data science, statistical analysis, machine learning algorithms and project management.</p>
          </div>
        </div>

		<div class="row">
			<h1 class="big-4">Experience</h1>
			<div class="underline"></div>
		</div>
		<br>
		
		<div class="row">
				<div class="col-md-6">
					<div class="resume-wrap ftco-animate">
						<span class="date">2023-Present</span>
						<h2>Software Developer Intern</h2>
						<span class="position">Compserv</span>
						<p class="mt-4">Compser Consultant Pvt Ltd, based in Kolhapur, specializes in providing consulting services in the software development industry. 
							<ul>
								<li>Analysed ad campaigns, clickstream, and customer surveys data, identified an increasing demand and launched a strategic product line.</li>
								<li>Developed time series forecasting models to predict sales and optimize marketing budgets, got model performance of 92%.</li>
								<li>Designed and executed A/B tests, performed rigorous statistical analysis. Led to 20% MoM increase in the conversion rate.</li>
							</ul>
						</p>
					</div>

				</div>

				<!-- <div class="col-md-6">
					<div class="resume-wrap ftco-animate">
						<span class="date">2018-2021</span>
						<h2>Senior Data Analyst</h2>
						<span class="position">iQuanti</span>
						<p class="mt-4">iQuanti is a data-driven digital marketing analytics and solutions company, helps top 100 global brands. 
							<ul>
								<li>Performed in-depth market research and analysis to create online pages. Resulted in ~100% website growth and 30% increase in conversion rate YoY.</li>
								<li>Delivered multiple training and mentorship sessions on analytical tools like SQL, MS Excel, Power BI, Tableau and Python.</li>
								<li>Performed migration and enhancements for merchandising dashboard, involved data integration and its feature improvement.</li>
							</ul>
						</p>
					</div>

				</div> -->
			</div>

		<br>
		<br>

		<div class="row">
			<h1 class="big-4">Education</h1>
			<div class="underline"></div>
		</div>
		<br>
		
			<div class="row">
    			<div class="col-md-6">
    				<div class="resume-wrap ftco-animate">
    					<span class="date">2022-2024</span>
    					<h2>Master of Computer Applications</h2>
    					<span class="position">D.Y.Patil University</span>
    					<p class="mt-4">Grade: First class .</p>
    				</div>
    			</div>

    			<div class="col-md-6">
    				<div class="resume-wrap ftco-animate">
    					<span class="date">2019-2022</span>
    					<h2>Bachelor of Science</h2>
    					<span class="position">Shivaji University Kolhapur</span>
    					<p class="mt-4">Grade: First class .</p>
    				</div>
				</div>
    		</div>

    		<div class="row justify-content-center mt-5">
    			<div class="col-md-6 text-center ftco-animate">
    				<p><a href="#" class="btn btn-primary py-4 px-5">Download CV</a></p>
    			</div>
    		</div>
    	</div>
    </section>

   

    <section class="ftco-section" id="project-section">
      <div class="container">
        <div class="row justify-content-center mb-5 pb-5">
          <div class="col-md-7 heading-section text-center ftco-animate">
            <h1 class="big big-2">Projects</h1>
            <h2 class="mb-4">Projects</h2>
            <p>Below are the sample  projects on SQL, Python, java & HTML,CSS.</p>
          </div>
        </div>
        <div class="row d-flex">
          <div class="col-md-4 d-flex ftco-animate">
          	<div class="blog-entry justify-content-end">
              <a href="https://github.com/sandesh5677/Tourse" class="block-20 zoom-effect" style="background-image: url('images/proj_1');">
              </a>
              <div class="text mt-3 float-right d-block">

                <h3 class="heading"><a href="https://github.com/sandesh5677/Tourse">Online Tourse Booking </a></h3>
                <p>Analyzed latest place store data it helps to save time or money to get information and trip budget.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 d-flex ftco-animate">
          	<div class="blog-entry justify-content-end">
              <a href="https://github.com/Baramati/Frontend_" class="block-20 zoom-effect" style="background-image: url('images/nandan\ dairy.jpeg');">
              </a>
              <div class="text mt-3 float-right d-block">

                <h3 class="heading"><a href="https://github.com/Baramati/Frontend_">Web application using Angular & Nest-Js Project for Beginners</a></h3>
                <p>Performed exploratory dynamic data feaching on nandan dairy data using Angular & Nest-Js to improve the customer experience.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 d-flex ftco-animate">
          	<div class="blog-entry">
              <a href="#" class="block-20 zoom-effect" style="background-image: url('images/proj_3.jpg');">
              </a>
              <div class="text mt-3 float-right d-block">

                <h3 class="heading"><a href="#">Power BI Sales dashboard Project for Beginners</a></h3>
                <p>Designed a power bi dashboard for Global Store to track and analyze the online sales data acorss India.</p>
              </div>
            </div>
          </div>
        </div>
	<br>
		<!-- added justify-content-center to center align the last two projects -->
	<!--	<div class="row d-flex justify-content-center">  
			<div class="col-md-4 d-flex ftco-animate">
				<div class="blog-entry justify-content-end">
				<a href="https://github.com/rishabhnmishra/sales_forecasting/tree/main" class="block-20 zoom-effect" style="background-image: url('images/proj_4.jpg');">
				</a>
				<div class="text mt-3 float-right d-block">
  
				  <h3 class="heading"><a href="https://github.com/rishabhnmishra/sales_forecasting/tree/main">Sales Forecast- Time Series Forecasting</a></h3>
				  <p>Used multiple machine learning models to forecast sales (retail store) and performed time series analysis.</p>
				</div>
			  </div>
			</div>
			<div class="col-md-4 d-flex ftco-animate">
				<div class="blog-entry justify-content-end">
				<a href="https://github.com/rishabhnmishra/customer_segmentation/blob/main/Customer_Segmentation-final.ipynb" class="block-20 zoom-effect" style="background-image: url('images/proj_5.jpg');">
				</a>
				<div class="text mt-3 float-right d-block">
  
				  <h3 class="heading"><a href="https://github.com/rishabhnmishra/customer_segmentation/blob/main/Customer_Segmentation-final.ipynb">Customer Segmentation using clustering model</a></h3>
				  <p>Developed a ML model to give various recommendations of financial products &amp; services on target customer groups.</p>
				</div>
			  </div>
			</div>
		 </div>
	  </div>	-->
    </section>

	<section class="ftco-section ftco-no-pt ftco-no-pb ftco-counter img" id="section-counter">
      <div class="container">
		<div class="row d-md-flex align-items-center">
          <div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
            <div class="block-18">
              <div class="text">
                <strong class="number" data-number="20">0</strong>
                <span>Achievements</span>
              </div>
            </div>
          </div>
          <div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
            <div class="block-18">
              <div class="text">
                <strong class="number" data-number="3">0</strong>
                <span>Projects</span>
              </div>
            </div>
          </div>

          <div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
            <div class="block-18">
              <div class="text">
                <strong class="number" data-number="50">0</strong>
                <span>Cups of coffee</span>
              </div>
            </div>
          </div>
        </div>
      </div>
	
	  <div class="ftco-section ftco-hireme img margin-top" style="background-image: url(images/bg_1.jpg)">
			<!-- <div class="container"> -->
				<div class="row justify-content-center">
					<div class="col-md-7 ftco-animate text-center">
						<h2>More projects on<span> Github  </span> </h2>
						<div class="heading"> <h4>I love to Develop Webapplications with delivered responsive project </h4>
						<br>
						<p><a href="https://github.com/dashboard" class="btn btn-primary py-3 px-5">GitHub</a></p>
						</div>
					</div>
				</div>
			<!-- </div> -->
		</div>
	</section>



    <section class="ftco-section contact-section ftco-no-pb" id="contact-section">
      <div class="container">
      	<div class="row justify-content-center mb-5 pb-3">
          <div class="col-md-7 heading-section text-center ftco-animate">
            <h1 class="big big-2">Contact</h1>
            <h2 class="mb-4">Contact Me</h2>
            <p>Below are the details to reach out to me!</p>
          </div>
        </div>

        <div class="row d-flex contact-info mb-5">
          <div class="col-md-6 col-lg-3 d-flex ftco-animate">
          	<div class="align-self-stretch box p-4 text-center">
          		<div class="icon d-flex align-items-center justify-content-center">
          			<span class="icon-map-signs"></span>
          		</div>
          		<h3 class="mb-4">Address</h3>
	            <p>Maharashtra, India</p>
	          </div>
          </div>
          <div class="col-md-6 col-lg-3 d-flex ftco-animate">
          	<div class="align-self-stretch box p-4 text-center">
          		<div class="icon d-flex align-items-center justify-content-center">
          			<span class="icon-phone2"></span>
          		</div>
          		<h3 class="mb-4">Contact Number</h3>
	            <p><a href="#">+91 9158843937</a></p>
	          </div>
          </div>
          <div class="col-md-6 col-lg-3 d-flex ftco-animate">
          	<div class="align-self-stretch box p-4 text-center">
          		<div class="icon d-flex align-items-center justify-content-center">
          			<span class="icon-paper-plane"></span>
          		</div>
          		<h3 class="mb-4">Email Address</h3>
	            <p><a href="mailto:sandeshshinde5677@gmail.com">sandeshshinde5677@gmail.com</a></p>
	          </div>
          </div>
          <div class="col-md-6 col-lg-3 d-flex ftco-animate">
          	<div class="align-self-stretch box p-4 text-center">
          		<div class="icon d-flex align-items-center justify-content-center">
          			<span class="icon-globe"></span>
          		</div>
          		<h3 class="mb-4">Download Resume</h3>
	            <p><a href="#">resumelink</a></p>
	          </div>
          </div>

		  <div class="container">
			<br>
			<br>
			<div class="row justify-content-center">
				<div class="col-md-7 ftco-animate text-center">
					<h2>Have a<span> Question?  </span> <a href="https://forms.gle/uLaTShUKXraAvHJ77" class="btn btn-primary py-3 px-5">Click Here</a> </h2>
				</div>
			</div>
				<br>
					<ul class="ftco-footer-social list-unstyled d-flex justify-content-center align-items-center mb-0">
					  <li class="ftco-animate normal-txt">Find me on  </li>
					  <!-- <li class="ftco-animate"><a href="https://www.youtube.com/@RishabhMishraOfficial"><span class="icon-youtube"></span></a></li> -->
					  <li class="ftco-animate"><a href="https://www.linkedin.com/in/sandesh-shinde-94455623b/"><span class="icon-linkedin"></span></a></li>  
					  <li class="ftco-animate"><a href="https://twitter.com/Sandsh007"><span class="icon-twitter"></span></a></li>
					  <li class="ftco-animate"><a href="https://www.facebook.com/sandesh.shinde.35175"><span class="icon-facebook"></span></a></li>
				      <li class="ftco-animate"><a href="https://www.instagram.com/its_s_a_n_d_y_07/?igsh=MXNvcGZxNmp6ZGtraw%3D%3D"><span class="icon-instagram"></span></a></li>
					</ul>
				<br>
		   </div>
   </div>
 </section>


 
	
    <footer class="ftco-footer ftco-section">
		<div class="container">
		  <div class="row">
			<div class="col-md-12 text-center">
  
			  <p><!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
	Copyright &copy;<script>document.write(new Date().getFullYear());</script> All rights reserved | This template is made with <i class="icon-heart color-danger" aria-hidden="true"></i> by <a href="#" target="_blank">Colorlib</a>
	<!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. --></p>
			</div>
		  </div>
		</div>
	  </footer>


  <!-- loader -->
  <div id="ftco-loader" class="show fullscreen"><svg class="circular" width="48px" height="48px"><circle class="path-bg" cx="24" cy="24" r="22" fill="none" stroke-width="4" stroke="#eeeeee"/><circle class="path" cx="24" cy="24" r="22" fill="none" stroke-width="4" stroke-miterlimit="10" stroke="#F96D00"/></svg></div>


  <script src="js/jquery.min.js"></script>
  <script src="js/jquery-migrate-3.0.1.min.js"></script>
  <script src="js/popper.min.js"></script>
  <script src="js/bootstrap.min.js"></script>
  <script src="js/jquery.easing.1.3.js"></script>
  <script src="js/jquery.waypoints.min.js"></script>
  <script src="js/jquery.stellar.min.js"></script>
  <script src="js/owl.carousel.min.js"></script>
  <script src="js/jquery.magnific-popup.min.js"></script>
  <script src="js/aos.js"></script>
  <script src="js/jquery.animateNumber.min.js"></script>
  <script src="js/scrollax.min.js"></script>
  
  <script src="js/main.js"></script>
    
  </body>
</html>
