# Robo Advisor

I  decided to create a robo advisor, because machine learning and NLP are disrupting finance to improve the customer experience. Existing and potentially new customers will be able to use this robo advisor to get investment portfolio recommendations for retirement.

I combined AWS(Amazon Web Services)  with Python superpowers in order to create a bot that will recommend an investment portfolio for a retirement plan.

Through Amazon Lex I created a bot that establishes a conversation about requirements to suggest an investment portfolio for retirement and I enhanced it with an Amazon Lambda function  that validates the user's input and returns the investment portfolio recommendation.

## Technoologies

```
datetime 
dateutil.relativedelta
json
botocore.vendored 
dateutil.relativedelta 
```

## Installation guide
In order to open and run this program you have to follow these steps:

* Go to my repository in GitHub and open the repository called ```roboadvisors_15```

* Copy the repository's link.

![roboadvisor_ssh_jpeg](https://user-images.githubusercontent.com/80844686/125149393-b399bc80-e0ed-11eb-98ef-0930adb1ae8e.jpg)

* Open Git Bash in your computer.

![git_bash](https://user-images.githubusercontent.com/80844686/115638940-40d82c80-a2c8-11eb-816a-e991b245cd88.jpg)

* Clone the repository by typing ```git clone``` and paste the link ```git@github.com:nestor39/roboadvisors_15.git```.
![git_clone_roboadvisor](https://user-images.githubusercontent.com/80844686/125149382-a54ba080-e0ed-11eb-9699-39bfd0214a1c.jpg)


After you download the files, you should go to https://aws.amazon.com/ and create an account with them. Click on the Amazon web console, and click on search, look for Amazon Lex and create the bot with the configuration I present below:

Bot Without Lambda configuration
![roboadvisor_utterances](https://user-images.githubusercontent.com/80844686/125149567-8bf72400-e0ee-11eb-9b25-fd8faa13de09.jpg)


In order to use the Lambda function combined with the Bot you have to go to the search bar and type Lambda, click on this and use the Lambda function I submitted in these files.  Modify the configuration as I show below and then click on the button Build.

![roboadvisor_utterances_with_lambda](https://user-images.githubusercontent.com/80844686/125150083-dcbc4c00-e0f1-11eb-8133-26027d7018c3.jpg)


## Results

You can see through the next videos and picture how this bot works.


![test_bot_without_Lambda](https://user-images.githubusercontent.com/80844686/125149729-7df5d300-e0ef-11eb-8edc-91049196636a.png)




https://user-images.githubusercontent.com/80844686/125150030-8d761b80-e0f1-11eb-876f-c83fb32daefe.mp4


Testing the bot with Lambda function:


https://user-images.githubusercontent.com/80844686/125150020-70d9e380-e0f1-11eb-8b50-be5200eb9a15.mp4




## Inside the Repository

![roboadvisor_excalidraw](https://user-images.githubusercontent.com/80844686/125148893-56e8d280-e0ea-11eb-998f-7494f6cf1164.jpg)

## Contributors

This project was made with helpful contribuitions from Berkeley Fintech Bootcamp members. 

This code was written by Nestor Ramirez.

email: nestorramirez3994@gmail.com

Linkedin: (https://www.linkedin.com/in/nestor-ramirez-cuadro-375654209/)



## License 
MIT
