<template>
<div class = "topdiv" >
<div>
        <div class="header"> 
          <h1>Featured Developers</h1>
        </div>
        
        
<form action="action_page.php" method="post">
  <div class="Home">
      <a href="#/Home" id="Home">Home</a>
       <a href="#/ViewAll" id="ViewAll">ViewAll</a>
      </div>
<br>
<div class = "bgc">
  <div class="imgcontainer">
    <img src="../assets/login.jpg" alt="Avatar" class="avatar">
  </div>

  <div class="container">
    <label for="uname"><b>Username</b></label>
    <br>
    <input type="text" placeholder="Enter Username" name="uname" required>
<br>
    <label for="psw"><b>Password</b></label>
    <br>
    <input type="password" placeholder="Enter Password" name="psw" required>
<br>
    <button class="submit">Login</button>
   
  </div>

  <!-- <div class="container" style="background-color:#f1f1f1">
    <form action="../components/Signup.vue">
    <button type="button" class="signupbutton">Signup</button>
    </form>
  </div> -->

  <div class="footer"> 
      <a>Featured Developer || CopyRight@2021 </a>
      <br>
      <a>Proposal 3B</a>
      <br>
      <a class="link" href="https://github.com/KeerthiMuli/Featured-Developer-Proposal/blob/main/Proposal.md">Proposal ||</a>
      <a class="link" href="https://github.com/KeerthiMuli/Featured-Developer-ThreeB-frontend"> Frontend Repo ||</a>
      <a class="link" href="https://github.com/KeerthiMuli/Featured-Developer-ThreeB-backend"> Backend Repo ||</a>
      <a class="link" href="https://github.com/KeerthiMuli/Featured-Developer-Proposal/projects/1"> Work planning</a>
    </div>
    </div>
    
</form>
</div>
</div>
</template>

<script>
export default {
  name: "Login",
  methods: {
    login() {},
  },
};
</script>

<style scoped>
/* Bordered form */
form {
  border: 3px solid #f1f1f1;
}

.topdiv {
  margin-top: -5%;
  margin-left: -1%;
  margin-right: -1%;
}

/* Full-width inputs */
input[type=text], input[type=password] {
  width: 30%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 2px solid #ccc;
  box-sizing: border-box;
}




/* Set a style for all buttons */
button {
  background-color: rgb(231, 142, 25);
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: 2px solid #ccc;
  cursor: pointer;
  width: 30%;
}

/* Add a hover effect for buttons */
button:hover {
  opacity: 0.8;
}

/* Extra style for the cansignupbutton (red) */
/* .signupbutton {
  width: auto;
  padding: 10px 18px;
  background-color: #f44336;
} */

/* Center the avatar image inside this container */
.imgcontainer {
  text-align: center;
  margin: 24px 0 12px 0;
}

/* Avatar image */
img.avatar {
  width: 10%;
  border-radius: 30%;
}

.header {
  padding: 20px;
  text-align: center;
  background: rgb(231, 142, 25);
  color: white;
  font-size: 30px;
}


/* footer code */

.footer{
  padding: 20px;
  text-align: center;
  background: rgb(231, 142, 25);
  color: white;
  font-size: 15px;
}

.link{
  color:white;
}

.link:hover{
  color:black;
}

/* Add padding to containers */
.container {
  padding: 16px;
}


/* The "Forgot password" text */
span.psw {
  float: right;
  padding-top: 16px;
}

#Home{
  flex: left;
   padding-left: 2% ;
   color: rgb(231, 142, 25);
}


#ViewAll{
  float: right;
   padding-right: 2% ;
   color: rgb(231, 142, 25);
}

/* Change styles for span and signupbutton on extra small screens
@media screen and (max-width: 300px) {
  span.psw {
    display: block;
    float: none;
  } */
  /* .signupbutton {
    width: 100%;
  } */
/* } */
</style>
