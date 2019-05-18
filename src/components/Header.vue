<template>
  <div class="header">
    <h1>KAZUKI'S PORTFOLIO</h1>
    <p>Web Engineer</p>
    <ol>
      <a href="#about">About</a>
      <a href="#works">Works</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </ol>
  </div>
</template>

<script>
</script>

<style scoped>
h1 {
  margin: 50px 0 40px;
  font-size: 7.6rem;
}
ol {
  padding: 0;
}
p {
  margin: 0 0 30px;
  letter-spacing: 1px;
  font-size: 2.2rem;
}
a {
  display: inline-block;
  width: 200px;
  padding: 20px;
  border-radius: 4px;
  color: #fff;
  text-decoration: none;
  letter-spacing: 1px;
  font-size: 2.2rem;
}
a:hover {
  opacity: 0.9;
}
.header {
  padding: 170px 30px 80px;
}
@media (max-width: 768px) {
  .header {
    padding-top: 60px;
  }
  h1 {
    font-size: 5rem;
  }
  p {
    font-size: 1.7rem;
  }
  a {
    font-size: 1.5rem;
  }
}
</style>
