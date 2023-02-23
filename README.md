# Shop1
In this program we create a Simple App header using Css Styles.
In this we create a nav tag to create Header..
In this we add logo,name of App and some headings with links in navigation Bar..then we give some CSS Styles like
    
    
    nav{
        width:100%;
        display:flex;
        align-items: center;
        justify-content: space-between;
        padding:20px 0;
        }
        
 And also add styles to list items..
 
    
      nav ul li{
            display: inline-block;
            list-style: none;
            margin:10px 30px;
            position:relative;
          }
      nav ul li a{
            text-decoration: none;
            color:#3f51b5;
          }
          
          
 Then we add a Heading and some paragraph and a button for shopping and styles those with css
 Then we add an image and give some styles like..
 
 
      .user-box{
            background-color: #d9e0ff;
            position:absolute;
            top:0;
            right:12%;---> when we give top:0 the navigation bar is not visible..To make that visible we give some extra styles
            z-index:1; and we give to navigation bar some style ------>z-index:100;
            }
      .user-box img{
            display: block;
            padding-top: 100px;
            width:410px;
            margin-bottom: -205px;---> it will give the bottom margin round shape and it must be the half of width value.
          }
