---
layout: default
title: Portfolio
---

<section class="hero">

    <div class="hero-content">

        <div class="hero-text">
            <p class="greeting">Hi</p>

            <h1>
                I'm <span>{{ Ramanujan }}</span>
            </h1>

            <h2>
                A Computer Systems Engineer
            </h2>

            <p class="hero-description">
                I design and build software, embedded systems, and
                other engineering projects. This portfolio showcases
                some of the things I've worked on.
            </p>

            <div class="hero-buttons">
                <a href="#projects" class="btn btn-primary">
                    View Projects
                </a>

                <a href="#contact" class="btn btn-secondary">
                    Contact Me
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


<section id="about" class="about">

    <div class="about-container">

        <div class="about-image">
            <div class="image-ring">
                <img
                    src="{{ '/assets/images/profile.jpg' | relative_url }}"
                    alt="{{ site.author.name }}"
                >
            </div>
        </div>

        <div class="about-content">

            <p class="section-label">ABOUT ME</p>

            <h2>
                Computer Systems
                <span>Engineer</span>
            </h2>

            <p>
                I'm interested in the intersection of software,
                hardware and systems engineering.
            </p>

            <p>
                My projects span areas such as embedded systems,
                C++, Python, web development, distributed systems
                and software architecture.
            </p>

            <a href="#experience" class="btn btn-primary">
                My Experience
            </a>

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
                    Project Image
                </div>

                <div class="project-card-content">

                    <h3>Project Name</h3>

                    <p>
                        Short description of what this project
                        does and what problem it solves.
                    </p>

                    <div class="tags">
                        <span>C++</span>
                        <span>Svelte</span>
                        <span>Docker</span>
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