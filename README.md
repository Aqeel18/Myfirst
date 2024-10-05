# Myfirst
A survey form using html and css
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Survey Form</title>
    <link href="styles.css" rel="stylesheet">
  </head>
  <body>
    <h1 id="title"> Survey Form </h1>
    <p id="description"><b>This survey is conducted for research purposes</b></p>
    <div>
      <section>
        <form method="post"action="/action_page.php"id="survey-form">
        <fieldset>
          <label id="name-label" for="name">Enter your Name: <input type="text"id="name"name:"name" required placeholder="John Stuu"></label>
          <label id="number-label" for="Age">Enter your Age: 
            <input type="number"id="number" name="number" min="18" max="120" required placeholder="30"></label>
          <label id="email-label" for="email" >Enter your Email Id: <input type="email"id="email"name:"email" required placeholder="aqi@12345.com"</label>
        </fieldset>
        <fieldset>
          <labelfor="dropdown">Which course do you prefer the most?<select id="dropdown" name="dropdown">
            <option value="">Select an option</option>
            <option value="1">AI</option>
            <option value="2">Web Development</option>
            <option value="3">Machine learning</option>
            <option value="4">Data Science</option>
          </select>
          </label>
        </fieldset>
        <fieldset>
        <label>Mode of Conduct</label>
        <label for="online"><input type="radio"id="online"name="preference"value="online" checked>Online</label>
        <label for="offline"><input type="radio"id="offline"name="preference"value="ffline" >Offline</label>
        </fieldset>
        <fieldset>
          <label>Select from list of options for the class</label>
          <label for="quiz"><input type="checkbox"id="quiz"name="event"value="quiz">Quiz</label>
          <label for="Brainstorming"><input type="checkbox"id="Brainstorming"name="event"value="Brainstorming" >Brainstorming</label>
          <label for="Games"><input type="checkbox"id="Games"name="event"value="Games" >Games</label>
          <label for="Real"><input type="checkbox"id="Real"name="event"value="Real" >Real life experiments</label>
          <label for="gd"><input type="checkbox"id="gd"name="event"value="gd" >Group Discussion </label>
          <label for="test"><input type="checkbox"id="test"name="event"value="test" >Test </label>
          <label for="Summ"><input type="checkbox"id="Summ"name="event"value="Summ" >Group Summary</label>
        </fieldset>
        <fieldset>
 <label for="bio">Any Comments or Suggestions</label>
          <textarea id="bio" name="bio" rows="8" cols="30" placeholder="the class should be ....."></textarea>
        
        </fieldset>


        <input type="submit" id="submit"value="Submit"/>
        </form>
      </section>
    </div>
  </body>
  </html>

