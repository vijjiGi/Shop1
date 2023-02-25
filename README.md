# Game Controller
In this program we create a website to buy some game controllers..
In this we create navigation bar for logo,features..
Then we add content like headings,paragrapgh,and price of the controllers,button for 'buy now'
Then a image of game controller and a link called 'Add to cart'..and style them
We give some color to divs for look good website and given some styles..

    .col-1::after{
          content: '';
          width:10px;
          height: 57%;
          background: linear-gradient(#ff469f,#ff6062);
          position:absolute;
          left:-40px;
          top:8px; 
      }
      And color for back div of the image
      .color{
          position: absolute;
          right:0;
          top:0;
          background: linear-gradient(#ff54a2,#ff575a);
          border-radius: 20px 0 0 20px;
          height:100%;
          width:80%;
          z-index:-1;
          transform: translateX(150px);
          }
          
          
After all this we give some hover effect to the 'Buy Now' button and add social media for support..


      button:hover{
        display: flex;
        align-items: center;
        justify-content: space-between;
        width: 160px;
        }
        For social media
       .social img{
          height: 13px;
          margin:20px;
          cursor: pointer;
          }
      .social{
          text-align: center;
          }
          
The highlight of this program is we add good visul in minimum axpects also using css...


      
           @media only screen and (max-width:700px){
        nav ul{
             width: 100%;
            background: linear-gradient(#ff54a2, #ff575a);
            position:absolute;
            top:75px;
            right:0;
            z-index:2;
          }
         nav ul li{
            display: block;
            margin-top:10px;
            margin-bottom: 10px;
          }
          nav ul li a{
           color:#fff;
          }
          .menu-icon{
            display: block;
          }
          #menuList{
            overflow: hidden;
            transition:0.5s;
          }
          .row{
             flex-direction: column-reverse;
              margin:50px 0;
          }
          .col-2{
              flex-basis: 100%;
              margin-bottom:50px; 
          }
          .col-2 .controller{
              width:77%;
          }
          .color{
              transform: translateX(75px);
          }
          .col-1{
              flex-basis: 100%;
          }
          .col-1 h2{
              font-size: 35px; 
            }
            .col-1 h3{
              font-size:15px;
             }
            }
            
            
In those small devices the navigation bar is not fit for that we give some special effects..like some javascript we using with a logo..
When we touch that logo the navigation features will be displayed..


       var menuList = document.getElementById('menuList');

            menuList.style.maxHeight="0px";

            function togglemenu(){
                if(menuList.style.maxHeight=="0px"){
                    menuList.style.maxHeight="130px"
                }
                else{
                    menuList.style.maxHeight="0px";
                }
            }
            
            
           and give some styles like overflow:hidden; transition:0.5s;
           
           
Then we will watch the good website for big and small devices also...

