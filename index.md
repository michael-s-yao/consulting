<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.container {
  position: relative;
  width: 50%;
}

.image {
  opacity: 1;
  display: block;
  width: 100%;
  height: auto;
  transition: .5s ease;
  backface-visibility: hidden;
}

.middle {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  text-align: center;
}

.container:hover .image {
  opacity: 0.3;
}

.container:hover .middle {
  opacity: 1;
}

.text {
  background-color: #4CAF50;
  color: white;
  font-size: 16px;
  padding: 16px 32px;
}
</style>
</head>

## Our Mission

Getting into your dream college is now harder than ever. Our company's mission is to help guide you through the process of gaining admission at the most prestigious and selective schools in the United States.

## Who We Are

We are a small, dedicated group of parents and students that have collectively figured out all of the details in the college application process.

<!---
<img src="/consulting/assets/images/woman.png" width="50%" height="50%" style="float:left">
<div style="float:right">
	<p><b>Jennifer Lee</b></p>
	<p>Son Recruited for Fencing at Princeton University</p>
</div>


<div class="container">
  <img class="container__image" src="/consulting/assets/images/michael.png">
  <div class="container__text">
    <p><a href="https://michaelsyao.com"><b>Michael Yao</b></a></p>
	<p><em>Current MD-PhD Candidate at University of Pennsylvania</em></p>
	<p><em>BS in Physics at Caltech (Recruited for Swimming)</em></p>
	<p><em>Admitted to 9 US medical schools and 11 undergraduate schools</em></p>
  </div>	
</div>
--->

<div class="container">
  <img src="/consulting/assets/images/michael.png" class="image" style="width:100%">
  <div class="middle">
    <div class="text">John Doe</div>
  </div>
</div>


