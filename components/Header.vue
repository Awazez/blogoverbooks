<template>

<div class="container">
        <h1>Overbooks</h1>   

        <div class="container-photo">
          <img src="../assets/img.jpg" >
          <p>
            <span>Blog personnel de <span style="color:#FFA7C4">Martin AUBEUT</span> <br>
            J’explique le monde des bibliothèques</span>
          </p>
          
        </div>


</div>
</template>

<script setup>

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@800&display=swap');
h1 {
    color: white;
    font-size: 42px;
    font-family: 'Montserrat', sans-serif;
}

img {
  width: 100px;
  height: 100px;
  border-radius: 50%;
}

p {
  width: 300px;
  height: 100px;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
}


.container {
  margin-left: 200px;
  margin-right: auto;
  width: 120px;
}

.container-photo {
  width: 500px;
  height: 100px;
  display: flex;
  align-items: center;
}

</style>
