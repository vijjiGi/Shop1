#Membership pricing list of An App
In this program we give three types of pricing list of an App Membership..
In this we give one heading 'choose your plan' and three types of plans like 'starters','advanced','premium'..
For this we make three divs for three pricing plans and style them..


        .price{--> for all divs have one class for looking same as other..
              width:90%;
              max-width: 1100px;
              margin:auto;
              display: grid;
              grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
              grid-gap:25px;
              }
              
              
              
Then we add plan name,price,features of plan and a button and given some styles..
For the features list we make custom bubbles to looks custom and pretty...
  
  
            .price-col ul li::before{
                          content: '\2022';
                          color:#e33058;
                          font-weight: bold;
                          margin-right:8px;
                          }

For the buy button we add some styles and hover effects...



            .price-col button{
                        width:100%;
                        padding:14px 0;
                        background:transparent;
                        color:#fff;  
                        font-size: 15px;
                        border:1px solid #e33058;
                        border-radius: 6px;
                        margin-top:30px;
                        cursor: pointer;
                        transition: background 0.5s;
                          }
            .price-col button:hover{
                        background:#e33058;
                          }
                          
                          
Then we will see the plans of an App
