<template>
    <div class="app">
        <div class="panel">
          <div class="depositAmount">
            <h1>Deposit Amount</h1>
            <div class="input-group">
              <input type="number" class="form-control" placeholder="Enter Amount" aria-label="Enter Amount" aria-describedby="basic-addon2">
              <div class="input-group-append">
                <button class="btn btn-outline-secondary" type="button">Deposit</button>
                <button class="btn btn-outline-secondary" type="button">Leverage</button>
              </div>
            </div>
          </div>
          <div class="stats">
            <h2>Stats for </h2>
              <div>Ethereum Balance: <span></span></div>
              <div>Depostied Amount: <span></span></div>
              <div>Yield Amount: <span></span></div>
              <div>Pool Balance: <span></span></div>
          </div>
        </div>
    </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
body {
    background: linear-gradient(171.08deg,#010101 -11.16%,#141921 6.1%,#0a0d11 49.05%,#000000 93.22%) no-repeat fixed;
    color: #f5f5f5;
}
</style>
<style scoped>
.panel {
  background-color:#141921;
  border-radius: 10px;
  border: 1px solid white;
  width: 500px;
  min-height: 500px;
  margin: 20vh auto;
  padding: 2rem;
}

input {
  border: 1px solid #f5f5f5;
  border-radius: 5px;
  padding: 1rem;
  background-color: #141921;
  color: #f5f5f5;
  width: 90%;
}

.btn-outline-secondary {
  border: 1px solid #f5f5f5;
  border-radius: 5px;
  padding: 1rem;
  background-color: #141921;
  color: #f5f5f5;
  margin: 1rem 1rem;
}
</style>