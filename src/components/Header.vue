<template>
    <b-navbar toggleable="lg" pills variant="dark">
        <b-navbar-brand href="#main">Samuel</b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
            <b-nav-item href="#aboutme">About Me</b-nav-item>
            <b-nav-item href="#skills">Skills</b-nav-item>
            <b-nav-item href="#experience">Experience</b-nav-item>
            <b-nav-item href="#personalprojects">Projects</b-nav-item>
            <b-nav-item href="#contact">Contact</b-nav-item>
        </b-collapse>
    </b-navbar>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    li {
        list-style-type: none;
    }
    .nav-link {
        color: #6ad4b1;            
        text-decoration: none;
        
    }
    .navbar {
        color:#6ad4b1;
        /* background-color:black; */
    }
    .navbar-light .navbar-brand {
        color: #6ad4b1;
    }
</style>