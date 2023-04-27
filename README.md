# Color-Palette-Generator
Use OpenAI's GPT to generate a color palette based on user input.


# Setup
1. Create a .env file with your OpenAI api key
Example: `OPENAI_API_KEY=<my_api_key>`

2. Setup virtual environment and install dependencies
`virtualenv env && source env/bin/activate && pip3 install -r requirements.txt`

3. Run Flask Server
`flask run`
or (to live respond to code changes)...
`flask run --debug`
