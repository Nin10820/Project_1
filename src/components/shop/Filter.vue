<template>
  <div class="filter">
    <div class="filter-head filter-item">
      <span>Category</span>
      <i class="fas fa-bars"></i>
    </div>
    <div class="filter-list">
      <li class="filter-item">
        <span>Vegetable</span>
        <i class="fas fa-carrot"></i>
      </li>
      <li class="filter-item">
        <span>Vegetable</span>
        <i class="fas fa-carrot"></i>
      </li>
      <li class="filter-item">
        <span>Vegetable</span>
        <i class="fas fa-carrot"></i>
      </li>

      <li class="filter-item">
        <span>Vegetable</span>
        <i class="fas fa-carrot"></i>
      </li>
      <li class="filter-item">
        <span>Vegetable</span>
        <i class="fas fa-carrot"></i>
      </li>
      <li class="filter-item">
        <span>Vegetable</span>
        <i class="fas fa-carrot"></i>
      </li>
      <li class="filter-item">
        <span>Vegetable</span>
        <i class="fas fa-carrot"></i>
      </li>
    </div>
  </div>
</template>
<style lang="scss">
.filter {
  .filter-item {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  &-head {
    border: 1px solid #919aa3;
    border-radius: 5px;
    padding: 0.8em 1em;
  }
  &-list {
    margin-top: 0.5em;
    li {
      cursor: pointer;
      padding: 1em;
      list-style: none;
      color: #919aa3;
      border-bottom: 1px solid #e8e8e8;
      transition: 0.2s;
    }
    li:hover {
      color: #2fd4ec;
    }
  }
}
</style>