                                Chat Bot for the UK Travel information.
Use case:
Travelling now is complicated. In response to the Coronavirus, governments around the world are adjusting their travel and social policies to try to keep the virus at bay.
But people are desperate to go for holidays after held up in lockdown for more than a year, while the travel advice from the UK government is changing day by day. 
The UK government has charted down three categories based on which, people coming to the UK has to undertake the quarantine measures. 
Red list countries and territories:
Before the travel to England they must:
•	take a COVID-19 test
•	book a quarantine hotel package, including 2 COVID-19 tests
•	complete a passenger locator form
On arrival in England
•	quarantine in a managed hotel, including 2 COVID-19 tests
Amber list countries and territories:
Before the travel to England they must:
•	take a COVID-19 test
•	book and pay for day 2 and day 8 COVID-19 travel tests – to be taken after arrival in England
•	complete a passenger locator form
On arrival in England they must:
•	quarantine at home or in the place you are staying for 10 days
•	take a COVID-19 test on or before day 2 and on or after day 8
Green list countries and territories:
Before the travel to England they must:
•	take a COVID-19 test
•	book and pay for a day 2 COVID-19 test – to be taken after arrival in England
•	complete a passenger locator form
On arrival in England
•	They must take a COVID-19 test on or before day 2 after you arrive.


Concerns:
•	The major concern for the people is they are not getting updated by the countries added to the lists.
•	For the Airlines, this is been a lot of stress, as they need to refund based on the changing circumstances.

Solution: 
The solution would be integrating the Travel advice chatbot into Flight booking sites, thus people would get the complete info before booking the ticket and take the decision accordingly.

    

In the above diagram, we have used Google Chat bot (Dialog flow), which can be integrated with the Airlines website or other platforms, and provides travel advice to the customer by interacting with Gov UK API’s. 
Before going to design, let’s understand the terminology and what the Dialogflow.
Here we are going to use Dialogflow CX agent
A Dialogflow CX agent is a virtual agent that handles conversations with your end-users. It is a natural language understanding module that understands the nuances of human language. Dialogflow translates end-user text or audio during a conversation to structured data that your apps and services can understand. You design and build a Dialogflow agent to handle the types of conversations required for your system.
A Dialogflow agent is similar to a human call center agent. You train them both to handle expected conversation scenarios, and your training does not need to be overly explicit.


Webhooks
Webhooks are services that host your business logic. During a session, webhooks allow you to use the data extracted by Dialogflow's natural language processing to generate dynamic responses, validate collected data, or trigger actions on the backend.
External API
We are going to use the API published by the UK government to get the travel information from their website. 
GOV.UK Content API v1.0.0
GOV.UK Content API provides a simple and consistent way to request GOV.UK content as structured data in a predictable format. It is used within the GOV.UK website as the means for applications to lookup content in order to render it.
This API accepts HTTP requests and responds with JSON data containing the same published content as is presented on GOV.UK.
Base URL
All requests to this API should be prefixed with the following URL:
https://www.gov.uk/api/content
Get URL - https://www.gov.uk/api/content/guidance/red-amber-and-green-list-rules-for-entering-england


