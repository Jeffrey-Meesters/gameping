<template>
    <div class="game-category">
        <h1>Category1</h1>
        <ul class="game-list">
            <CardsListItem />
            <CardsListItem />
            <CardsListItem />
            <CardsListItem />
            <CardsListItem />
        </ul>
    </div>
    <div class="game-category">
        <h1>Category2</h1>
        <ul class="game-list">
            <CardsListItem />
            <CardsListItem />
            <CardsListItem />
            <CardsListItem />
            <CardsListItem />
        </ul>
    </div>
</template>

<script>
import CardsListItem from "../components/game-card/CardListItem"

export default {
    name: "Home",
    components: {
        CardsListItem
    }
}
</script>

<style lang="scss" scoped>
    .game-list {
        display: flex;
        justify-content: space-around;
    }
</style>
