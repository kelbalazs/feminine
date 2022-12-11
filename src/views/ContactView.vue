<template>
    <div>
    <form action="https://formsubmit.co/femininetothrive@gmail.com" method="POST" target="_blank">
  <input name="name" type="text" class="feedback-input" placeholder="Name" />   
  <input name="email" type="text" class="feedback-input" placeholder="Email" />
  <input name="subject" type="text" class="feedback-input" placeholder="Subject" />

  <textarea name="text" class="feedback-input" placeholder="Message"></textarea>
  <input type="submit" value="SUBMIT"/>
</form> 
    </div>
</template>

<style scoped>

body { background:rgb(30,30,40); }
form { max-width:420px; margin:50px auto; }

.feedback-input {
  color: black;
  font-family: 'Open Sans';
  font-weight:500;
  font-size: 18px;
  border-radius: 5px;
  line-height: 22px;
  background-color: transparent;
  border:2px solid #985277;
  transition: all 0.3s;
  padding: 13px;
  margin-bottom: 15px;
  width:100%;
  box-sizing: border-box;
  outline:0;
}

.feedback-input:focus { border:2px solid #CC4949; }

textarea {
  height: 150px;
  line-height: 150%;
  resize:vertical;
}

[type="submit"] {
  font-family: 'Open Sans Regular';
  width: 100%;
  background:#F1D0E5;
  border-radius:5px;
  border:0;
  cursor:pointer;
  color: black;
  font-size:24px;
  padding-top:10px;
  padding-bottom:10px;
  transition: all 0.3s;
  margin-top:-4px;
  font-weight:700;
}
[type="submit"]:hover { background:#985277; }
</style>