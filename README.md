# runcoachform
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <link rel="stylesheet" a href="styles.css">
  <title>Registration Form</title>
  </head>
  <h1 id="title"> Run Coaching with Anna</h1>
<body>
  <p id="description">Looking to PR your next race? Need guidance on fueling your training runs? Let's chat!</p>
  <form id="survey-form">
    <label id="name-label">
    <input id="name" type="text" placeholder="Name" required >What's your name?
    <label id="email-label">
    <input
    id="email" type="email" placeholder="example@email.com" required >Enter your email address
    <label id= "number-label">
    <input id="number" type="number" min="0" max="100000000"
    placeholder="888-888-8888" >Enter your phone number
<fieldset>How did you hear about me?
  <select id="dropdown"> 
    <option value="">
    <option value="Instagram">Instagram
      <option value="Facebook">Facebook
        <option value="Google Search">Google Search
  <option value="Other">Other
</select>
</fieldset>
<fieldset>
<p>Have you ever worked with a run coach before?</p>
  <input type="radio"  name="yesno" value="Y">
  <label for="Yes">Yes </label>
  <input type="radio"
  name="yesno"
  value="N">
  <label for="No">No</label>
  </fieldset>
  <fieldset>
    <p>What distance(s) are you looking to race in the next 6 months?</p>
    <input type="checkbox"
    name="distance" value="marathon">
    <label for="marathon">Marathon</label>
    <input type="checkbox" name="distance" value="half-marathon"> 
    <label for="half-marathon">Half-Marathon</label>
    <input type="checkbox"
    name="distance" value="10k">
    <Label for="10k">10k</label>
    <input type="checkbox" name="distance" value="5k">
    <label for="5k">5k</label>
    </fieldset>
    <fieldset>
      <p>Is there anything else you'd like me to know?</p>
      <textarea rows="4" cols="30"></textarea>
      </fieldset>
      <button id="submit" type="submit">
        <label for="submit">Submit</label>
  
