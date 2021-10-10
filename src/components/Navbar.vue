<template>
    <div class="nav">
        <div class="left">
            <div id="logo" class="el">
                Logo
            </div>
            <div id="home" class="el">
                Home
            </div>
            <div id="projects" class="el">
                Projects
            </div>
            <div id="contact" class="el">
                Contact
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Navbar',
}
</script>

<style scoped>
.nav {
    display: flex;
    top:0;
    background-color: black;
}
.left {
    display: flex;
}
.el {
    padding: 20px;
    font-size: 20px;
    color:white;
}
</style>