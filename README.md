# AskMe 
This is a project for the Technion course: Intelligent interactive systems. 
The project tackles the issue of Passive Learning, marked by the absence of active engagement in the learning process, which can lead to gaps in knowledge and a misjudgment of one's learning progress (illustrated by the 'Dunning-Kruger' effect).
Our solution is a web app designed as a personalized virtual learning assistant. 
This assistant prompts students with questions tailored to the text they're studying and their previous interactions. It can also respond to questions inputted by the user, indicating whether the answer is found within the document or derived from external data. 
This approach ensures that learners actively participate in their education, enabling a more accurate assessment of their understanding.


### How to activate:
In order to activate, we have created an anaconda environment with all the dependencies.
1. Pull the files by their original locations
2. Inside pages folder, in 3_generate.py , look for "API_KEY = 'Enter API KEY here'" and replace the string with your google API key
3. Download anaconda 
4. Enter anaconda powershell
5. go to the folder of InteractiveSystemProject using cd commands
6. Write:
     1. conda env create -f sysenv.yml
     2. conda activate sysenv
     3. streamlit run streamlit_app.py
