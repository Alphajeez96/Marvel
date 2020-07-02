<template>
   <header>
    <nav>
      <section class="header">
          <div class="grid-item"><div class="grid-items">1 </div></div>
            <div class="grid-item">1</div>
              <div class="grid-item">1</div>
             
      </section>
    </nav>
   </header>
</template>

<style scoped>

.header {
    display: grid;
    grid-template-columns: auto auto auto;
    padding: 10px;
}
.grid-item {
  background-color: rgba(255, 255, 255, 0.8);

  padding: 20px;
  font-size: 30px;
  text-align: center;
}
.grid-items {
  background-color: rgba(255, 255, 255, 0.8);
  padding: 20px;
    border: 1px solid rgba(0, 0, 0, 0.8);
  font-size: 30px;
  text-align: center;
}


</style>