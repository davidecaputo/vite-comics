<template>
    <div>
        <div class="d-flex container justify-content-between align-items-center py-4">
          <img src="../../public/img/dc-logo.png" alt="">
          <ul class="d-flex gap-4 w-75 text-uppercase fw-bold">
            <li>Characters</li>
            <li class="active">Comics</li>
            <li>Movies</li>
            <li>Tv</li>
            <li>Games</li>
            <li>Collectibles</li>
            <li>Videos</li>
            <li>Fans</li>
            <li>News</li>
            <li>Shop</li>
          </ul>
        </div>
  </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    li{
        cursor: pointer;

        &::after{
        display: block;
        content: '';
        width: 100%;
        height: 235%;
        border-bottom: 4px solid transparent;
        }

        &:hover, &.active{
            color: #2b82f9;
        }

        &:hover::after, &.active::after{
            border-bottom: 4px solid #2b82f9;
        }
    }
</style>