<template>
  <header>
    <nav>
      <section class="header">
        <div class="grid-item border-bottom">1</div>
        <div class="grid-item border-left border-right border-bottom">2</div>

        <div class="grid-item border-left border-right border-bottom">3</div>
        <div class="grid-item border-left border-right border-bottom">4</div>
        <div class="grid-item border-bottom">5</div>
        <div class="grid-item border-left border-bottom">6</div>
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
  padding: 10px;
  background-color: #202020;
}
.grid-item {
  padding: 20px;
  font-size: 12px;
  text-align: center;
}

.border-left {
  border-left: 1px solid gray;
  position: relative;
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
</style>
