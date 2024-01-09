<script></script>

<template>
  <div class="container">
    <h2>Game Dev Leaderboard</h2>

    <div class="buttons">
      <button>Rank 1-5</button><button>Rank 6-10</button><button>Rank 11-15</button>
    </div>

    <div class="rank1-5">
      <div class="1">1. Danny Chen</div>
      <div class="2">2. Leo Yang</div>
      <div class="3">3. Evan Gao</div>
      <div class="4">4. Jack Shen</div>
      <div class="5">5. Jason Shi</div>
    </div>
    <div class="rank6-10">
      <div class="6">6. Ching Chen</div>
      <div class="7">7. Ming Yang</div>
      <div class="8">8. Xiao Mai Nu</div>
      <div class="9">9. literally the goat</div>
      <div class="10">10. leo is the goat</div>
    </div>
    <div class="rank11-15">
      <div class="11">11. Chen</div>
      <div class="12">12. Yang</div>
      <div class="13">13. Xiao</div>
      <div class="14">14. goat</div>
      <div class="15">15. the goat</div>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 1rem;
  backdrop-filter: blur(10px);
}
.buttons {
  display: flex;
  flex-direction: row;
  padding: 1rem;
}
button {
  display: inline-block;
  margin: 5px;
  padding: 0.75rem 1rem;
  border: 1px solid transparent;
  border-radius: 10px;
  background-color: var(--vt-c-red);
  color: white;
  font-weight: 400;
}
</style>
