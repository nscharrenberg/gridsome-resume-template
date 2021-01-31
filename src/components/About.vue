<template>
    <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="about">
        <div class="w-100">
            <h1 class="mb-0">
                Noah
                <span class="text-primary">Scharrenberg</span>
            </h1>
            <div class="subheading mb-5">
                <a
                        href="mailto:nscharrenberg@hotmail.com"
                >nscharrenberg@hotmail.com</a>
            </div>
            <p class="lead mb-5">
                I'm a recently graduated Software Engineer with an interest to "new" and interesting technologies.
                Throughout my study at Fontys University of Applied Sciences, I've gained experience with advanced software engineering principles for enterprise applications such as microservices.
                During this study I gained interest into Blockchain technology and Artificial Intelligence, where I've worked on projects with these technologies.
            </p>
            <p>I'm currently attending a Bachelor Data Science & Artificial Intelligence, with the aim of specializing into AI and to eventually become a machine learning expert.</p>
            <div class="social-icons">
                <a href="https://linkedin.com/in/nscharrenberg" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn Profile">
                    <font-awesome :icon="['fab', 'linkedin']"/>
                </a>
                <a href="https://github.com/nscharrenberg" target="_blank" rel="noopener noreferrer" aria-label="GitHub Profile">
                    <font-awesome :icon="['fab', 'github']"/>
                </a>
                <a href="https://nscharrenberg.nl" target="_blank" rel="noopener noreferrer" aria-label="Loke.dev">
                    <font-awesome :icon="['fas', 'rss']"/>
                </a>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    .social-icons a {
        cursor: pointer;
        display: inline-block;
        height: 3.5rem;
        width: 3.5rem;
        background-color: var(--secondary);
        color: #fff !important;
        border-radius: 100%;
        text-align: center;
        font-size: 1.5rem;
        line-height: 3.5rem;
        margin-right: 1rem;

        @media (max-width: 380px) {
            margin-right: 0.5rem;
        }

        @media (max-width: 350px) {
            margin-right: 0.2rem;
        }
    }

    .social-icons a:last-child {
        margin-right: 0;
    }

    .social-icons a:hover {
        background-color: var(--primary);
    }
</style>
