# Project Portfolio (WIP)

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Profile Page</title>
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

## Bio <a name="bio"></a>

Hi, I'm Alex! I am a sophomore at CU Boulder studying aerospace and electrical engineering. I am passionate about contributing to the future of space exploration through developing avionics, control systems, and GNC algorithms for spacecraft.

## Education <a name="edu"></a>

University of Colorado, Boulder class of 2027

B.S. Aerospace Engineering, minor in Electrical Engineering

## Experience <a name="exp"></a>

<hr>

View my full resume [here](Alex_Reich_2024-7_Resume.pdf)

### Avionics Lead, CU Sounding Rocket Lab

Responsible for organizing the creation of a full avionics system including updating an existing sensor suite, adding RF downlink capability, and adding pyro channels to meet deployment requirements.

### Avionics Engineer, CU Sounding Rocket Lab

Designed and implemented custom sensor drivers and employing low-level communications protocols using NASA's FPrime flight software framework.

### NASA SUITS Team Co-Lead (Team Cartographer)

Coordinated the design and implementation of an augmented reality EVA assistance system and associated mission control console. Testing at the Johnson Space Center Rock Yard demonstrated a significant decrease in cognitive load on the "astronaut" during simulated EVA tasks.



## Projects <a name="proj"></a>

<hr>

### Inverted Pendulum Simulation and Control

Determined system dynamics equations, created control architecture and algorithm, and tuned using MATLAB. Code can be found [here](https://github.com/areich128/ControlAlgorithms/tree/master/MCMC)

### PD Controller for 1-DOF Thrust Vector Control

Determined system dynamics and transfer equations, created PD controller and tuned gains to be able to dictate natural frequency and damping ratio. Code can be found [here](https://github.com/areich128/ControlAlgorithms/tree/master/PD_Algo)

<div>
    <img src="damping.png" alt="Angle of deflection of 'rocket' when run with varying damping ratios" style="width: 45%; height: auto;">
    <img src="W_n.png" alt="Angle of deflection of 'rocket' when run with varying natural frequencies" style="width: 45%; height: auto;">
</div>

### 5th Kibo RPC

Created pathfinding algorithm to scan images throughout the Kibo ISS module while avoiding Keep-Out-Zones and following a near-optimal path. Team was awarded **US Top 10**.

### Kalman Filter

Created univariate Kalman filter algorithm based off [this](https://www.kalmanfilter.net/alphabeta.html) tutorial. Applied it to altitude readings made by the BMP388 barometric altitude sensor. Code can be found [here](https://github.com/areich128/KalmanFilter)

<div>
    <img src="filteredAltitude.png" alt="Filtered altitude sensing. Lag in filtered data was later fixed by increasing process noise variance." class="centered-image">
</div>

### NASA Space Apps Hackathon (2023)

### Coilgun

Designed and implemented circuit to launch a small metal projectile using electromagnetic propulsion.

### Marx Generator

Designed and implemented high voltage generator.



<!-- [General Engineering Projects](https://areich128.github.io/Projects/projects.html)

[Software Projects](https://areich128.github.io/Software/software.html)

[Circuit Design Projects](https://areich128.github.io/CircuitDesign/circuitdes.html) -->


## Contact <a name="contact"></a>

<hr>

<div style="display: flex; justify-content: space-between;">
    <div style="width: 30%; text-align: left;">alre8317@colorado.edu</div>
    <div style="width: 30%; text-align: center;">
        <a href="https://www.linkedin.com/in/alex-reich-650683252/" target="_blank" class="social-icons">
            <i class="fab fa-linkedin fa-2x"></i>
        </a>
    </div>
    <div style="width: 30%; text-align: right;">
        <a href="https://github.com/areich128" target="_blank" class="social-icons">
            <i class="fab fa-github fa-2x"></i>
        </a>
    </div>
</div>