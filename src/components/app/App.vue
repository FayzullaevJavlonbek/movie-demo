<template>
<div class="app font-monospace">
    <div class="content">
        <AppInfo />
        <div class="search-panel">
            <SearchPanel />
            <AppFilter />
        </div>
        <MovieList />
        <MovieAddForm />

    </div>
</div>
</template>
<script>
import AppInfo from '@/components/app-info/AppInfo.vue'
import SearchPanel from '@/components/search-panel/SearchPanel.vue'
import AppFilter from '@/components/app-filter/AppFilter.vue'
import MovieList from '@/components/movie-list/MovieList.vue'
import MovieAddForm from '@/components/movie-add-form/MovieAddForm.vue'
export default{
    components: {
        AppInfo,
        SearchPanel,
        AppFilter,
        MovieList,
        MovieAddForm
    },
}
</script>
<style>
.app{
    color: black;
}
.content{
    width: 50%;
    min-height: 700px;
    background-color: rgb(232, 213, 189);
    margin: auto;
    padding: 10rem 5rem;
}
.search-panel{
    margin-top: 2rem;
    padding: 1.5rem;
    background-color: #fcfaf5;
    border-radius: 4px;
    box-shadow: 15px 15px 15px rgb(0, 0, 0, 0.2);
}
</style>