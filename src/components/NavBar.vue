<script setup lang="ts">


</script>

<template>
<nav class="nav">
        <div class="container">
            <div class="logo">
                <img src="../assets/SpartlogoNoText.png" style="width: 150px; height: auto;" />
            </div>
            <div id="mainListDiv" class="main_list">
                <ul class="navlinks">
                    <li><a href="#">Sign In</a></li>
                </ul>
            </div>
            <span class="navTrigger">
                <i></i>
                <i></i>
                <i></i>
            </span>
        </div>
    </nav>
</template>

<style scoped>

.nav {
    width: 100%;
    height: 65px;
    position: fixed;
    top: 0;
    left: 0;
    line-height: 65px;
    text-align: center;
}

.nav div.logo {
    float: left;
    margin-top: -1.5em;
    width: auto;
    height: auto;
    padding-left: 3rem;
}


.nav div.logo a {
    text-decoration: none;
    color: black;
    font-size: 1.5rem;
}

.nav div.logo a:hover {
    color: #466472;
}

.nav div.main_list {
    height: 65px;
    float: right;
}

.nav div.main_list ul {
    width: 100%;
    height: 65px;
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
}

.nav div.main_list ul li {
    width: auto;
    height: 65px;
    padding: 0;
    padding-right: 3rem;
}

.nav div.main_list ul li a {
    text-decoration: none;
    color: #466472;
    line-height: 65px;
    font-size: 1rem;
}

.nav div.main_list ul li a:hover {
    color: #bbb;
}
</style>