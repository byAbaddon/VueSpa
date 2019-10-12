<template>
  <div class="registration">
    <h2>Welcome to Registration</h2>

    <section>
      <img id="photo" src="../assets/images/image-photo.jpg" alt />
      <br />
      <br />
      <img src="../assets/images/triangle.png" alt />
      <form action="#">
        <article>
          <h1>Registration form</h1>
          <i class="fas fa-user fa"></i>
          <input class="input" type="text" placeholder="Name" />
          <br />
          <i class="fas fa-unlock"></i>
          <input class="input" type="password" placeholder="******" />
          <br />
          <i class="fas fa-unlock"></i>
          <input class="input" type="password" placeholder="******" />
          <input id="btnSubmit" type="submit" />
        </article>
      </form>
      <p>&copy; 2016 Flat Business Profile Widget. All rights reserved</p>
    </section>
  </div>
</template>






<style scoped  lang="scss">
@import url("https://fonts.googleapis.com/css?family=Oxygen");
@import url("https://use.fontawesome.com/releases/v5.6.3/css/all.css");

* {
  margin: 0;
  padding: 0;
}

.registration {
  background: rgb(146, 112, 87);
  background: cover;
  font-family: "Oxygen", sans-serif;
  text-align: center;
  margin-top: 0em;
  padding: 4.2%;
  color: white;
}

#photo {
  border: 3px solid rgb(213, 195, 149);
}

#tr {
  margin: 5em 0 -5px 0;
}

article {
  background-color: rgb(213, 195, 149);
  width: 30%;
  display: inline-block;
  padding: 30px;
  box-sizing: border-box;
  margin: -1em 0 0 0;
}

h1 {
  padding-bottom: 20px;
  font-weight: 800;
}

input {
    padding: 8px;
    margin-bottom: 25px;
    width: 80%;
    padding-left: 9px;
    position: inherit;
    margin-left: 10px;
}

.fas {
     color: sienna;
    
}

#btnSubmit{
  font-size: bold;
  border: none;
  outline: none;
  padding: 1em 3em;
}

#btnSubmit:hover {
  cursor: pointer;
  background: rgb(146, 112, 87);
  color: white;
}

p {
  margin-top: 1em;
  font-size: 15px;
}

.input {
  background: rgb(233, 240, 196);
  border: none;
  outline: none;
  position:inherit;
}
</style>