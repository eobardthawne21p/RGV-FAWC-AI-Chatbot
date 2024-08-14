# RGV-FAWC-AI-Chatbot

### This project was done for CSCI 3351 AI-Powered Apps With Mr. Eric Martinez. It was created using Python3, Gradio, OPENAI API, and SQLite databases. This AI Chatbot named Sparky simulates an app that allows users to sign up for cleanup events using databases and prompt engineering.
### *This file requires a .env file with an OPENAI_API_BASE and OPEN_API_KEY in order to work. May need updated versions of dependency software as well, so it does not currently work (Never put your API base or key directly in the public repo)

## Inspiration

### As a member of the Board of Directors for RGV Fishing Area and Waterway Cleanups, I witness firsthand the large amount of texts and phone calls that all of the board members receive from volunteers. Many of the questions that we get are ones that can be answered by looking at the group's Facebook page or an assistant might be able to answer. Additionally, many prospective volunteers ask about signing themselves and others up for events, and we often tell them that they are welcome to just come over and help us clean. It would be very helpful if we had an accurate headcount prior to events to bring an adequate amount of supplies and food. 

### Therefore, Sparky was born! Sparky was the solution that I came up with that would leverage GPT's conversational messages as well as the feature, that was released and still worked as of May 2024, that would allow me to pass the LLM tools in the form of Python3 functions that it could call to get more information and interact with real databases. Sparky is a proof of concept piece of software that shows the power of leveraging GPT 4.0's newest features that could potentially be deployed in the near future to register volunteers effectively and give propsective volunteers information about our organization and cleanups.


## Future Work

### Since Sparky was created as a final project for CSCI 3351 AI-Powered Apps, it is only known to work on May 20th, 2024. Due to potential new releases in software that it is dependent on, some updates in the software and potential debugging may be required to get Sparky working. Additionally, the user would need to supply their own OPENAI_API_BASE and OPENAI_API_KEY in a .env file to work. 

### My plans for Sparky are to:

### . Improve its functionality to be more helpful -> I could never get it to show past events.

### . Add additional tools for GPT 4.0 to leverage

### . Deploy Sparky to a rendering service to make it accessible to volunteers


