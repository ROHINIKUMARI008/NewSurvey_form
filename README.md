# NewSurvey_form
NewSurvey_form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SURVEY FORM</title>
    <link rel="stylesheet" type="text/css" href="style.css7">
    <style>
        body{
            font-size: 16px;
            font-family: Arial, Helvetica, sans-serif;
            margin: 0;
            padding: 0%;
            background-color: white;
        }
        .outer-container{
            width: 75%;
            height: 100vh;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color:  rgb(5, 173,162 );
        }
        .container{
             width: 60%;
             display: flex;
             flex-direction: column;
             align-items: center;
             background-color: white;
             color: black;
             padding: 15px;
             margin: 0 auto;
         }
        .startpt{
            width: 80%;
            margin: auto 0;
        }
        .survey{
            text-align: center;
            color: black;
            border: 20px;
           

        }
        .title{
            background-color:  rgb(5, 173,162 );
            color:black;
            margin: auto;
            width: 800%;
            text-align: center;  
            margin-left: 200%;
            margin-right: 200%;
        }

         #description{
             text-align: center;
         }
         #text{
             text-align: center;
             margin-top: 10px;
         }
         
        #survey-form{
            text-align:centre;
        }
        .row-tab{
            display:block;
            padding-bottom: 20px;
        }
        .label-tab{
            display:inline-block;
            width: 44%;
            text-align:right;
            vertical-align: top;
        }
        .input-tab{
            text-align: left;
            display :inline-block;
            width: 54%;
        }
        .select-tab{
            text-align: left;
            width: 54%;
            display: inline-block;
        }
        
    
        #select-box{
            padding: 5px 0px;
            text-align: center;
            
        }
 </style>
</head>
<body>
   <div class="outer-container">
       <h1 class="survey"> 
           Survey form</h1>

       <div class="container">
         <div class="startpt">
             

           
           <section>
               <div id="description">
        <p> Let us know how we can improve freeCodeCamp</p>
        </div>
         <form action="" id="survey-form">
               <div class="row-tab">
                  <div class="label-tab">
                     <label> Name:</label>
                       </div>
                           <div class="input-tab">
                             <input type="text" value="Enter your name" id="name"Required> </div>
                       </div>
               
                   <div class="row-tab">
                       <div class="label-tab">
                    <label>Email: </label>
                       </div>
                       <input type="email" value="Enter your Email" id="email" required></p>
                  
                   </div>
                 <div class="row-tab">
                   <div class="label-tab">
                 <label>Age:
                 </label>
                 </div><input type="number" placeholder="Age" id="age" required></p></div>
            
           
           <div class="row-tab">
               <div class="label-tab">
              <label> Which option best describe your current role?</label>
       </div>
         <div class="select-tab" >
             <select id="select-box">
             <option value="Student">Student </option>
             <option value="Teacher">Teacher</option>
              </Select>
               </div>
               </div>
                    <div class="row-tab">
                      <div class="label-tab">
                    <label> How likely is that you would recommmed  freeCodeCamp to a friend?</label>
                   </div>
                   <div class="input-tab">
                     <input type="radio" name="suggest" value="Definetly"><label>Definetly</label><br>
                     <input type="radio" name="suggest" value="Maybe"><label>Maybe</label><br>
                     <input type="radio" name="suggest" value="Not sure"><label>Not sure</label><br>
                   </div>
               </div>
                 <div class="row-tab">
                   <div class="label-tab">
                  <label> What do You like most in FCC </label>
                     </div>
                       <div class="select-tab">
                           <select id="select-box">
                           <option value="Select an option">Select an option</option>
                           <option value="option-1">option1</option>
                           <option value="option-2">option2</option>
                       </select>
                        </div>
                       </div>
                               <div class="row-tab">
                                   <div class="label-tab">
                               <label>
                                   Things that should be improved in the future ( Check all that apply )</label>
                                   </div>
                       <div class="input-tab">
                       
                           <input type="checkbox"  name="projects" value="Front-end projects">
                           <label for="Front-end projects">Front-end projects</label><br>
                           <input type="checkbox" name=" projects" value="Back-end projects">
                           <label for="Back-end projects">Back-end projects</label><br>
                            <input type="checkbox" name="projects" value="Data Visualization">
                           <label for="Data Visualization">Data visualization</label><br>
        
                       </div>
          </div>
       </form>
       </div>
          </section>
          </div>
       </div>
   </div> 
</body>
</html>
