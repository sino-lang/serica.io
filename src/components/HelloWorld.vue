<template>
  <div class="container">
    <div class="search-form">
      <input type="text" placeholder="Search packages...">
      <button>Search</button>
    </div>
    <div class="featured-packages">
      <h2>Featured Packages</h2>
      <div class="package-list">
        <div class="package-item">
          
          <h3>rand</h3>
          <p>Random number generators and other randomness functionality.</p>
          <a href="#">Learn more</a>
        </div>
        <div class="package-item">
          
          <h3>tokio</h3>
          <p>An event-driven, non-blocking I/O platform for writing asynchronous I/O backed applications.</p>
          <a href="#">Learn more</a>
        </div>
        <div class="package-item">
          
          <h3>request</h3>
          <p>higher level HTTP client library</p>
          <a href="#">Learn more</a>
        </div>
      </div>
    </div>
    <div class="popular-tags">
      <h2>Popular Tags</h2>
      <div class="tag-list">
        <a href="#">#web</a>
        <a href="#">#num</a>
        <a href="#">#sec</a>
        <a href="#">#net</a>
      </div>
    </div>
  </div>
</template>

<style>
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

.search-form {
  display: flex;
  justify-content: center;
  margin-bottom: 40px;
}

.search-form input[type="text"] {
  width: 60%;
  padding: 10px;
  font-size: 16px;
  border: none;
  border-radius: 5px 0 0 5px;
}

.search-form button {
  background-color: #007fff;
  color: white;
  padding: 10px 20px;
  font-size: 16px;
  border: none;
  border-radius: 0 5px 5px 0;
  cursor: pointer;
}

.featured-packages {
  margin-bottom: 40px;
}

.package-list {
  display: flex;
  justify-content: space-between;
}

.package-item {
  width: 30%;
  background-color: #f2f2f2;
  padding: 20px;
  border-radius: 5px;
  text-align: center;
  box-shadow: rgba(0, 0, 0, 0.1) 0 4px 12px;
}

.package-item img {
  max-width: 80%;
  margin-bottom: 20px;
}

.package-item h3 {
  font-size: 24px;
  margin-bottom: 10px;
}

.package-item p {
  margin-bottom: 20px;
}

.package-item a {
  color: #007fff;
}

.popular-tags .tag-list {
  display: flex;
  flex-wrap: wrap;
}

.popular-tags a {
  display: inline-block;
  margin-right: 10px;
  margin-bottom: 10px;
  padding: 5px 10px;
  background-color: #f2f2f2;
  color: #007fff;
  border-radius: 5px;
  text-decoration: none;
}
</style>
