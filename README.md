# GPT-4 Unlimited
Custom Plugins for GPT-4 (easy web app interface)

Basically, this app gives GPT-4 access to your command line. (Don't worry! By default you must approve every command manually)

This unlocks the ability for GPT-4 to interact with the internet, APIs, python scripts, and any applications that you could with a CLI. Basically it's open source, flexible, plugins for GPT-4.

# Examples
This information is accurate thanks to it's ability to Google:

<img width="738" alt="Screen Shot 2023-04-09 at 9 14 31 PM" src="https://user-images.githubusercontent.com/29033313/230792116-2f7d5d8f-16d6-4bf3-9154-52be1de91613.png">


Automatic file generation:
<img width="788" alt="Screen Shot 2023-04-08 at 3 55 56 PM" src="https://user-images.githubusercontent.com/29033313/230725162-11ce2407-7375-425c-b6f5-fc994bd5daac.png">
<img width="1313" alt="Screen Shot 2023-04-08 at 3 56 24 PM" src="https://user-images.githubusercontent.com/29033313/230725166-c2815c85-6ee9-43e3-9468-9fe47301b375.png">

<img width="848" alt="Screen Shot 2023-04-08 at 1 07 05 AM" src="https://user-images.githubusercontent.com/29033313/230690667-921ee2d1-6a31-4697-8202-1874bde8c251.png">

With a ***fully editable knowledgebase*** to tell GPT-4 what commands it has access to, how they are used, and how they should be run by your CLI.

<img width="1292" alt="Screen Shot 2023-04-07 at 11 59 57 PM" src="https://user-images.githubusercontent.com/29033313/230684178-6511c17a-200d-4af8-ba67-a1fb1cfea9b5.png">

# Installation And Startup
1. ```pip install -r requirements.txt```
2. ```streamlit run app.py```

# To Do:
- Better parsing of incorrect command syntax instead of telling GPT to correct itself. (Save tokens)
- OpenAI API Price calculator because god damn..
- Rolling content window to avoid max tokens error
