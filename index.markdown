---
layout: default
title: Portfolio
---

<section class="hero">

    <div class="hero-content">

        <div class="hero-text">
            <p class="greeting">Hey</p>

            <h1>
                I'm <span>{{ site.author.name }}</span>
            </h1>

            <h2>
                A Computer Systems Engineering Student
            </h2>

            <p class="hero-description">
                This is a little space where I showcase some 
                of the projects I have worked on. They range from a simple LoRa PCB
                to a the qualification of a 1U CubeSat for space!
            </p>

            <div class="hero-buttons">
                <a href="#projects" class="btn btn-primary">
                    View Projects
                </a>
            </div>
        </div>

        <div class="hero-image">
            <div class="image-ring">
                <img
                    src="{{ '/assets/images/profile.jpg' | relative_url }}"
                    alt="{{ site.author.name }}"
                >
            </div>
        </div>

    </div>

</section>


<section id="projects" class="projects">

    <div class="section-container">

        <p class="section-label">FEATURED WORK</p>

        <h2>My Projects</h2>

        <div class="project-grid">

            <article class="project-card">

                <div class="project-card-image">
                    <img
                        src="{{ '/assets/images/rad.jpg' | relative_url }}"
                    >
                </div>

                <div class="project-card-content">

                    <h3>Radiation Detector</h3>

                    <p>
                        A space-rated radiation detector that uses a
                        dual-opamp analogue signal processing circuit to process
                        radiation data collected via an SiPM. It is one of the payloads on
                        the APSS-3 CubeSat.
                    </p>

                    <div class="tags">
                        <span>Altium Designer</span>
                        <span>Soldering and Testing</span>
                        <span>Embedded C</span>
                    </div>

                </div>

            </article>


            <article class="project-card">

                <div class="project-card-image">
                    Project Image
                </div>

                <div class="project-card-content">

                    <h3>Project Name</h3>

                    <p>
                        Short description of what this project
                        does and what problem it solves.
                    </p>

                    <div class="tags">
                        <span>Python</span>
                        <span>PyQt</span>
                        <span>Machine Learning</span>
                    </div>

                </div>

            </article>


            <article class="project-card">

                <div class="project-card-image">
                    Project Image
                </div>

                <div class="project-card-content">

                    <h3>Project Name</h3>

                    <p>
                        Short description of what this project
                        does and what problem it solves.
                    </p>

                    <div class="tags">
                        <span>Embedded</span>
                        <span>C</span>
                        <span>Hardware</span>
                    </div>

                </div>

            </article>

        </div>

    </div>

</section>