# GenAI Programs

## Commands to run chatbot.py in command line
### Install Python environment
```
pip3 install virtualenv 
virtualenv GenAIPrograms
source GenAIPrograms/bin/activate
```

### Use transformers library to use NLP capabilities and torch library for PyTorch capabilities
```
python3 -m pip install transformers==4.30.2 torch
```

### Execute chatbot.py in command line
```
python3 chatbot.py
```

## Commands to run chatbot_on_web.py in command line
### Install Python environment
```
pip3 install virtualenv 
virtualenv GenAIPrograms
source GenAIPrograms/bin/activate
```

### Use transformers library to use NLP capabilities and torch library for PyTorch capabilities
```
python3 -m pip install flask
python3 -m pip install flask_cors
python3 -m pip install transformers==4.30.2 torch
```

### Execute chatbot_on_web.py in command line
```
python3 chatbot_on_web.py
```

### Talk to chatbot on web
```
curl -X POST -H "Content-Type: application/json" -d '{"prompt": "Hello, how are you today?"}' 127.0.0.1:5000/chatbot
```
