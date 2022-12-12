<script>
export default {
    name: 'SidebarDashboard'
}
</script>

<template>
    <div class="sidebar">
        <div class="top">
            <div class="avatar">
                <span><i class="fa fa-user"></i></span>
            </div>
            <div class="info">
                <p class="name">Ruan</p>
                <p class="status">Online</p>
            </div>
        </div>
        <div class="menu">
            <ul>
                <li>Menu</li>
                <li>Dados</li>
                <li>Calcular</li>
                <li>Adicionar</li>
                <li>Remover</li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss">

.sidebar {
    .top {
        width: 100%;
        display: flex;
        justify-content: center;
        padding: 25px 5px;
        margin-top: 10px;

        .avatar {
            margin-right: 10px;

            span {
                display: block;
                width: 50px;
                height: 50px;
                border-radius: 50%;
                background-color: #999;
                display: flex;
                justify-content: center;
                align-items: center;
                font-size: 25px;
                color: #fff;
            }
        }

        .info {
            display: flex;
            flex-direction: column;
            justify-content: center;

            p {
                margin: 0;
                color: #fff;
            }

            .name {
                font-size: 14px;
            }

            .status {
                font-size: 10px;
                color: green;
            }

        }
    }

    .menu {
        color: #fff;

        ul {
            list-style: none;
            display: flex;
            flex-direction: column;

            li {
                margin-top: 30px;
                transition: .3s;
            }

            li:hover {
                background-color: #999;
                color: #000;
                border-radius: 10px 0 0 10px;
                padding: 10px 5px;
            }
        }
    }
}
</style>