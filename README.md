# Deep Learning Chatbot- DoorDash Customer Support

In the past few years, chatbots have become wildly popular in the tech and business sectors. These intelligent bots are so adept at imitating natural human languages and conversing with humans, that companies across various industrial sectors are adopting them. From e-commerce firms to healthcare institutions, everyone seems to be leveraging this nifty tool to drive business benefits. In this project, a Customer Support Chatbot was built and deployed. The Artificial Intelligent Chatbot was trained using Deep Learning algorithims and deployed using the Flask method. 


![image](https://user-images.githubusercontent.com/39967400/205730983-4a8c5415-d7ca-4444-aeda-0031489e5afa.png)



![APP](https://user-images.githubusercontent.com/39967400/205729401-2d6f1102-d2ea-4976-a596-d93a0237d137.png)


## Requirements
1- TensorFlow    
2- Flask

## Execution
To run this Bot, first run the # train.py file to train the model. This will generate a file named chatbot_model.h5
This is the model which will be used by the Flask REST API to easily give feedback without the need to retrain.
After running train.py, next run the app.py to initialize and start the bot.
To add more terms and vocabulary to the bot, modify the intents.json file and add your personalized words and retrain the model again.



For further details see the notebooks in the repository.


