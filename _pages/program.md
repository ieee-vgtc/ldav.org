---
layout: default
title: Program
---

# Program

<b>Symposium – October 2, 2017, Room 301-D</b>

<table>
    <tr>
        <td>8:30 – 8:45 am</td>
        <td>Opening Remarks</td>
    </tr>
    <tr>
        <td>8:45 – 8:55 am</td>
        <td>Fast Forward</td>
    </tr>
    <tr>
        <td>8:55 – 10:10 am</td>
        <td><h4>Session: Multicore Techniques</h4>
            (Chair: to be announced)
            <ul>
                <li>
                    Techniques for Data-Parallel Searching for Duplicate Elements. 
                    <i>Brenton Lessley, Kenneth Moreland, Matthew Larsen, Hank Childs</i>
                </li>
                <li>
                    Task-based Augmented Merge Trees with Fibonacci Heaps.
                    <i>Charles Gueunet, Pierre Fortin, Julien Jomier, Julien Tierny</i>
                </li>
                <li>
                    Maximal Clique Enumeration with Data-Parallel Primitives. 
                    <i>Brenton Lessley, Talita Perciano, Manish Mathai, Hank Childs, E. Wes Bethel</i>
                </li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>10:10 – 10:30 am</td><td>Break</td>
    </tr>
    <tr>
        <td>10:30 – 10:55 am</td><td>
        <h4>Session: Sampling Techniques</h4>
        (Chair: to be announced)
        <ul>
            <li>
                Sampling Techniques to Improve Big Data Exploration.
                <i>Julian Andres Ramos Rojas, Mary Beth Kery, Stephanie Rosenthal, Anind Dey</i>
            </li>
        </ul>
        </td>
    </tr>
    <tr>
        <td>10:55 – 12:10 pm</td>
        <td><h4>Keynote Presentation</h4>
            Multiphysics simulation not yet at the extreme scale.
            <br /><i>Prof. Dr. Ulrich Rüde, Friedrich-Alexander Universität Erlangen-Nürnberg</i>
        </td>
    </tr>
    <tr>
        <td>12:00 – 2:00 pm</td>
        <td>Lunch</td>
    </tr>
    <tr>
        <td>2:00 – 3:40 pm</td>
        <td><h4>Session: Interactive Visualization / In Situ Techniques</h4>
            (Chair: to be announced)
            <ul>
                <li>
                    Interactive Visualization of High-Dimensional Petascale Ocean Data.
                    <i>David Ellsworth, Christopher Henze, Bron Nelson</i>
                </li>
                <li>
                    Scalable Web-Embedded Volume Rendering. 
                    <i>Mohammad Raji, Alok Hota, Jian Huang</i>
                </li>
                <li>
                    Using Feature Importance Metrics to Detect Events of Interest in Scientific Computing Applications. 
                    <i>Julia Ling, W. Philip Kegelmeyer, Konduri Aditya, Hemanth Kolla, Kevin A. Reed, Tim M. Shead, Warren L. Davis IV</i>
                </li>
                <li>
                    In Situ Video Encoding of Floating-Point Volume Data Using Special-Purpose Hardware for a Posteriori Rendering and Analysis. 
                    <i>Nick Leaf, Bob Miller, Kwan-Liu Ma</i>
                </li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>3:40 – 4:15 pm</td>
        <td>Break</td>
    </tr>
    <tr>
        <td>4:15 – 5:05 pm</td>
        <td><h4>Session: Distributed Memory Techniques</h4>
        (Chair: to be announced)
        <ul>
            <li>
            GraphRay: Distributed Pathfinder Network Scaling. 
            <i>Alessio Arleo, Oh-Hyun Kwon, Kwan-Liu Ma</i>
            </li>
            <li>
            Parallel Multi-Level Ghost Cell Generation for Distributed Unstructured Grids. <i>John Patchett, Boonthanome Nouanesengesy, James Ahrens, Hans Hagen</i>
            </li>
        </ul>
        </td>
    </tr>
    <tr>
        <td>5:05 – 5:45 pm</td>
        <td><h4>Panel</h4></td>
    </tr>
    <tr>
        <td>5:05 – 5:45 pm</td>
        <td>Best Paper Award &amp; Closing Remarks</td>
    </tr>
    <tr>
        <td>7:00 – 9:00 pm</td>
        <td>
        <h4>VIS Opening Reception &amp; LDAV Poster Session</h4>
        <br />
        Posters:
<ul>
    <li>
        An Application-Oriented Framework for Feature Tracking in Atmospheric Sciences. <i>Daisuke Sakurai, Hans-Christian Hege, Alex Kuhn, Henning Rust, Bastian Kern, Tom-Lukas Breitkopf</i>
    </li>
    <li>
        Optimal Viewpoint Finding for Space Time Cube to Explore Spatio-temporal Characteristics of Vehicle Trajectories on Crossroads. <i>Masahiko Itoh, Daisaku Yokoyama, Masashi Toyoda,Masaru Kitsuregawa</i>
    </li>
    <li>
        VIDeR: Exploring Virtual Reality Visualization and Interaction Tools for Dense Segmented Volume Reconstructions. <i>Edouard Brooks, Joseph Insley, Michael Papka, Silvio Rizzi</i>
    </li>
</ul>
    </td>
    </tr>
</table>

<hr />

<h1>Keynote</h1>

<b>Multiphysics simulation not yet at the extreme scale.</b><br />
<i>Prof. Dr. Ulrich Rüde, Friedrich-Alexander Universität Erlangen-Nürnberg</i>

Exploiting future extreme scale computers to their full capability will require innovation on many levels: New algorithmic paradigms must address unprecedented levels of concurrency in heterogenous systems. In this talk I will report on our work towards extreme scale predictive simulations in physics and engineering problems. Our focus will be on coupled multifield problems as they
arise in Earth mantle convection and in the direct numerical simulation of multiphase flows. We model the whole volume of the planet with a finite element mesh of 1km resolution, resulting in a linear system with more than one trillion (10<sup>12</sup>) degrees of freedom and a solution vector with a size of 80 TByte. Similarly large models can be used with the lattice Boltzmann method for the direct simulation of particulate suspensions for environmental or biomedical flows. Based on these examples, we will discuss our challenges on the road to
predictive science.

<p style="text-align: left;">
<b>Speaker</b><br />
<img style="padding: 0; margin: 0 0 1em 1em; float: right; width: 20%" src="assets/UR.jpg" />
Ulrich Ruede heads Chair for Simulation at the University Erlangen-Nuremberg and is the leader of the Parallel Algorithms Team at the Centre Européen de Recherche et de Formation Avancée en Calcul Scientifique (CERFACS) in Toulouse. He studied Mathematics and Computer Science at Technische Universitaet Muenchen (TUM) and The Florida State University. He has been a visiting Professor at University of Colorado, Boulder and the National University of Singapur. His research interests lie in Computational Science and Engineering with a focus on parallel numerical algorithms and high end computing, in particular computational fluid dynamics, multilevel methods, and software engineering for high performance computing. He is a Fellow of the Society of Industrial and Applied Mathematics.</p>
