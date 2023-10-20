# Webshop Automation 2023

## About
  The program was created to automate various webshop processes.
  The goal would be not to have any human interaction when handling the process.
  
  Currently, In the first version, it is only optimized to one page to generate with and one page to upload to, and there is still a bit of human interaction needed.

## Steps
  The steps of the execution in the process looks like the following:
  
  1. Generating prompt for the Art generator - [ChatGPT](https://chat.openai.com/)
  2. Generating picture by a random prompt - [NightCafe Studio](https://creator.nightcafe.studio/)
  3. Making the picture bigger to make it look better on the items - [Photo Enlarger](https://www.photoenlarger.com/)
  4. Uploading the generated Art to a webshop - [Redbubble](https://www.redbubble.com/)

 The process is also linked in more detail in Hungarian, in the file called RedbubbleFolyamat.txt

## How-to-Run
  The code was created with Selenium IDE and then exported to a Python code. It is possible to run by various methods, you can read about the details [here](https://www.browserstack.com/guide/python-selenium-to-run-web-automation-test).
  
  Make sure that your window size is set to bigger than 960px when using NightCafe Studio. 

## Missing
  The code is missing the following parts for now: 
   - The usage of ChatGPT at the picture generator tool - It is independently generating a picture, not using the prompt given by ChatGPT
   - The file uploads on Photoenlarger and Redbubble - They require human interaction.
   - The "I am not a robot" filter on Redbubble is not solved properly
   - Redbubble title, description, tags to fill out properly. Currently, it's set to "Example". - To be fixed before using
