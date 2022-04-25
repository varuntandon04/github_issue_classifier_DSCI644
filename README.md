# Classification of Github Issues

Popular projects receive an overwhelming amount (tens of thousands) of issues reports every single day. So naturally it becomes a huge problem to manage and prioritize the issue reports even with the help of issue trackers. Hence, it’s a necessity to have a tool that can automatically predict the type of the issue.
In this project, we treated the problem of issue labeling as a multiclass classification problem with the following classes: 
* Bugs 
* Enhancements
* Questions

We use Google's BERT as our classifier and use closed issues from Github to train the model. A detailed explaination of the process can be found in the project report in this repo.
