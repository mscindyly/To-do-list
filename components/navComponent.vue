<template>
  <div class="navComponent">
    <div class="nav-bar">
      <h1>Cindy's To Do List</h1>
      <ul>
        <li><a href="#">Work</a></li>
        <li><a href="#">Personal</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">

body {
  padding: 0;
  margin: 0;
}

.navComponent {
  background: #fff9f9;
  height: 100px;
  border: 1px solid#fff0f2;

  .nav-bar {
    display: flex;
    justify-content: space-around;
    color: #998789;

    h1 {
      margin: 0;
      font-size: 25px;
    }

    ul {
      margin: 0px;
      padding: 0px;
    }

    ul li {
      display: inline-flex;
      font-size: 25px;
    }

    a {
      text-decoration: none;
    }
  }

}
</style>

