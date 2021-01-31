<template>
    <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="skills">
        <div class="w-100">
            <h2 class="mb-5">Skills</h2>

            <div class="subheading mb-3">Programming Languages &amp; Tools</div>
            <ul class="list-inline dev-icons">
                <li class="list-inline-item">
                    <font-awesome :icon="['fab', 'vuejs']"/>
                </li>
                <li class="list-inline-item">
                    <font-awesome :icon="['fab', 'react']"/>
                </li>
                <li class="list-inline-item">
                    <font-awesome :icon="['fab', 'node-js']"/>
                </li>
                <li class="list-inline-item">
                    <font-awesome :icon="['fab', 'java']"/>
                </li>
            </ul>

            <div class="subheading mb-3">Other</div>
            <ul class="fa-ul mb-0">
                <li>
                    <font-awesome class="fa-li" :icon="['fas', 'check']"/>Blockchain
                </li>
                <li>
                    <font-awesome class="fa-li" :icon="['fas', 'check']"/>Microservices
                </li>
                <li>
                    <font-awesome class="fa-li" :icon="['fas', 'check']"/>Waterfall
                </li>
                <li>
                    <font-awesome class="fa-li" :icon="['fas', 'check']"/>Agile Development &amp; Scrum
                </li>
                <li>
                    <font-awesome class="fa-li" :icon="['fas', 'check']"/>Spring Boot Framework
                </li>
                <li>
                    <font-awesome class="fa-li" :icon="['fas', 'check']"/>Artificial Intelligence Basics
                </li>
            </ul>
        </div>
    </section>
</template>
