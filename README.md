# AmazingChatGPTPrompts

### Test Automation Framework
ChatGPT can certainly help you create a desired framework in a desired language and tech stack!
I used following prompt to generate a basic framework and worked my way to integrate other tools.

`prompt: create a boiler plate selenium webdriver 4 testing framework with testng, java, maven that can 
also handle parallel execution and print an Extent report. Add api testing with rest assured to 
this framework and add an example test for both UI and API`

#### Follow-up Prompts
You will need to tweak the follow up prompts to request whatever integtration you are missing or required.

Since it didn't provide a testng.xml or a pom.xml I asked the following prompts.
`prompt: add testng file for the above project`

`prompt: add a pom.xml file for the above project`

I then asked it to integrate Extent Report

`prompt: integrate an Extent report in this project`

Following are just some examples, but you get the point figure out what your needs are and what's missing and cater the prompts accordingly.

`update this project to take user credentials from user.properties`

`update the project to rerun the failed tests`

`Update this project to integrate with Azure Test Case updates`

It had a hickup while generating the response for the azure so I had to ask it to complete again `prompt: print the complete AzureTestCaseUpdater  class without explanation`

What I loved is once I had everything I needed, I asked it to `generate a readme.md file for the above project`, it beautifully created the file with all the features.
