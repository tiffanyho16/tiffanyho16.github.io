---
layout: post
title:  "Jello Simulation"
date:   2019-4-9
excerpt: ""
project: true
tag:
- blog
comments: true
---
    
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
<head>
    <style>
        body {
          padding: 100px;
          width: 1000px;
          margin: auto;
          text-align: left;
          font-weight: 300;
          font-family: 'Open Sans', sans-serif;
          color: #121212;
        }
        h1, h2, h3, h4 {
          font-family: 'Source Sans Pro', sans-serif;
        }
        table, th, td {
          border: 1px solid black;
        }
</style>
<title>Jello Simulation  |  CS 184</title>
<meta http-equiv="content-type" content="text/html; charset=utf-8" />
<link rel="stylesheet" type="text/css" href="style.css" media="screen" />
</head>

<body>
<h1 align="middle">Simulating Rigid Bodies In Jello</h1>
    <h3 align="middle">Derrick Li, Tiffany Ho, and Ashley Park</h3>
    <div align="middle">
            <img src="./images/jello.jpg" height=400px/>
    </div>

    <div class="padded">
        <p>Our project proposal is a realistic simulation of rigid objects encased in a gelatin solution.
            The inspiration for this idea is the <a href="https://www.youtube.com/watch?v=glFrp-CmNVA&t=34s"> "Stapler in Jello"</a>
            scene from The Office. If time allows, we could extend the functionality of the project by including an interactive
            portion of the project that responds to user inputs.
        </p>
    
    <h2 align="middle">Problem Description</h2>
        <p>The problem we are trying to solve is creating a realistic model of the physical properties of a gelatin material
            surrounding a rigid object. Specifically, we will be trying to model the properties of a <a href="https://en.wikipedia.org/wiki/Colloid">colloidal</a>
            material that refracts light and is elastic in response to forces. We also want to simulate how a rigid object such as a stapler would interact with a deformable environment.
            This problem is important because we will be combining several physical properties that are complex to model in graphics (reflection / refraction of light,
            fluids / deformable objects, elastic vs. inelastic material) combining them, and attempting to model
            their interactions. The challenge of the problem lies in being able to model all these properties individually,
            and then realistically simulating how all these properties would work together when combined.
        </p>

    <h2 align="middle">Goals and Deliverables</h2>
        <p>
            Our goals can be broken down into three major milestones:
        </p>
        <ol>
            <li> A realistic simulation of a gelatin substance. An example of the type of material we are trying to
                create can be found <a href="https://vimeo.com/59639004">here</a>. Some sources suggest using a
                mass spring system to simulate the material, which is also used in the cloth simulation for Project 4.
                We would consider this the "baseline plan".
            </li>
            <li> A realistic simulation of rigid bodies encased in the gelatin material. This would require implementing
                interactions between rigid and elastic materials, and probably include a video demo to demonstrate the interactions
                between the two different materials.
            </li>

            <li> A responsive realtime demo of the rigid bodies encased in gelatin. This would require handling user input
                and changing the scene accordingly. We would potentially also have to think about optimizations if our
                rendering takes too long for a realtime simulation. This would definitely be part of the "aspirational plan"
            </li>
        </ol>

        <p> In summary, we can break down the goals and deliverables into two plans:</p>
        <ol>
            <li>Our baseline plan is to complete Milestone 1 and a reasonable amount of Milestone 2 (e.g. we expect to encounter
                some difficulties dealing with the interactions between rigid and elastic objects, so the interactions may not
                work perfectly).
            </li>
            <li>
                Our aspirational plan is to have Milestone 1 and 2 completely done, and complete as much as possible of
                Milestone 3. If time allows, we could allow the user to control more complex aspects of the scene (to be decided later).
            </li>
        </ol>

    <h2 align="middle">Schedule</h2>

    <p><b>By 4/18: </b> Finish implementing the basic properties of gelatin. This would include the visual properties such as how gelatin reflects/refracts light as well as a demo (with pre-determined parameters) showing how gelatin moves given a directional force.</p>
    <p><b>By 4/25: </b> Finish implementing gelatin interacting with static objects. We've broken this down into three different goals listed below.</p>
    <ol>
        <li>A static object encased in gelatin
        </li>
        <li>
            Gelatin under static objects: The object should sink into the gelatin at a speed depending on its weight and the gelatin should cave in and expand around it as a result. We can demo this with two objects of different weights.
        </li>
        <li>
          Gelatin and gravity: We'd like to demo gelatin falling out from an upside down mug. We'd have to take into account the friction between gelatin and the mug to calculate the speed at which it moves out of the mug, how fast it'd fall once out of the mug, and then the reaction to it hitting the ground (breaking off into pieces, getting squished, etc). </li>
    </ol>
    <p><b>By 5/9: </b> Finish adding interactive components. We'd like the user to be able to move around a plate on which the gelatin rests. Depending on speed at which the user moves around their finger/cursor, the gelatin should jiggle accordingly. We'd also like the user to be able to "poke"/click on the gelatin at a position of their choosing. The gelatin should jiggle and indent.

    <h2 align="middle">Resources</h2>
        <p>The following resources are references for the project:</p>
        <ol>
            <li>http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.101.3192&rep=rep1&type=pdf</li>
            <li>https://www.cs.cmu.edu/~ph/jello/jello.html</li>
            <li>http://www.cs.cmu.edu/~barbic/prog3.html</li>
        </ol>

        <p>In anticipation of the realtime component of the project, one software resource we may rely on is OpenGL.</p>


</div>
</body>
</html>
