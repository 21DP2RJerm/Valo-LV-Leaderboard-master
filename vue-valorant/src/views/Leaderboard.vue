<script>
import { RouterLink } from 'vue-router';
import header from '../components/Header.vue'; 

export default {
  components: {
    header
  }
}

</script>

<template id="body">
 

    <div id="leaderboard">
        <div id="player">

        </div>
    </div>
    <img src="../assets/valorantbck.jpg" alt="background" id="background">
</template>

<style scoped>
  #body{
    padding: 0;
    margin: 0;


  }

  #background{
    
    margin: 0;
    padding: 0;
    width: 100%;
    max-width: max-content;
   
  }

#leaderboard{
    background-color:#6c757d;
    width: 80vh;
    height: 90vh;
    border: 5px solid #495057;
    position: absolute;
    top: 70%;
    left: 50%;
    transform: translate(-50%, -50%);
    padding: 10px;
    border-radius: 50px;
    box-shadow: 0px 0px 20px 2px black;
}
#player{
    position: inherit;
    width: 76vh;
    height: 10vh;
    background-color: #e9ecef;
    left: 3vh;
    border-radius: 40px;
}
</style>