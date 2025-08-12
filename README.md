# AIExploration
learning how to build and apply AI agents

This will implement an AI chatbot, using the Azure Open AI demo chatbot.

Steps:
Set up repository and branch protections
Set up dev, uat and prod env
Set up jupyter notebook deployment
Add code
test and so on

Source material for learning: https://github.com/Azure-Samples/azure-search-openai-demo

Hey there! I am creating a web application that will help with holiday planning and outfit decisions. The application will have login profiles. Within someone's profile, they will have recommendations for sites and outfits they may want to buy with a connected LLM that can give outfit suggestions based on the prompt that the user has created for the styles they want.

Below is the AWS architecture for the application:

<img width="1490" height="895" alt="Image" src="https://github.com/user-attachments/assets/80acba89-b7f0-46a8-aa43-eb1691354a57" />


Resource Usage and justification

I am using the Azure Open AI chatbot as I have previous experience with it, it is also suitable for this applications function.
I am using terraform for the deployment of the resources which is key as this will be solution that is set up across different cloud platforms.
The infrastructure code will be separate, all deplyments will be excecuted using CI/CD pipelines, created using Github Actions.
Finally, I aim to monitor the performance of my platform using Prometheus or Grafana. How, I'm not sure yet, still learning lol
