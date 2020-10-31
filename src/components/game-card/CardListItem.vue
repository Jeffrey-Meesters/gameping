<template>
    <li class="card-list-item">
        <a href="">
            <img src="#" alt="game-card-image">
            <h3>Game title</h3>
            <p>game excerpt</p>
        </a>
    </li>
</template>

<style lang="scss">
.card-list-item {
    min-width: 200px;
    list-style: none;
    border: 1px solid grey;
    margin: 5px;
    
    a {
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: center;
    }
}
</style>
