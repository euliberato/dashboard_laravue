<script>
export default {
    name: 'NavbarDashboard',
    methods: {
        logout(){
            this.$router.push({name: 'login'});
        }
    }
}
</script>

<template>
    <div class="navbar">
        <h3 class="logo"><i class="fa fa-star"></i> Startup Dev</h3>
        <a href="" class="logout" @click.prevent="logout"><i class="fa-solid fa-right-from-bracket"></i> Sair</a>
    </div>
</template>

<style lang="scss">

.navbar {
    .logo {
        color: #fff;
    }

    .logout {
        color: #fff;
        text-decoration: none;
    }
}

</style>