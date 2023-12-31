# <img src="https://i.pinimg.com/originals/78/4a/6f/784a6f2c96fe06147ff26130d5847438.png" alt="angry face" width="35"/> Intigram - LoL Win Prediction
<!-- The statistical way to show how hard your team inted in LoL -->
<img src="https://github.com/Intigram/.github/blob/main/profile/DemoScreenshot3.png" alt="screenshot demo"/>

## What is This?
This is a silly project I decided to work on while watching the 2023 League of Legends Worlds Championship. It includes a data pipeline to train a simple predictive model for a numbers-heavy game, apply explainability methods to get insights, and finally build a web app for easy consultation of the trained model. Despite being specific to the game League of Legends (LoL), I believe this is a good example of a simple, but realistic use-case for predictive machine learning, that can also work for a variety of applications, such as other games and sports. The core tech used for this project includes Python (NumPy, scikit-learn, seaborn, SHAP and Flask), JavaScript (React) and Docker.
</br></br>
Right now, I've posted a work-in-progress article explaining the project on Medium. Head on over there for more details:
<a href="https://medium.com/@chiniczrebeca/practical-machine-learning-with-lol-a-simple-predictive-use-case-with-data-collection-learning-c2b6e621df66">https://medium.com/@chiniczrebeca/practical-machine-learning-with-lol-a-simple-predictive-use-case-with-data-collection-learning-c2b6e621df66</a>

## Repositories
- [DataCollection](https://github.com/Intigram/DataCollection): every script that was used in the process of collecting and preparing the data.
- [WinModel](https://github.com/Intigram/WinModel): the python code used to train, test and analyse the model for win prediction.
- [FrontWebInterface](https://github.com/Intigram/FrontWebInterface): the front-end React app for using the model to predict given a player.
- [BackWebInterface](https://github.com/Intigram/BackWebInterface): the back-end Flask API for using the model.

## Demo

<!--
*Observation: this demo is from before the change from summoner names to Riot IDs hit League, but the code has been updated to work with Riot IDs and I'll update this GIF and the screenshot above soon*
-->

<img src="https://github.com/Intigram/.github/blob/main/profile/ezgif.com-speed.gif?raw=true" alt="demo recording"/>

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
