<template>
    <nav class="navbar" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
            <a class="navbar-item" href="https://bulma.io">PhoneApp</a>

            <div class="navbar-menu is-active">
                <router-link  class="navbar-item" to="/home">Home</router-link>
                <router-link  class="navbar-item" to="/about">About</router-link>
            </div>

            <div class="navbar-burger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>
</template>