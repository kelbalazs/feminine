<template>
    <div class="footer">
        <div class="wrapper">
  <a href="https://www.facebook.com/FemininetoThrive" target="_blank" class="icon facebook">
    <div class="tooltip">Facebook</div>
    <span><i class="fab fa-facebook-f"></i></span>
  </a>
  <a href="https://www.youtube.com/channel/UCA6-S8XTj87OXsN5981UHLg" target="_blank" class="icon youtube">
    <div class="tooltip">Youtube</div>
    <span><i class="fab fa-youtube"></i></span>
  </a>
  <a href="https://www.instagram.com/femininetothrive/" target="_blank" class="icon instagram">
    <div class="tooltip">Instagram</div>
    <span><i class="fab fa-instagram"></i></span>
  </a>
  <a href="mailto:femininetothrive@gmail.com" class="icon email">
    <div class="tooltip">Email</div>
    <span><i class="fa fa-envelope"></i></span>
  </a>
</div>
        
    </div>
</template>

<style scoped>

.footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  background-color:#EB9BC3	;
  color: white;
  text-align: center;
}

.wrapper .icon{
  position: relative;
  background-color: #ffffff;
  border-radius: 50%;
  margin: 10px;
  width: 50px;
  height: 50px;
  line-height: 50px;
  font-size: 22px;
  display: inline-block;
  align-items: center;
  box-shadow: 0 10px 10px rgba(0, 0, 0, 0.1);
  cursor: pointer;
  transition: all 0.2s cubic-bezier(0.68, -0.55, 0.265, 1.55);
  color: #333;
  text-decoration: none;
}
.wrapper .tooltip {
  position: absolute;
  top: 0;
  line-height: 1.5;
  font-size: 14px;
  background-color: #ffffff;
  color: #ffffff;
  padding: 5px 8px;
  border-radius: 5px;
  box-shadow: 0 10px 10px rgba(0, 0, 0, 0.1);
  opacity: 0;
  pointer-events: none;
  transition: all 0.3s cubic-bezier(0.68, -0.55, 0.265, 1.55);
}
.wrapper .tooltip::before {
  position: absolute;
  content: "";
  height: 8px;
  width: 8px;
  background-color: #ffffff;
  bottom: -3px;
  left: 50%;
  transform: translate(-50%) rotate(45deg);
  transition: all 0.3s cubic-bezier(0.68, -0.55, 0.265, 1.55);
}
.wrapper .icon:hover .tooltip {
  top: -45px;
  opacity: 1;
  visibility: visible;
  pointer-events: auto;
}
.wrapper .icon:hover span,
.wrapper .icon:hover .tooltip {
  text-shadow: 0px -1px 0px rgba(0, 0, 0, 0.1);
}
.wrapper .facebook:hover,
.wrapper .facebook:hover .tooltip,
.wrapper .facebook:hover .tooltip::before {
  background-color: #3b5999;
  color: #ffffff;
}
.wrapper .youtube:hover,
.wrapper .youtube:hover .tooltip,
.wrapper .youtube:hover .tooltip::before {
  background-color: #FF0000;
  color: #ffffff;
}
.wrapper .instagram:hover,
.wrapper .instagram:hover .tooltip,
.wrapper .instagram:hover .tooltip::before {
  background-color: #e1306c;
  color: #ffffff;
}


.wrapper .email:hover,
.wrapper .email:hover .tooltip,
.wrapper .email:hover .tooltip::before {
  background-color: #de463b;
  color: #ffffff;
}
</style>