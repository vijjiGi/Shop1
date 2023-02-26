#Background video
In this program we built a website like tourism places..In this we highlight a feature like background video
In this we create a logo and navigation features..
Then we add a Background video,on that a text line with some special styles and a button 'Explore'..
We add video using html..


        <video autoplay loop muted plays-inline class="back-video">
                <source src="images/video.mp4" type="video/mp4">
         </video>
         
         .back-video{
                   position: absolute;
                   right:0;
                   bottom:0;
                   z-index:-1;-->This will use for watch the navigation bar..
                }
                
                
Then we add a text line and button on video and give some styles..



             .content h1{
                        font-size: 160px;
                        color:#fff;
                        font-weight: 600;
                        transition:0.5s;
                      }
            .content h1:hover{
                      -webkit-text-stroke: 2px #fff;
                      color:transparent;
                      }


For small,big devices we give perfect styles to play video like..


            @media (min-aspect-ratio:16/9){
                .back-video{
                      width:100%;
                      height:auto;
                }
                  }
            @media (max-aspect-ratio:16/9){
                .back-video{
                        width:auto;
                        height:100%;
                  }
                    }
                    
                    
Then we can see the website with special features..
