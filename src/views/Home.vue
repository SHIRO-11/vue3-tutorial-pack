<template>
    <div class="home">
        <img alt="Vue logo" src="../assets/logo.png" />
        <div id="nav">
            <ul>
                <li><router-link to="/draggable">DraggableTest</router-link></li>
                <li><router-link to="/about">About</router-link></li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: "Home",
    components: {},
};
</script>

<style scoped>
#nav {
    padding: 30px;
}

#nav a {
    font-weight: bold;
    color: #2c3e50;
}

#nav a.router-link-exact-active {
    color: #42b983;
}

ul {
    display: inline-block;
    text-align: left;
}
</style>
