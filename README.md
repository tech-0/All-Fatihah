<!DOCTYPE html>
<html lang="en">
<head>

  <script type="module" src="https://cdn.jsdelivr.net/npm/@ionic/core@4.7.4/dist/ionic/ionic.esm.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

  <script nomodule src="https://cdn.jsdelivr.net/npm/@ionic/core@4.7.4/dist/ionic/ionic.js"></script>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@ionic/core@4.7.4/css/ionic.bundle.css"/>

<style>
.button {
  background-color: #4CAF50; /* Green */
  border: none;
  color: white;
  padding: 10px 100px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin-top: auto;
  margin-bottom: 0px;
  transition-duration: 0.3s;
  cursor: pointer;
 
}

.button2 {
  background-color: white; 
  color: black; 
  border: 2px solid #008CBA;

}

.button2:hover {
  background-color: #008CBA;
  color: white;
}

.char{
  text-shadow: 0 0 3px #FF0000;
  text-align: center;
  animation-name: dorkn;
  animation-duration: 3s;
  animation-iteration-count: infinite;
  position:relative;
}

@keyframes dorkn{
10%{color:red;transform:scale(2,01);}
20%{color:skyblue;}
30%{color:yellow;}
  
  
}

  </style>
  
</head>

<body>

    <ion-content fullscreen>
      <ion-card class="card" color="">

        <ion-card-header>
<h1 class="char">CHARA</h1>
<br>
<a href="#" class="button button2">Blue</a>
<br>
<br>
<br>
<a href="#" class="button button2">Blue</a>

</body>
</html>
