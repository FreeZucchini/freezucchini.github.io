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
                I enjoy building systems where hardware and software meet.
                My projects span embedded systems, PCB design, software development,
                cloud-connected applications, and CubeSat avionics.
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

        <h2>What I've Worked On</h2>

        <div class="project-grid">

            <!-- APSS -->

            <a
                href="{{ '/projects/apss-2-tvac.html' | relative_url }}"
                class="project-card"
            >

                <div class="project-card-image">
                    <img
                        src="{{ '/assets/images/kessler.jpeg' | relative_url }}"
                        alt="APSS-2 CubeSat PCB"
                    >
                </div>

                <div class="project-card-content">

                    <h3>CubeSat Avionics</h3>

                    <p>
                        As Avionics Team Lead for the Auckland Programme for Space Systems,
                        I work across avionics development, testing and system integration,
                        including qualification testing of CubeSat hardware.
                    </p>

                    <div class="tags">
                        <span>Embedded Systems</span>
                        <span>Hardware Testing</span>
                        <span>Space Systems</span>
                    </div>

                </div>

            </a>


            <!-- Radiation Detector -->

            <a
                href="{{ '/projects/radiation-detector.html' | relative_url }}"
                class="project-card"
            >

                <div class="project-card-image">
                    <img
                        src="{{ '/assets/images/rad.jpeg' | relative_url }}"
                        alt="Radiation Detector PCB"
                    >
                </div>

                <div class="project-card-content">

                    <h3>Radiation Detector</h3>

                    <p>
                        A space-rated radiation detector designed for the APSS-3 CubeSat,
                        using a silicon photomultiplier and analogue signal processing
                        to detect and process weak radiation signals.
                    </p>

                    <div class="tags">
                        <span>PCB Design</span>
                        <span>Analogue Signal Processing</span>
                        <span>Embedded C</span>
                    </div>

                </div>

            </a>


            <!-- Software -->

            <a
                href="#"
                class="project-card"
            >

                <div class="project-card-image">
                    <img
                        src="{{ '/assets/images/car-charging.jpeg' | relative_url }}"
                        alt="Car Charging Console"
                    >
                </div>

                <div class="project-card-content">

                    <h3>Car Charging Console</h3>

                    <p>
                        A cloud-connected EV charging application built with Svelte,
                        C#, Azure Functions and Azure IoT Hub, connecting a web interface
                        to a simulated vehicle charging device.
                    </p>

                    <div class="tags">
                        <span>Svelte</span>
                        <span>C#</span>
                        <span>Azure IoT</span>
                    </div>

                </div>

            </a>

        </div>

    </div>

</section>