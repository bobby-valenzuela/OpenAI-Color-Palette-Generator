# Color-Palette-Generator
Use OpenAI's GPT to generate a color palette based on user input.


# Setup
1. Create a .env file with your OpenAI api key
Example: `OPENAI_API_KEY=<my_api_key>`

2. Setup virtual environment and install dependencies
```bash
$ virtualenv env && source env/bin/activate && pip3 install -r requirements.txt
```

3. Run Flask Server
```bash
$ flask run
```
or (to live respond to code changes)...
```bash
$ flask run --debug
```

You should now be able to access the app at [http://localhost:5000](http://localhost:5000)! For the full context behind this example app, check out the [tutorial](https://beta.openai.com/docs/quickstart).
