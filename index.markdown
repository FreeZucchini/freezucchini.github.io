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
                        src="{{ '/assets/images/rad.jpeg' | relative_url }}"
                        alt="Radiation Detector PCB Image"
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
                    <img
                        src="{{ '/assets/images/lipo-charger.jpeg' | relative_url }}"
                        alt="Multi-Battery Charger PCB"
                    >
                </div>

                <div class="project-card-content">

                    <h3>Multi LiPo Battery Charger</h3>

                    <p>
                        This PCB can charge up to 6 LiPo batteries
                        simultaneously. It was designed to charge batteries during our
                        annual pico-satellite competition where teams would use those batteries
                        for their payloads.
                    </p>

                    <div class="tags">
                        <span>High Power PCB Routing</span>
                        <span>Power Delivery ICs</span>
                        <span>High Power PCB Testing</span>
                    </div>

                </div>

            </article>


            <article class="project-card">

                <div class="project-card-image">
                    <img
                        src="{{ '/assets/images/kessler.jpeg' | relative_url }}"
                        alt="APSS-2 PCB"
                    >
                </div>

                <div class="project-card-content">

                    <h3>Thermal Vacuum Qualification of APSS-2</h3>

                    <p>
                        Qualified the APSS-2 PCB for space conditions by helping out
                        with the setup, debugging and software of the thermal-vacuum test. 
                    </p>

                    <div class="tags">
                        <span>Sensor Calibration</span>
                        <span>Hardware and Harness Setup</span>
                        <span>Space-Systems</span>
                    </div>

                </div>

            </article>

        </div>

    </div>

</section>