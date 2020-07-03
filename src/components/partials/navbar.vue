<template>
  <header>
    <nav>
      <section class="header">
        <div class="grid-item border-bottom">1</div>
        <div class="grid-item border-left border-right border-bottom">
          <p>nn</p>
        </div>

        <div class="grid-item border-left border-right border-bottom">
          <div class="img"><img src="../../assets/marvel.png" /></div>
        </div>
        <div class="grid-item border-left border-right border-bottom">
          mastercard
        </div>
        <div class="grid-item border-bottom">search</div>
        <div class="grid-item border-left end border-bottom">6</div>
        <div class="grid-item">1</div>
        <div class="grid-item">1</div>
        <div class="grid-item">1</div>
        <div class="grid-item">1</div>
        <div class="grid-item">1</div>
        <div class="grid-item">1</div>
      </section>
    </nav>
  </header>
</template>

<style scoped>
.header {
  display: grid;
  grid-template-columns: 100px 150px auto 150px 100px 100px;
  background-color: #202020;
  max-height: 20vh;

}

.grid-item {
  padding: 20px;
  font-size: 12px;
  text-align: center;
  height: fit-content;
}

.border-left {
  border-left: 1px solid gray;
  position: fixed;
  bottom: 10px;
}
.border-right {
  border-right: 1px solid gray;
}
.border-bottom {
  border-bottom: 1px solid gray;
  position: relative;
  bottom: 10px;
}
.sign__in a {
  font-family: 'Montserrat', sans-serif;
  font-weight: 600;
  color: #edf0f1;
  text-decoration: none;
}
.sign__in {
  list-style: none;
  display: flex;
  text-transform: uppercase;
  font-size: 12px;
}
</style>
