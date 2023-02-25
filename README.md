#Hover
In this proram we create some hover effects and images for a website using html and css..
For this we create navigation bar, content div and and images...
In navigation bar we create a logo, features of website and indication logo and give those to some css styles..
In this highlights of css are..

    
    cursor:pointer;
    justify-content:space-between;
    display:flex;
    flex:1;
    display:inline-block;
    position:relative;
    
    nav ul li a::before{
              content:'';
              width:100%;
              height:0px;
              background:#d9f688;
              position:absolute;
              z-index:-1;
              left:0;
              bottom:-5px;
              border-bottom-left-radius: 8px;
              border-bottom-right-radius: 8px;
              transition:height 0.5s;  
            }
           
 After this we create a div and sub div for content and images and give some css styles
 In the content we add a heading and a button for order
 For the images we add some styles in the new styles are to the class of images
 
 
      .col{
          flex-basis:50%;
          position:relative;
          }
          
          
For the hover effect on naviation bar we give  some css styles..


      nav ul li a:hover::before{
            height:85px;
            }
            
 Then we can see beautiful website....
 
 
      
