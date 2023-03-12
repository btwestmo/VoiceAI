 A simple Python script that enables speech to text to communicate with ChatGPT. The response from Chat GPT then is exported to Text to Speech.  The Speech recognition engine is leveraging Azure Cognitive Services. Leveraging python display via interactive mode to show a click button to send voice calls. Be sure to run in [interactive mode](https://code.visualstudio.com/docs/python/jupyter-support-py).

You need to create a Cognitive Service API Key and note the Region
Also you will need to create a Open API Key. Currently OpenAI is awarding $18.00 in initial credits. [Open AI Key](https://platform.openai.com/account/api-keys )

*UPDATE the following code line with your keys*

> speech_key, service_region, openai_key = "<\YourCognitiveServicesKey>", "eastus2", "<\YourOpenAIAPIKey>"

Leverages ChatGPT latest model gpt-3.5-turbo

![image](https://user-images.githubusercontent.com/6943803/224547684-0dcd08dd-c1c1-449a-b33f-fc985c283c80.png)
