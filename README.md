<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8>
   <title>Survey Form</title>
   </head>
   <body>
     <main>
     <h1>Survey Form</h1>
     <p>Let us know how we can improve freeCodeCamp</p>

     <form>
   
   <!--Name, Email, Age-->
   <lable for="name">Name</lable>
   <input type="text" id="name" name="name" placeholder="Enter your name">

   <lable for="email">Email</lable>
   <input type="email" id="email" name="email" placeholder="Enter your Emmail">

   <lable for="age">Age</lable>
   <input type="number" id="age" name="age" placeholder="Age">

   <!--Dropdrown-->
   <lable for="role">Which option best describes your current role?</lable>
   <select id="role" name="role">
   <option value="">Select an option</option>
   <option value="student">Students</option>
   <option value="job">Full time Job</option>
   <option value="learner">Full Time learner</option>
   <option value="prefer-not">Prefer not to say</option>
   </select>

   <!--Radio buttons-->
   <fieldset>
   <legend>How likely is that you would recommend freeCodeCamp to a friend?</legend>

   <input type="radio" id="definitely" name="recommend" value="definitely">
   <lable for="definitely">Definitely</lable>

   <input type="radio" name="recommend" value="maybe">
   <lable for="maybe">Maybe</lable>

   <input type="radio" id="not sure" name="recommend" value="not-sure">
   <lable for="not-sure">Not sure</lable>
   </fieldset>

   !--Checkboxes-->
   <fieldset>
   <legend>Things that should be improved in the future (Check all that apply)</legend>

   <input type="checkbox" id="front-end" name="improvement" value="front-end">
   <lable for="front-end">Front-end Projects</lable>

   <input type="checkbox" id="back-end" name="improvement" value="back-end">
   <lable for="back-end">Back-end Projects</lable>

    <input type="checkbox" id="data-vis" name="improvement" value="data-vis">
   <lable for="data-vis">Data Visualization</lable>
   </fieldset>

   <!--text area-->
   <lable for="comments">Any comments or Suggestions?</lable>
   <textarea id="comments" name="comments" placeholder="Enter your comment here..."></textarea>

   <button type="submit">Submit</button>
   </form>
   </main>
   </body>
   </html>
   </main>
   </body>
   </html>
