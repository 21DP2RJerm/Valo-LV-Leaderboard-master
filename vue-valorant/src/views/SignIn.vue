
<template>
    <div id="Signin">
        <h1>Sign in</h1>
        <form>
            <label for="Username" id="text">Username:</label>
            <input type="text" id="textbar" name="Username"><br>
            <br><br><br>
            <label for="Password" id="text">Password:</label>
            <input type="text" id="textbar" name="Password">
        </form> <br><br><br>
        <button id="signin">Sign in</button>
    </div>
    <img src="../assets/valorantbck.jpg" alt="background" id="background">

</template>
<script>

</script>
<style>

#Signin{
    position: absolute;
    width: 50vh;
    height: 60vh;
    background-color: transparent;
    left: 20%;
    top: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    
    border-radius: 50px;
}
#background{
    margin: 0;
    padding: 0;
    width: 100%;

  }
#textbar{
    border-radius: 50px;
    border: none;
    background-color:#212529;
    height: 3vh;

}
#text{
    padding: 25px;
}
#signin{
    background-color: white;
    width: 9vh;
    height: 3vh;
    border-radius: 50px;
    border-color: black solid;
    
}

</style>