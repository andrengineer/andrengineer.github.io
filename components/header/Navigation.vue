<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container">
            <NuxtLink class="navbar-brand green" to="/">
                <img src="https://andrengineer.github.io/images/logo.png" alt="Andrengineer" width="30">ndrengineer
            </NuxtLink>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                    <NuxtLink class="nav-link" aria-current="page" to="/about">Acerca</NuxtLink>
                </li>
            </ul>
            </div>
        </div>
    </nav>
</template>