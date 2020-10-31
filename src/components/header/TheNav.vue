<template>
    <div class="header">
        <div>
            logo
        </div>
        <nav>
            <ul class="nav-item-list">
                <li class="nav-item">
                    <router-link to="">Start</router-link>
                </li>
                <li class="nav-item">
                    <router-link to="">Puzzel</router-link>
                </li>
                <li class="nav-item">
                    <router-link to="">Arcade</router-link>
                </li>
                <li class="nav-item">
                    <router-link to="">Sociaal</router-link>
                </li>
                <li class="nav-item">
                    <router-link to="">Bord</router-link>
                </li>
                <li class="nav-item">
                    <router-link to="">Avontuur</router-link>
                </li>
                <li class="nav-item">
                    <router-link to="">Kaarten</router-link>
                </li>
                <li class="nav-item">
                    <router-link to="">Behendigheid</router-link>
                </li>
                <li class="nav-item">
                    <router-link to="">etc...</router-link>
                </li>
            </ul>
        </nav>
    </div>
</template>

<style lang="scss" scoped>
.header {
    align-items: center;

    nav {
        width: 90vw;
        
        .nav-item-list {
            display: flex;
            justify-content: space-around;
        }
    }
}

</style>
