# Color-Palette-Generator
Use OpenAI's GPT to generate a color palette based on user input.


# Setup
1. Create a .env file with your OpenAI api key
Example: `OPENAI_API_KEY=<my_api_key>`

2. Setup Flask server  
Make sure you have the virtual environmwnt package installed:
`sudo apt install python3.8-venv`  or `sudo apt install python3-venv`
Setup your virtual environment:
`python3 -m venv env && source env/bin/activate`

3. Install dependencies:  
`pip3 install Flask`  
`pip3 install openai`  
`pip3 install python_dotenv`  
Note: This should be done before step2 to make sure all dependencies are installed in Python virtual environment.                                                                  

4. Run Flask Server
`flask run`
or (to live respond to code changes)...
`flask run --debug`