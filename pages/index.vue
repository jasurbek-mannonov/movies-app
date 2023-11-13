<script setup>
const searchError = ref(false);
const searchMovie = (searchInput) => {
    // console.log("Search Input: ", searchInput)
    if(searchInput === ""){
        searchError.value = true;
    }
    if(searchInput !== ""){
        searchError.value = false;
    }
};
</script>

<template>
    <div>
        <SearchBar @search-movie="searchMovie" :searchError="searchError"/> 
    </div>
</template>