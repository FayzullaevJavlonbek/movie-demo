<template>
    <ul class="movie-list list-group">
        <MovieListItem />
        <MovieListItem />
        <MovieListItem />
        
    </ul>
</template>
<script>
import MovieListItem from '@/components/movie-list-item/MovieListItem.vue'
export default {
    components: {
        MovieListItem,
    }
}
</script>
<style>
.movie-list{
    margin-top: 2rem;
    padding: 1.5rem;
    background-color: #fcfaf5;
    border-radius: 4px;
    box-shadow: 15px 15px 15px rgb(0, 0, 0, 0.2);
}
</style>