# Challenge: Machine Learning for Formula E

In the heat of a Formula E race, teams need fast access to insights that can help drivers make split-second decisions and cross the finish line first. Can your data-science skills help Mediascale Racing, our very own team in the championship, take home even more trophies?

The goal of this challenge is to build a Machine Learning model that predicts the Mediascale Racing drivers’ lap times. Your solution will be evaluated on:
- The performance of your Machine Learning model.
- The quality of your code.

## Challenge 
To succeed, you have to:
- Implement a Python package called `challenge`, which exposes a REST API according to the following specifications.
- *Optional*: Use your API to predict the `LAP_TIME` for the [submission dataset](./datasets/submission.csv).

### API specifications:

1. A prediction endpoint at `localhost:5000/race/predict`,
   1. To which you can POST a CSV with the columns required to make a prediction.
   2. Which returns another CSV with header: `LAP_TIME`, containing the predicted lap times.

### Important notes:
- Datasets are provided in the [datasets](./datasets) directory.
- You may consider several factors that affect performance during a session, including:
  1. Weather.
  2. Track conditions.
  3. Driver’s familiarity with the track.
- Feel free to use any library you want.
- [Reach us](mailto:dev@mediascale.eu) when you completed the challenge.

### Github setup

1. [Fork this repo](https://github.com/mediascale-be/racing-challenge).
2. In your forked challenge repo:
   1. Go to `Settings`, at the bottom of the page, set the project visibility to `Private`.
   2. Go to `Settings > Manage Access > Add people` and add `mediascale` as a `Reader` so we can follow along with your progress.


## Good luck!
-- The Mediascale team
