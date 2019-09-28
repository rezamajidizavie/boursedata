<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light" style="position:absolute;width:100%">
    <a class="navbar-brand" href="#">بورس تحلیل</a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#">
            صفحه اصلی
            <span class="sr-only">(current)</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">ورود</a>
        </li>
        <li class="nav-item dropdown">
          <a
            class="nav-link dropdown-toggle"
            href="#"
            id="navbarDropdown"
            role="button"
            data-toggle="dropdown"
            aria-haspopup="true"
            aria-expanded="false"
          >فهرست مطالب</a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">فهرست نماد ها</a>
            <a class="dropdown-item" href="#">فهرست تحلیل ها</a>
            <a class="dropdown-item" href="#">نمودار سهام</a>
          </div>
        </li>
      </ul>
      <form class="form-inline my-2 my-lg-0 justify-content-center">
        <input
          class="form-control mr-sm-2"
          type="search"
          placeholder="جستجو..."
          aria-label="Search"
        />
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">جستجو</button>
      </form>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
  props: {
    msg: String
  }
};
</script>

<style scoped>
</style>
