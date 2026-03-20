**Tasks** [Create and use virtual environment .venv]
**Prompt** [Hello. Help me create and use a virtual environment named .venv. Install packages and run streamlit from the environment]
**AI suggestion** [The AI checked the requirements and created the virtual environemmt and installed the packages, and ran streamlit. It then redirected me to the streamlit app running on http://localhost:8502]
**My modifications:**[To doublecheck, I created a new terminal to verify the installation via # Check if streamlit installed correctly
"streamlit --version" then ran (make sure virtual environment is active)
streamlit run app.py *NOTE: I need to be in the correct file. This message appeared and confirmed it has been installed correctly:
>> streamlit --version
Streamlit, version 1.55.0
(.venv) PS C:\Users\bella\Downloads\lastname_firstname_week10_assignment.zip\your-project> ]
**Tasks** [Ai Help with preparing for Git and Github for Streamlit]
**Prompt** [Please help me set up Git and GitHub for my Streamlit project. I need to:
1. Initialize a git repository in my current project folder
2. Create a .gitignore file that includes .streamlit/secrets.toml and .venv/ to keep my token and virtual environment private
3. Make my initial commit
4. Help me create a GitHub repository and connect it
4. Push my code to GitHub
Please give me step-by-step commands to run in my terminal and guide me through, and also show me how to verify each step worked.]
**Ai Suggestions** [Initialize the Git Repository. (Install Git first*not installed) Then restart terminal after installation]
**My modifications and reflections**: [I had to install Git first because I realized that the app is not installed, only the website account have been set up. After I installed git and restarted vs code, I ran the following commands in order which was provided by the Ai ---> cd, git init, git status.]
**Tasks** [continuation of prep]
**Prompt** [1. I have installed git and ran the commands in order 2.Informtion: My name is Bella Zhu and my email is blzhu@ucdavis.edu]
**Ai suggestions** [Configure my git user and make the initial commit is the next step. To configure git, I need to run commands that set my git identity, after words I verify with git config --list]
**My modifications and reflections**:[The ai ran the pwsh command for me to configure git user.name Bella Zhu and my email that I provided (blzhu@ucdavis.edu)]