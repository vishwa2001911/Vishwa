<template>

<div class="Main">
    <div class="Container" style="background-color: aqua;">
        <img src="https://www.sean-lloyd.com/assets/static/20210303-dino-game-6.8cbd2dc.4f377d819706628d9af0659786334303.gif" alt="" class="CoverImage">
        <img src="https://github.com/vishwa2001911/portfolio/blob/main/my.jpg?raw=true" alt="" class="profile">
        <button class="followBtn">
            <span>Follow</span>
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-twitter" viewBox="0 0 16 16">
                <path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z"/>
            </svg>
        </button>

        <div class="detailsBox">
            <h1 class="Name">Vishwa Prabhath</h1>
        </div>
    </div>
</div>
  
</template>

<script>
export default {

}
</script>

<style>

.Name{
    
}

.followBtn{
    width: 100px;
    padding: 8px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    border: none;
    border-radius: 20px;
    color: whitesmoke;
    background-color: #0d6efd;
    position: absolute;
    top: 227px;
    font-weight: bolder;
    right: 100px;
}

.Main{
    width: 100vw;
    
    display: flex;
    justify-content: center;
    align-items: start;
    
}

.CoverImage{
    max-width: 650px;
    height: 200px;
}

.Container{
    min-width: 650px;
    height: 500px;
    background-color: white;
    position: relative;
    
}

.profile{
    width: 120px;
    position: absolute;
    top: 140px;
    left: 80px;
    border-radius: 50%;
    border: solid black 5px;
}

</style>