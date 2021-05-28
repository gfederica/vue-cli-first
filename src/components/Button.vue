<template>
    <div class="button">
        <button><a href="https://cli.vuejs.org/">Scarica la documentazione</a></button>
        <button><a href="https://github.com/gfederica">GitHub</a></button>
    </div>
</template>


<script>

export default {
  name: 'Button'
}
</script>


<style>
    button {
        background-color:white;
        border: none;
        border-radius: 10px;
        margin: 10px 20px;
        padding: 10px;
    }
    button a {
        text-decoration: none;
    }
    button:hover {
        cursor: pointer;
        background-color: lightsteelblue;
        font-weight: bold;
    }
    .button {
        z-index: 2;  
        margin: 10px; 
    }
</style>