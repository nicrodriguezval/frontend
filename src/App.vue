<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container">
        <div class="col">
          <h2>
            <a href="/"><i class="fas fa-wallet"></i> UN Wallet</a>
            <span class="float-right">
                <div>
                  <router-link :to="{ name: 'login' }"><b-button variant="outline-primary">Log in</b-button></router-link>
                  <router-link :to="{ name: 'signup' }"><b-button variant="outline-primary">Sign up</b-button></router-link>
                </div>
            </span>
          </h2>
        </div>
      </div>
    </nav>

    <br>
    <div class="container">
        <div class="row">
            <div class="col">
                <img src="../public/homeimg.jpg" alt="responsive image">      
            </div>
            <div class="col">
                <div class="card">
                    <div class="card-header bg-primary text-white text-center">
                        <h3>
                            UN wallet advantages
                        </h3>
                    </div>
                    <div class="card-body">
                        <ul>
                            <li>Easy registration</li>
                            <li>Save and recive money</li>                 
                            <li>Recharge your money</li>
                            <li>Save time with UNWallet</li>
                            <li>Fast and secure transactions</li>
                            <li>Make payments to merchants and banks</li>
                            <li>mmediate availability of your money</li>                                              
                            <li>Money on hand without cash</li>                            
                        </ul>
                    </div>
                </div>
            </div>            
        </div>
    </div>
    <br>
    <router-view/>
  </div>
</template>

<script>

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
