<div class="header">
    <div class="container">

    <ul class="Nav" >
        
        <li><a href="#" class="active">Home</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact Me</a></li>
        

    </ul>
   
</div>
</div>
<style>
    .container{
    width: 100%;
   
   
    margin: auto;
}
.header{
    background-color: rgba(0, 0,0,0.9);
    height: 100px;
     position:absolute;
     width: 100%;
     z-index: 1;
 }

 .header .Nav{
     width: 60%;
     float: left;
     text-align: right;
     list-style: none;
 }
 .header .Nav> li{
    display: inline-block;
 
    
     text-align: center;
 
 }
 .header .Nav >li >a.active::after,.header .Nav >li >a::after{
 
     content: "";
     display: block;
    margin-top: 2px;
     transition: width .5s;
     height: 3px;
     background-color: #6195ff;
 }
 .header .Nav >li >a::after{
 
     width: 0;
 }
 .header .Nav >li >a.active::after{
     width: 100%;
 }
 
 .header .Nav> li> a:hover::after{
     width: 100%;
 }
 .header .Nav >li >a{
     text-decoration: none;
     color: ghostwhite;
     display: block;
     
     padding: 30px 40px  15px 15px;

     font-size: 18px;
   
 }


</style>