# Fronted-mentor-challenge
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <link href="https://fonts.googleapis.com/css2?family=Barlow+Semi+Condensed:wght@500;600&display=swap" rel="stylesheet">
        <style>
             body
  {
    background-color: hsl(210, 46%, 95%);
    overflow:scroll;
  }     
    .main{
        height: fit-content;
        font-size: 13px;
        font-family: 'Barlow Semi Condensed', sans-serif;
        display: grid;
       grid-template-columns: 1fr 1fr 1fr 1fr;
        grid-column-gap: 2em;
        grid-row-gap: 2em;
        padding: 160px 240px 160px 200px;
    }
    .first_para{   
     border-radius:4%;
    grid-area: "first_para";
    grid-column: 1/span 2;
    background-color: hsl(263, 55%, 52%);
 background-image: url(image/bg-pattern-quotation.svg);
 background-repeat: no-repeat;
    background-position: 80% 0;
    color:hsl(0, 0%, 100%);
    padding: 20px 20px 20px 20px;
    }
    .second_para{
        grid-area: "second_para";
    background-color: hsl(217, 19%, 35%);
    border-radius:4%;
  
    color:hsl(0, 0%, 100%);
    padding: 20px 20px 20px 20px;
}
.third_para{
    grid-area: "third_para";
    grid-column: 4/span 1;
    grid-row: 1/span 2;
    background-color: hsl(0, 0%, 100%);
    border-radius:4%;
   
    color: hsl(217, 19%, 35%);
    padding: 20px 20px 20px 20px;
}
.fourth_para{
    grid-area: "fourth_para";
    background-color: hsl(0, 0%, 100%);
    border-radius:4%;
    padding: 20px 20px 20px 20px;
    color: hsl(217, 19%, 35%);
}
.fifth_para{
    background-color: hsl(219, 29%, 14%);
    grid-column: 2/span 2;
    border-radius:4%;
    color:hsl(0, 0%, 100%);
    padding: 20px 30px 20px 30px;
}
img{
     float:left;
     width: 35px;
    height: 35px;
    border-radius: 50%;  
}
p1{
    font-size: 18px;
    font-weight: bold;
}
p2{
     opacity: 60%;
     padding-top:20px;
}
h{
     padding-left: 20px;
     font-size: 12px;
}
span{
     padding-left: 20px;
     opacity: 60%;
     font-size: 13px;
     font-weight: 20px;
}

     </style>
    </head>
    <body>
        <div class="main">
        <div class="first_para">
            <div class="image">
                <img src="image\image-daniel.jpg">
            </div>
            <div>
          <h> Daniel Clifford </h><br>
           <span>Verified Graduate</span><br><br>
       <p1 >  I received a job offer mid-course, and the subjects I learned<br>
         were current, if not more so, in the company I joined. I<br>
         honestly feel I got every penny’s worth.<br>
       </p1><br>
      <p2> “ I was an EMT for many years before I joined the bootcamp. I’ve been looking to make a<br>
         transition and have heard some people who had an amazing experience here. I signed up for<br>
          the free intro course and found it incredibly fun! I enrolled shortly thereafter. The next 12<br>
           weeks was the best - and most grueling - time of my life. Since completing the course, I’ve<br>
          successfully switched careers, working as a Software Engineer at a VR startup. ”
          </p2>
          </div>
               </div>
       
               <div class="second_para">
                    <div class="image">
                         <img src="image\image-jonathan.jpg">
                     </div>
              <h>  Jonathan Walters</h><br>
             <span>Verified Graduate</span><br><br>
           <p1 >  The team was very<br>
                supportive and kept me motivated<br>
           </p1><br>
          <p2> “ I started as a total newbie with<br>
               virtually no coding skills. I now work<br>
               as a mobile engineer for a big<br>
                company. This was one of the best<br> 
                investments I’ve made in myself. ” 
              </p2>
                   </div>

                   <div class="third_para">
                    <div class="image">
                         <img src="image\image-kira.jpg">
                     </div>
                   <h>Kira Whittle</h><br>
                   <span> Verified Graduate</span><br><br>
               <p1 >  Such a life-changing experience.<br>
                         Highly recommended! <br> 
               </p1><br>
              <p2>“ Before joining the bootcamp, I’ve <br>
                  never written a line of code. I needed <br>
                   some structure from professionals <br>
                    who can help me learn programming  <br>
                    step by step. I was encouraged to <br>
                     enroll by a former student of theirs <br>
                      who can only say wonderful things <br>
                      about the program. The entire <br>
                       curriculum and staff did not <br>
                        disappoint. They were very hands-on <br>
                       and I never had to wait long for <br>
                       assistance. The agile team project, in <br>
                       particular, was outstanding. It took  <br>
                        my learning to the next level in a way <br>
                        that no tutorial could ever have. In <br>
                         fact, I’ve often referred to it during <br>
                       interviews as an example of my  <br>
                         developent experience. It certainly <br>
                       helped me land a job as a full-stack <br>
                       developer after receiving multiple  <br>
                                offers. 100% recommend! ”
                  </p2>
                       </div>

                       <div class="fourth_para">
                         <div class="image">
                              <img src="image\image-jeanette.jpg">
                          </div>
                       <h> Jeanette Harmon </h><br>
                        <span>Verified Graduate</span><br><br>
                   <p1 > An overall wonderful<br>
                        and rewarding<br>
                         experience <br>
                   </p1><br>
                  <p2> “ Thank you for the wonderful<br>
                       experience! I now have a job I really<br>
                        enjoy, and make a good living while<br>
                         doing something I love. ”
                      </p2>
                           </div>

                           <div class="fifth_para">
                              <div class="image">
                                   <img src="image\image-patrick.jpg">
                               </div>
                            <h>Patrick Abrams</h><br>
                          <span>Verified Graduate</span><br><br>
                       <p1 >  Awesome teaching support from TAs who did the bootcamp<br>
                            themselves. Getting guidance from them and learning from<br>
                             their experiences was easy.<br>
                       </p1><br>
                      <p2>“ The staff seem genuinely concerned about my progress which I find really refreshing. The<br>
                           program gave me the confidence necessary to be able to go out in the world and present<br> 
                           myself as a capable junior developer. The standard is above the rest. You will get the<br>
                            personal attention you need from an incredible community of smart and amazing people. ”
                          </p2>
                               </div>
    
        </div>
                    </div>
                </body>
            
            </html>
