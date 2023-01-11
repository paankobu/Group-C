# Project Execution 

## Project coding

### Requirements and dependencies :

![req](https://user-images.githubusercontent.com/121606343/211840469-0acb92ee-4a7b-4f2f-8ccf-e6ce2b65625c.png)

![dependancies](https://user-images.githubusercontent.com/121606343/211841697-7b72ce67-7389-41cf-a1aa-220093dfde60.png)


### Python source code:

1. This block of code creates an object app which is accessed remotely through localhost that executes python script and display into the html application. The predict function is created with loading data that contains ham and spam classified emails. It labels the spam mail as '0' and ham email as '1'. The data is separated into texts and label before splitting into training and test data to train the model.

![code1](https://user-images.githubusercontent.com/121606343/211844007-8efa1d37-2d11-400b-999b-38c74f45c54d.png)

2. The next step is to perform feature extraction using TF-IDf vectorizer to get values that will be used as the inputs for the logistic regression model. The messages from emails are in string format and need to be fit into feature vectors by converting them to integer. The labels must also be converted into integers which are the Y_train and Y-test variables. The regression based model must be trained using training data before being tested using both training and test data to obtain the accuracy.

![code2](https://user-images.githubusercontent.com/121606343/211846707-c55b8aa7-9ac7-43a9-a65b-87e056bac5e6.png)

3. The last step is to link the prediction function when the user presses the button predict in the html application. The text are converted into feature vectors before being used as an object by the prediction function. The app will execute the python blocks when the main is called from the html script.

![code3](https://user-images.githubusercontent.com/121606343/211847964-0fdcad11-a375-4260-bddb-ddd897711456.png)

## Project output 

### Output 1: The output shows the model predicting an email text that is supposed to be ham

The image 1 shows the user entering an email text and clicking predict button
![ham-test-1](https://user-images.githubusercontent.com/121606343/211848775-96f3bb40-8305-4955-8e4b-ab2df2bd8fc3.png)


The image 2 shows the model accurately classifying that the email is ham
![ham-test-2](https://user-images.githubusercontent.com/121606343/211849202-e0424465-c946-4582-a555-4e4a00310323.png)

### Output 2: The output shows the model predicting an email text that is supposed to be spam

The image 3 shows the user entering an email text and clicking predict button
![spam-test-1](https://user-images.githubusercontent.com/121606343/211849525-4fb42c3c-e132-4a12-b458-ebf2f4d63fbf.png)


The image 4 shows the model accurately classifying that the email is spam
![spam-test-2](https://user-images.githubusercontent.com/121606343/211849658-e1a1b5e1-7487-4718-ba8e-3c308aca7294.png)




