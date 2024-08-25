*{
    padding: 0px;
    margin: 0px;
    font-family:  "Sofia", sans-serif;
    
}



.nav{
    font-family: "Outfit", sans-serif;
    font-optical-sizing: auto;
    font-weight: 100;
    font-style: normal;
    display: flex;    
    justify-content: space-between;
    align-items: center;
    padding: 20px 10px;
    color: black;
    width: 100%;
    z-index: 1;
    background-color: white;
    position: fixed;
    top: 0px;
    
}
.logo{
    display: flex;
    font-style: Verdana;
    font-size: 30px;
    background-color: burlywood;
    padding: 10px;
    cursor: pointer;
}
.nav a{
    text-decoration: none;
    margin: 0px 30px;
    color: black;
    font-size: 20px;
    transition: 0.5s;
}
.nav a:hover{
    transform: scale(-1.5);
    color: rgb(255, 255, 0);
}

.d1{
    color: black;
    transform: rotateZ(-30deg);
    margin-right: 10px;
    font-weight: bolder;
    transition: 1s;
}
.d1:hover{
    transform: scale(1.1);
}
.d2{
    color: darkseagreen;
    margin-right: 10px;
    font-weight: bolder;
    transition: 1s;
}
.d2:hover{
    transform: scale(1.5);
}
.d3{
    color: olivedrab;
    margin-right: 10px;
    font-weight: bolder;
    transition: 1s;
}
.d3:hover{
    transform: scale(1.1);
}
.d4{
    color: teal;
    margin-right: 10px;
    font-weight: bolder;
    transition: 1s;
}
.d4{
    transform: scale(1.2);
}
.d5{
    color: salmon;
    font-weight: bolder;
    transition: 1s;
    
}
.d5:hover{
    transform: scale(1.2);
}
.b1{
    padding: 10px;
    border-radius: 10px;
    background-color: black;
    color: white;
    font-size: 20px;
    transition: 2s;
}
.b1:hover{
    transform: scale(1.1);
}

.div1{
    padding: 10px 30px;
    margin-top: 20px;
    
}
.div11{
    padding: 20px 0px;
    font-size: 30px;
    margin: 0px 5px;
}
.div12{
    display: flex;
    justify-content: space-between;
    scale: 0.95;
    

}
#img{
    margin-top: 10px;
    scale: 1.5;
}
#div1{
    width: 350px;
    height: 500px;
    border: solid 1px black;
    display: flex; 
    flex-direction: column; 
    padding-top: 0px;
    align-items: center;
    border-radius: 30px;
    box-shadow: black;
    border: none;
    background-color: aliceblue;
    transition: 0.5s;
}
#div1:hover{
    
    translate: -2px -5px 0px;
    box-shadow: 10px 10px black;
    padding-right: 5px;
}
.img{
    height: 320px;
    width: 230px;
    padding: 5px;
}
#p1{
    font-size: 20px;
    font-weight: bold;
    margin-top: 10px;
}
#p2{
    font-size: 15px;
    
}
 .mode{
    display: flex;
    background-color: transparent;
 }
 .mode select{
    font-size: 16px;
    border: none;
 }
 .mode option{
    background-color: white;
    width: 300px;
    font-size: 20px;
    padding: 10px;
    margin: 10px;
 }
 .bottombuttons{
    display: flex;
    align-items: end;
    justify-content: space-around;
    width: 100%;
    height: 100%;
    padding-bottom: 20px;
   
 }
 .b2{
    padding: 20px 40px;
    border-radius: 30px;
    background-color: black;
    color: white;
    transition: 1s;
    border: solid 2px white;
 }
 .b2:hover{
    background-color: whitesmoke;
    color: black;
    border: solid 2px black;
    translate: -2px -5px 0px;
    box-shadow: 6px 8px black;
 }
 .b2:active{
    box-shadow: none;
    translate: 0px 0px 0px;
    
 }
 .b3{
    padding: 20px 50px;
    border-radius: 30px;
    font-weight: bold;
    background-color: yellow;
    border: solid 2px rgb(0, 0, 0);
    transition: 1s;
  
 }
 .b3:hover{
    background-color: white;
    border: solid 2px yellow;
    color: rgb(0, 0, 0);
    translate: -2px -5px 0px;
    box-shadow: 6px 8px black;
 }
 .b3:active{
    box-shadow: none;
    translate: 0px 0px 0px;
 }
 .like{
    position: relative;
    top: -418px;
    right: -130px;
    cursor: pointer;
    transition: 1s;
    width: -1px;
    height: 49px;
    border-radius: 50px;
    
 }
 .like:hover{
    translate: -2px -5px 0px;
    box-shadow: 6px 8px black;
    background-color: red;
 }
 .like:active{
    box-shadow: none;
    translate: 0px 0px 0px;
 }
 .break1{
    height: 50px;
 }
 #price{
    font-size: 30px;
 }
 #t1{
    width: 176px;
    height: 40px;
    padding: 0px 0px 0px 32px;
    border-radius: 10px;

 }
 #i1{
    position: relative;
    right: 208px;
    top: 6px;

 }


.div11{
  font-family: "Montserrat", sans-serif;
  font-optical-sizing: auto;
  font-weight: 500;
  font-style: normal;
}
button{
    cursor: pointer;
}  
img{
    cursor: grab;
    transition: 2s;
}
img:hover{
    transform: rotateY(180deg);

}
.like img:hover{
    transform: none;    
}
