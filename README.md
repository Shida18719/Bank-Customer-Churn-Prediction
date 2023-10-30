## How to use this repo

1. Use this template to create your GitHub project repo

1. Log into <a href="https://app.codeanywhere.com/" target="_blank" rel="noreferrer">CodeAnywhere</a> with your GitHub account.

1. On your Dashboard, click on the New Workspace button

1. Paste in the URL you copied from GitHub earlier

1. Click Create

1. Wait for the workspace to open. This can take a few minutes.

1. Open a new terminal and <code>pip3 install -r requirements.txt</code>

1. In the terminal type <code>pip3 install jupyter</code>

1. In the terminal type <code>jupyter notebook --NotebookApp.token='' --NotebookApp.password=''</code> to start the jupyter server.

1. Open port 8888 preview or browser

1. Open the jupyter_notebooks directory in the jupyter webpage that has opened and click on the notebook you want to open.

1. Click the button Not Trusted and choose Trust.

## IDE Reminders

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to _Account Settings_ in the menu under your avatar.
2. Scroll down to the _API Key_ and click _Reveal_
3. Copy the key
4. In the IDE terminal, run `heroku_config`
5. Paste in your API key when asked

## Dataset Content

- Describe your dataset. Choose a dataset of reasonable size to avoid exceeding the repository's maximum size and to have a shorter model training time. If you are doing an image recognition project, we suggest you consider using an image shape that is 100px × 100px or 50px × 50px, to ensure the model meets the performance requirement but is smaller than 100Mb for a smoother push to GitHub. A reasonably sized image set is ~5000 images, but you can choose ~10000 lines for numeric or textual data.

## Business Requirements

- Recall: A recall of 70% on the churn class indicates that the model is able to identif a significant portion of the actual churn cases. The model is capturing a substantial number of customers who are likely to churn.

- Precision: A precision of 72% on the churn class in the training set means that when the model predicts a customer will churn, it is correct approximately 72% of the time. On the test set, a precision of 91% on the no-churn class means that when the model predicts a customer won't churn, it is correct approximately 91% of the time.

While these metrics individually show a level of performance in terms of capturing churn and making accurate no-churn predictions, it's crucial to consider the trade-off between precision and recall:

A model with high recall may generate more false positives, which means it may incorrectly classify some non-churn customers as churners. This could lead to unnecessary retention efforts or false alarms.

A model with high precision is good at minimizing false positives, but it may miss some actual churn cases.

The choice between recall and precision depends on business objectives and the associated costs. For example:

If retaining customers at all costs is the top priority, a higher recall may be desirable, even if it means more false positives.

If business have limited resources for retention efforts and want to minimize unnecessary actions, it might prefer a higher precision, even if it results in missing some churn cases.

It's also important to consider the consequences and costs associated with false positives and false negatives in a specific business context. In some cases, a balance between precision and recall may be the best approach.

- In summary, the model shows a 70% recall on churn and a 72% precision on no-churn on the test set, along with a 70% recall on churn and a 91% precision on no-churn on the train set, are positive indications, but the model's performance should be evaluated in the context of the business goals and operational constraints.

- Training Set Accuracy (73%): This indicates that, on the training data, the model correctly classified approximately 73% of all data points. In other words, out of all the instances in the training set, 73% were predicted correctly by the model.

- Test Set Accuracy (74%): This represents the model's performance on data it has not seen during training. An accuracy of 74% on the test set means that, on unseen data, the model correctly classified approximately 74% of all instances.

The fact that the test set accuracy is similar to the training set accuracy is generally a positive sign. It suggests that the model is not overfitting the training data, as the performance on unseen data is relatively consistent.

## Hypothesis and how to validate?

- List here your project hypothesis(es) and how you envision validating it (them)

## The rationale to map the business requirements to the Data Visualizations and ML tasks

- List your business requirements and a rationale to map them to the Data Visualizations and ML tasks

## ML Business Case

- In the previous bullet, you potentially visualized an ML task to answer a business requirement. You should frame the business case using the method we covered in the course

## Dashboard Design

- List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
- Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).

## Deployment

### Heroku

- The App live link is: https://YOUR_APP_NAME.herokuapp.com/
- Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
- The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. At the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.

## Main Data Analysis and Machine Learning Libraries

- Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.

## Credits

- In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism.
- You can break the credits section up into Content and Media, depending on what you have included in your project.

### Content

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site

## Acknowledgements (optional)

- Thank the people that provided support through this project.
