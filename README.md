# Minion Speak Transaltor

## List of Contents
- Descritpion
- Input
- Output
- Processing
- Screenshots
- Link

> **Description:** Ever wonder how to write words in minions language, then this app will help you to write your words in minion languaa=ge, enter text you want on input box and click on translate button and then see the magic in front of your eyes. For this app we have used `funtransalations.com API` to translate user input.(if you don't know about minions then search about them and come back) 

<br>

> **Input:** A user has to enter text and wait for atmost 5 seconds to get input translated. A empty input get epmpty output but with silence. Inputs dont have any constraints as input can be user name or any text which to be transalted.

<br>

> **Output:** User will get to know translated input in five seconds of clicking `Translate` button in the `green` output sectionexcept `API RATE LIMIT REACHED` if rate limit reached then user is informed with alert and told to try after X duration. 

<br>

> **Processing:**
- User has to enter text and click on translate button.
- If user entered input is empty, then user will get empty output.
- After clicking on transalte button an API request is made to url `api.funtranslations.com/translate/minion.json` requesting text to translated, then based upon response recieved user is updated either with output or alert.
- (continued) First user input is checked if it contains some text then API call is made else not, after that (if contains) then  user input is cencoded and then using fetch API or function request is made and response is taken and check for whether it contains data for request or not if contains then user is updated else alert is send to user, meanwhile error handling is done using catch while API request is being made.

<br>

> **Screenshots:**
![Minion Speak Transaltor home page](https://github.com/shmbajaj/minion-speak-transalator/blob/main/screenshots/home.png?raw=true)
![Minion Speak Transaltor minion speak page translated text](https://github.com/shmbajaj/minion-speak-transalator/blob/main/screenshots/translation.png?raw=true)

<br>

> **Link:** [Minion Speak Transaltor](https://lets-speak-minion.netlify.app/)