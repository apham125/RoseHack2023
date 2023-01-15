<template>
    <nav>
        <!-- <div id="everything"> -->
            <div id="logo">
                R
                <a href="#" ><img src="../assets/roselogo.png"></a> 
                seBuds
            </div>
            
            <div id="text">
                <RouterLink to="/">Home</RouterLink>
                <RouterLink to="/about">About</RouterLink>
            </div>
        <!-- </div> -->
    </nav>
</template>

<style>
nav {
    width: 100%;
    background-color: #1C0D18;
    display: flex;
    justify-content: space-between;
    
}

#logo {
    /* background-color: red; */
    color: #ffff;
    font-weight: 200;
}

#text {
    /* background-color: blue; */
    text-align: right;
}

</style>