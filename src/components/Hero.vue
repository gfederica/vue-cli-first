<template>
    <div class="container">
        <div class="overlay"></div>
        <Title/>
        <Button/>
    </div>
</template>


<script>

import Title from './Title'
import Button from './Button'


export default {
  name: 'App',
  components: {
    Title,
    Button
  }
}

</script>



<style scoped>
    .container {
        height: 97vh;
        background-image: url('https://media1.thehungryjpeg.com/thumbs2/ori_43956_0bd485bb5945247ebdf26228d5ee35ef70e66b45_seamless-geometric-minimal-patterns.jpg');
        background-size: 50%;
        position: relative;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

    }
    .overlay {
        content:"";
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(255, 255, 255, 0.6);
        z-index: 1;
    }
    
</style>
