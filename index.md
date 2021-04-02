<head>
    <style>
        .our-team{
            text-align: center;
            border-radius: 20px;
            overflow: hidden;
            position: relative;
            transition: all 0.3s ease 0s;
        }
        .our-team .pic{
            background: #f6931e;
            transition: all 0.3s ease 0s;
        }
        .our-team:hover .pic{
            padding: 10px;
            border-radius: 10px;
            transform: scale(0.5) translateY(-30%);
        }
        .our-team .pic img{
            width: 100%;
            height: auto;
        }
        .our-team .team-content{
            width: 100%;
            padding: 7px 15px;
            background: #f6931e;
            position: absolute;
            bottom: -30%;
            right: 0;
            opacity: 0;
            transition: all 0.3s ease 0s;
        }
        .our-team:hover .team-content{
            opacity: 1;
            bottom: -10px;
        }
        .our-team .title{
            font-size: 22px;
            color: #fff;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin: 0 0 5px 0;
        }
        .our-team .post{
            display: block;
            font-size: 15px;
            font-weight: 600;
            color: #fff;
            font-style: italic;
            text-transform: capitalize;
            margin: 0 0 5px 0;
        }
        .our-team .social{
            padding: 0;
            margin: 0;
            list-style: none;
            transition: all 0.35s ease 0s;
        }
        .our-team .social li{
            display: inline-block;
            margin: 0 5px 0 0;
        }
        .our-team .social li a{
            display: block;
            width: 40px;
            height: 40px;
            line-height: 40px;
            border-radius: 15px 0 15px 0;
            font-size: 20px;
            color: #fff;
            overflow: hidden;
            z-index: 1;
            position: relative;
            transition: all 0.35s ease 0s;
        }
        .our-team .social li a:before{
            content: "";
            width: 100%;
            height: 100%;
            background: #e06f06;
            position: absolute;
            top: 0;
            left: -100%;
            z-index: -1;
            transition: all 0.3s ease-in-out 0s;
        }
        .our-team .social li a:hover:before{ left: 0; }
        @media only screen and (max-width: 990px){
            .our-team{ margin-bottom: 30px; }
        }
    </style>
</head>

## Our Mission

Getting into your dream college is now harder than ever. Our company's mission is to help guide you through the process of gaining admission at the most prestigious and selective schools in the United States.

## Who We Are

We are a small, dedicated group of parents and students that have collectively figured out all of the details in the college application process.

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

<div class="container">
    <div class="row">
        <div class="col-md-4 col-sm-6">
            <div class="our-team">
                <div class="pic">
                    <img src="/consulting/assets/images/michael.png">
                </div>
                <div class="team-content">
                    <h3 class="title">Williamson</h3>
                    <span class="post">Web Developer</span>
                    <ul class="social">
                        <li><a href="#"><i class="fab fa-facebook"></i></a></li>
                        <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                        <li><a href="#"><i class="fab fa-google-plus"></i></a></li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="col-md-4 col-sm-6">
            <div class="our-team">
                <div class="pic">
                    <img src="images/img-2.jpg">
                </div>
                <div class="team-content">
                    <h3 class="title">Kristiana</h3>
                    <span class="post">Web Designer</span>
                    <ul class="social">
                        <li><a href="#"><i class="fab fa-facebook"></i></a></li>
                        <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                        <li><a href="#"><i class="fab fa-google-plus"></i></a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>


