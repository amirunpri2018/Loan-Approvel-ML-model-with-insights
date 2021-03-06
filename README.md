# Loan Approval Predictor

![CI](https://github.com/mmaithani/Loan-Approvel-ML-model-with-insights/workflows/CI/badge.svg)

[ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="20"> ](https://www.linkedin.com/in/mohitmaithani/)
[![Twitter](https://img.shields.io/twitter/follow/xaret_?style=social)](https://twitter.com/xaret_)
[![github](https://img.shields.io/github/followers/mmaithani?label=Follow&style=social)](https://github.com/login?return_to=%2Fmmaithani)


## ⓪ Interfacce 

<img align="left" width="100%" src="/assets/ui(1drop).png" alt="fork this repository" />
<br>

## ➀ Description

Loan approval is a very important process for banking organizations. The system approved or reject the loan applications.
Recovery of loans is a major contributing parameter in the financial statements of a bank. It is very difficult to predict the possibility of payment of loan by the customer.
In recent years many researchers worked on loan approval prediction systems. Machine Learning (ML)techniques are very useful in predicting outcomes for large amount of data.

## ➁ Key Features

- Interface to predict <a href="https://loan5.herokuapp.com/">loan application approval </a>
- data insights withhin <a href="https://github.com/mmaithani/Loan-Approvel-ML-model-with-insights/blob/master/Loan%20application%20-approval%20insights%20.ipynb">Jupyter Notebook</a>
- Trained <a href="https://github.com/mmaithani/Loan-Approvel-ML-model-with-insights/blob/master/modell.pkl"> Model </a>
- Public <a href="https://loan5.herokuapp.com/api"> api </a>
- Heroku git <a href="https://git.heroku.com/loan5.git"> link </a> 
- multiple machine learning algorithms. 

## ➂ Public Api usage

install Requests, 
```sh
# heroku url
heroku_url = 'https://loan5.herokuapp.com/api' # change to your app name

# sample data
data={'Gender':1, 'Married':1, 'Dependents':2, 'Education':0, 'Self_Employed':1,
'Credit_History':1,'Property_Area':1, 'Income':1}

data = json.dumps(data)
```
- check prediction
```sh
print(send_request.json())

```
you will get answer
{'results': {'results': 1}}

Now people can access API endpoint with the Heroku URL and use this model to make prediction 

## ➃ Tech Stack

- Heroku
- Scikit-learn
- Flask
- Pandas, numpy
![Python Version](https://img.shields.io/badge/python-v3.7-blue)

---
##  ➄ Credit
 <img width="70" src="assets/pic.gif" alt="kitty" />[<img src="https://github.com/favicon.ico" width="20"> ](https://github.com/mmaithani)    [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="20"> ](https://www.linkedin.com/in/mohitmaithani/)    [<img src="https://twitter.com/favicon.ico" width="20">](https://twitter.com/xaret_)    **[Mohit Maithani](https://mmaithani.github.io)**    |  Tech enthusiast (Data Science)

- public api deployment 
[<img src="https://twitter.com/favicon.ico" width="20">](https://twitter.com/elizabethets)
---
## ➅ Contributing

```sh
git clone https://github.com/mmaithani/Loan-Approvel-ML-model-with-insights.git 
```
Start rocking

---
# For beginner here is a full <a href="https://github.com/firstcontributions/first-contributions/blob/master/README.md"> tutorial :</a>

<img align="right" width="300" src="assets/fork.png" alt="fork this repository" />

If you don't have git on your machine, [install it]( https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="assets/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the *copy to clipboard* icon.
Open a terminal and run the following git command:

```
git clone "url you just copied"
```
where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:
```
git clone https://github.com/this-is-you/first-contributions.git
```
where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```
Now create a branch using the `git checkout` command:
```
git checkout -b <add-your-new-branch-name>
```

For example:
```
git checkout -b add-alonzo-church
```
(The name of the branch does not need to have the word *add* in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="assets/git-status.png" alt="git status" />


If you go to the project directory and execute the command `git status`, you'll see there are changes.


Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:
```
git commit -m "Add <your-name> to Contributors list"
```
replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-branch-name>
```
replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.

<img style="float: right;" src="assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="assets/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

---

### Attribution

These contribution guidelines have been learned from [this good-Contributing.md-template](https://gist.github.com/PurpleBooth/b24679402957c63ec426).

Also special thanks : elizabethets <img width="30" src="assets/mona-whisper.gif" alt="kitty" />

