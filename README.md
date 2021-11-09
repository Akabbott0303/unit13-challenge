# Robo Advisor

Chatbots are a common feature on modern websites.  The bots do everything from assist with  order problems on Amazon to capturing initial information from potential clients on insurance company websites.  Chatbots use natural language processing and artificial intelligence to simulate conversation with a human.  

![image](https://user-images.githubusercontent.com/85846948/140851443-02dbdd6d-28ee-4284-90a9-26869574f72f.png)

One platform for developing chatbots is Amazon Lex, the interface that powers Amazon's own virtual assistant, Alexa.  Amazon Lex provides developers with an easy-to-use graphical user interface to build chatbots.  Developers input sample utterances that an end user would be likely to enter.  The prompts that will be used by a chatbot are controlled by slots, which can be configured to be simple lines of dialog or response cards, complete with buttons and icons.  

Amazon's Lambda service is what breathes life, so to speak, into a chatbot created with Lex.  In Lambda, developers can create functions to control how chatbots respond to both valid and invalid user input.  The Lex GUI makes importing the Lamda function(s) as easy as checking boxes.  

For this project, I created a chatbot that helps users figure out how to invest for retirement.  The user is asked for their name, age, and amount they want to invest.  Certain parameters are required - the user must be under 65 years old, and the investment amount must be at least $5,000.  After giving the chatbot the requested information, the user is promted via response card to select a risk level, ranging from no risk (as indicated by a sleeping icon - who says developers creating financial tools can't have a sense of humor?) to very high risk (as indicated by a rambunctious-looking icon).  The chatbot then returns a suggestion for how to allocate retirement funds to the user.  

Amazon Lex and Lambda are fantastic tools for developers.  Technology continues to evolve, and having tools like these available enables developers to come up with creative solutions to problems and to create entirely new things.  I, for one, look forward to the day when Alexa can take my Starbucks order and submit it through the Starbucks app, and I can choose to get into my autonomous vehicle to pick up my coffee or opt for robot delivery.
