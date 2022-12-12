<script>
import SidebarDashboard from './SidebarDashboard.vue';
import NavbarDashboard from './NavbarDashboard.vue';

export default {
    name: "DashboardComponent",
    components: {
        SidebarDashboard,
        NavbarDashboard
    }
}
</script>

<template>
    <div class="main">
        <div class="sidebar">
            <SidebarDashboard/>
        </div>
        <div class="content-right">
            <div class="navbar">
                <NavbarDashboard/>
            </div>
            <div class="pages">
                
            </div>
        </div>
    </div>
</template>

<style lang="scss" src="./DashboardComponent.scss" scoped/>