# mtg-card-generator

mtg-card-generator is a tool for creating custom Magic the Gathering cards based on a generative model. <br>

This project was written as a final project of a Machine learning course at Jagiellonian University, Cracow. <br>
The main aim of this project was to learn more about generative models and machine learning as a field of study. As a bonus to wirte a program to generate a set of at least 360 different cards for the "cube" format. Those cards will be printed and draft played on 01.04.2022 in a group of 8 people. 


## Preparation

1. In order to run the notebook you have to register at https://mtg.design/ <br>
2. Log in <br>
3. Open your browser developer console via "Option + ⌘ + J (on macOS)" or "Shift + CTRL + J (on Windows/Linux)" <br>
4. Change the webstite adress to https://mtg.design/login <br>
5. Go to window "Network" and below in the column "Name" click "login" <br>
6. In the section "Request Headers" copy your "laravel_session" string and "user-agent" string <br>
7. Replace tha values in the code in the section "Render" in the  "rederCard(obj)" method - line 8 and 9 <br>

Packadges that has to be loaded: <br>
os
time
re
gc
hutil
numpy
random
math
matplotlib.pyplot 
urllib.request, json
requests
cv2
PIL
IPython
tensorflow 
__future__ 

## Usage

It is advised to run the notebook via Google colab (by importing the file) or to execute all cells in jupyter lab. <br>
When you don't have time for it just run in from the command line: 

```shell
jupyter nbconvert --to notebook --execute mtg-card-generator.ipynb
```
## Futher milestones

1. Fix artwork render <br>
2. Optimize data cleaning process <br>
3. Training the models longer to make better predictions <br>
4. Automation of artwork theme. <br>
Every Magic The Gathering set ist placed in a creative word with theme such as dragons, ninjas, pharaons etc. It is still possible to change the art searchword manually but it has not benn automized yet. <br>
5. Create a mtg standard set with card categorization. The default Magic has 101 commons, 80 uncommons, 60 rares, and 20 mythic rares.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.

## License
[The Chicken Dance License](https://github.com/supertunaman/cdl/blob/master/COPYING)
