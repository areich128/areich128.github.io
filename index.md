# Project Portfolio

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alex Reich Portfolio</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" rel="stylesheet">
    <style>
        .social-icons {
        text-decoration: none;
        color: inherit; /* Use current text color */
        margin-right: 15px; /* Space between icons */
        }
    </style>
    <style>
        .centered-image {
            display: block;  
            margin: 0 auto;  
            max-width: 300px;
            width: 100%;     
            height: auto;    
        }
    </style>
</head>

| [**BIO**](#bio) | [**EDUCATION**](#education) | [**EXPERIENCE**](#experience) | [**PROJECTS**](#projects) | [**CONTACT**](#contact) |

<br>

## Bio

<hr id="bio">

Hi, I'm Alex! I am a sophomore at CU Boulder studying aerospace and electrical engineering. I am passionate about contributing to the future of space exploration through developing avionics, ADCS, and GNC hardware and software for spacecraft.

<br>

## Education

<hr id="education">

University of Colorado, Boulder class of 2027

B.S. Aerospace Engineering, minor in Electrical Engineering

<br>

## Experience

View my full resume [here.](Alex_Reich_2024-10_Resume.pdf)

<hr id="experience">

<br>

<h3 style="line-height:0">Avionics Lead, CU Sounding Rocket Lab</h3>

*2024 - Present*

Responsible for organizing the creation of a full avionics system including updating an existing sensor suite, adding RF downlink capability, and adding pyro channels to meet deployment requirements.

<br>

<h3 style="line-height:0">Avionics Engineer, CU Sounding Rocket Lab</h3>

*2023-2024*

Designed and implemented custom sensor drivers. Employed low-level serial communications protocols using NASA's FPrime flight software framework.

<br>


<h3 style="line-height:0">NASA SUITS Team Co-Lead (Team Cartographer)</h3>

*2023-2024*

Lead top nationwide team to test mission solutions at Johnson Space Center. Coordinated the design and implementation of an augmented reality EVA assistance system and associated mission control console. Testing at the Johnson Space Center Rock Yard demonstrated a significant decrease in cognitive load on the "astronaut" during simulated EVA tasks.

<br>


## Projects

<hr id="projects">

<br>

<h3 style="line-height:0">Inverted Pendulum Simulation and Control</h3>

<i style="line-height:0">2024</i>

Determined system dynamics equations, created control architecture, and tuned control gains using the Markov Chain Monte Carlo method in MATLAB. Code can be found [here](https://github.com/areich128/ControlAlgorithms/tree/master/MCMC).

<div>
    <video controls style="width: 45%; height: auto; margin-left: auto; margin-right: auto;">
        <source src="pendulum_swingup.mp4" type="video/mp4">
    </video>
    <img src="MCMC10k_updownfinal.jpg" alt="Gains through tuning process with 10k iterations" style="width: 45%; height: auto; margin-left: auto; margin-right: auto;">
</div>
<div style="text-align:center">
    <i>Left: Video of pendulum swing-up stabilization. Right: Gain set as they are tuned over 10k iterations of MCMC algorithm.</i>
</div>

<br>

<h3 style="line-height:0">PD Controller for 1-DOF Thrust Vector Control</h3>

<i style="line-height:0">2024</i>

Determined system dynamics and transfer equations, created PD controller and tuned control gains to be able to dictate natural frequency and damping ratio. Code can be found [here](https://github.com/areich128/ControlAlgorithms/tree/master/PD_Algo).

<div>
    <img src="damping.png" alt="Angle of deflection of 'rocket' when run with varying damping ratios" style="width: 45%; height: auto; margin-left: auto; margin-right: auto;">
    <img src="W_n.png" alt="Angle of deflection of 'rocket' when run with varying natural frequencies" style="width: 45%; height: auto; margin-left: auto; margin-right: auto;">
</div>
<div style="text-align:center">
    <i>Angle of deflection of 'rocket' when run with varying natural damping ratios and natural frequencies, respectively.</i>
</div>

<br>

<h3 style="line-height:0">5th Kibo Robot Programming Challenge</h3>

<i style="line-height:0">2024</i>

Created pathfinding algorithm to guide the AstroBee robot through a simulated Kibo ISS module while scanning images, avoiding Keep-Out-Zones and following a near-optimal path. Awarded **US Top 10**.

<div>
    <img src="kibo_traversal.png" alt="AstroBee robot traversing simulated ISS module" style="width: 100%; height: auto; margin-left: auto; margin-right: auto;">
</div>
<div style="text-align:center">
    <i>AstroBee robot traversing simulated ISS module.</i>
</div>

<br>

<h3 style="line-height:0">Kalman Filter</h3>

<i style="line-height:0">2024</i>

Created univariate Kalman filter algorithm based off [this](https://www.kalmanfilter.net/alphabeta.html) tutorial. Applied it to altitude readings made by the BMP388 barometric altitude sensor. Code can be found [here](https://github.com/areich128/KalmanFilter).

<div>
    <img src="filteredAltitude.png" alt="Filtered altitude sensing. Lag in filtered data was later fixed by increasing process noise variance." class="centered-image">
</div>
<div style="text-align:center">
    <i>Filtered altitude sensing. Lag in filtered data was later fixed by increasing process noise variance.</i>
</div>

<br>

<h3 style="line-height:0">Coilgun</h3>

<i style="line-height:0">2016-2017</i>

Created analog circuit to launch a small metal projectile using electromagnetic propulsion. Designed capacitor bank and coil to exert maximum force on the projectile. Learned basics of IC 555 oscillators, full bridge rectifiers, and voltage step-up and step-down methods. Performed theoretical energy transfer analysis to determine areas for improvement to optimise energy transfer.

<br>



<!-- [General Engineering Projects](https://areich128.github.io/Projects/projects.html)

[Software Projects](https://areich128.github.io/Software/software.html)

[Circuit Design Projects](https://areich128.github.io/CircuitDesign/circuitdes.html) -->


## Contact

<hr id="contact">

<div style="display: flex; justify-content: space-between;">
    <div style="width: 30%; text-align: center;">
        <a href="alre8317@colorado.edu" target="_blank" class="social-icons">
            <i class="fa fa-envelope fa-2x"></i>
        </a>
    </div>
    <div style="width: 30%; text-align: center;">
        <a href="https://www.linkedin.com/in/alex-reich-650683252/" target="_blank" class="social-icons">
            <i class="fab fa-linkedin fa-2x"></i>
        </a>
    </div>
    <div style="width: 30%; text-align: center;">
        <a href="https://github.com/areich128" target="_blank" class="social-icons">
            <i class="fab fa-github fa-2x"></i>
        </a>
    </div>
</div>