# SimpliGov

SimpliGov aims at improving the inclusion of an average person into the AI revolution by simplifying the interface between them and the government.
Our user-friendly assistant guides you through the process step-by-step, making bureaucratic procedures more accessible and less daunting.
It also features the ability to check eligibility and run simple queries for Government Funded Schemes.
This project is an AI-powered chatbot designed to also assist people in filling out government forms in India.

## Features

- Step-by-step guidance for filling out various Indian government forms
- User-friendly conversational interface powered by SimpliGov AI
- Multilingual support (list supported languages)
- Explanations of complex terms and requirements
- Error checking and validation

## Prerequisites

To run SimpliGov, you need the following:

- Python 3.12
- LangGraph
- IBM WatsonX Platform, including Granite 13B
- Google Cloud Services account and credentials

## Setup

As SimpliGov is not open-source, please follow these steps to set up the project:

1. Ensure you have Python 3.12 installed on your system.

2. Install LangGraph:
   ```
   pip install langgraph
   ```

3. Set up Google Cloud Services:
   - Create a Google Cloud account if you don't have one
   - Set up a new project in Google Cloud Console
   - Enable necessary APIs(IBM WatsonX, Groq, Google Cloud Services)
   - Create and download service account credentials

4. Contact the SimpliGov team to obtain the project files and additional setup instructions.

5. Configure the application:
   - Set up environment variables for Google Cloud credentials
   - Configure any other necessary settings as per the provided instructions

## Usage

1. Start the SimpliGov application (specific command to be provided by the SimpliGov team).

2. Access the SimpliGov interface through the provided URL or method.

3. Select the government form you need assistance with from the available options.

4. SimpliGov will greet you and ask for basic information to start the process.

5. Answer SimpliGov's questions honestly and accurately. If you're unsure about any question, type "help" or "explain" for more information.

6. SimpliGov will guide you through each section of the form, explaining requirements and asking for necessary information.

7. Once all information is collected, SimpliGov will present a summary for your review.

8. If everything looks correct, confirm to generate the filled form. If you need to make changes, let SimpliGov know.

9. Download or print your completed form as instructed by SimpliGov.

## Supported Forms

- Aadhaar Card Application, Pan Card Application, Passport Application, etc.
- It also supports multiple government schemes like PM Kisan Yojana etc.