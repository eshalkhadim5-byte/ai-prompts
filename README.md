<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Survey form</title>
</head>

<body>
   <center>
      <h1>Survey form</h1>
      <p>Let us know how we can improve freeCodeCamp</p>
      <form>
         <table cellpadding="10">
            <tr>
               <td> * Name:</td>
               <td>
                  <input type="text" placeholder="Enter your Name">
               </td>
            </tr>

            <tr>
            <td> * Email:</td>
            <td>
            <input type="email" placeholder="Enter your Email">
            </td>
            </tr>

            <tr>
            <td> * Age:</td>
            <td>
            <input type="number" placeholder="Age">
            </td>
            </tr>

            <tr>
            <td>
             Which option best describes your current role?
             </td>

             <td>
             <select>
             <option>Student</option>
             <option>Teacher</option>
             <option>Developer</option>
             </select>
             </td>
             </tr>

             <tr>
             <td>
             * How likely is that you would recommend freeCodeCamp to a friend?
             </td>

             <td>
             <input type="radio" name="recommend">Definitely<br><br>
             <input type="radio" name="recommend"Maybe<br><br>
             <input type="radio" name="recommend">Npt sure
             </td>
             </tr>

             <tr>
             <td>What do you like most in FCC:</td>

                 <td>
                 <select>
                 <option>Select an option</option>
                 <option>Projects</option>
                 <option>Community</option>
                 </select>
                 </td>
                 </tr>

                 <tr>
                 <td>
                 Things that should be improved in the future (Check all that apply):
                 </td>

                 <td>
                 <input type="checkbox">Front-end Projects <br><br>
                 <input type="checkbox">Back-end Projects <br><br>
                 <input type="checkbox">Data Visualization
                 </td>
                 </tr>
                 </table>
                 <br>
                 <input type="submit" value="Submit">
                 </form>
                 </center>
                 </body>
                 </html>
