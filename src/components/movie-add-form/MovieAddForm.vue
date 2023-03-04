<template>
    <div class="movie-add-form">
        <h3>Add new movie</h3>
        <form class="add-form d-flex">
            <input type="text" class="form-control new-movie-label" placeholder="Which movie?" />
            <input type="text" class="form-control new-movie-label" placeholder="Number of watched" />
        <button class="btn btn-outline-success" type="submit" >Add</button>
        </form>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
.movie-add-form {
    margin-top: 2rem;
    padding: 1.5rem;
    background-color: #fcfaf5;
    border-radius: 4px;
    box-shadow: 15px 15px 15px rgb(0, 0, 0, 0.2);
} 
</style>