# Cliniko-Chatbot-Project
A Voiceflow chatbot integrated with Cliniko API for healthcare records
## Overview
This project demonstrates an AI-powered healthcare chatbot created using Voiceflow. The chatbot integrates with the Cliniko API to provide basic information about patient records and appointments. It is designed to enhance patient interaction and streamline appointment management.

## Features
- Captures patient ID and uses it to fetch patient details from Cliniko.
- Retrieves and displays essential patient information such as:
  - Name
  - Email
  - Phone number
- AI-powered responses to user queries.
- Uses Voiceflow’s intuitive flow blocks for logic and Cliniko API for data fetching.

## How It Works
1. The user provides their **Patient ID**.
2. The chatbot uses the ID to fetch patient information through the **Cliniko API**.
3. The AI generates a concise response based on the retrieved data, answering specific queries like "What is my name?" or summarizing the patient details.

## Voiceflow Project
You can view the Voiceflow project for this chatbot at the link below:

[**Voiceflow Cliniko Chatbot Project**](https://creator.voiceflow.com/prototype/67a73cb60fe6c98cd39cb19c)

## API Integration
### Endpoints Used:
- **GET /patients**: Retrieves a list of all patients.
- **GET /patients/{id}**: Fetches specific details for a patient by ID.

### API Authentication:
- The Cliniko API uses **Basic Authentication** with a Base64-encoded API key.
- API key setup is required in the API block within Voiceflow.

## Screenshots
### Voiceflow Flow:
![Voiceflow Project Flow](https://i.postimg.cc/1tdJrP81/temp-Image-U3iw-Fo.avif)
### Chatbot in Action:
![Chatbot Test Mode](https://i.postimg.cc/6QTL0FFC/temp-Image-Tkli5l.avif)

## How to Run
1. **Access the Project:**
   - Open the [Voiceflow Cliniko Chatbot Project](https://creator.voiceflow.com/prototype/67a73cb60fe6c98cd39cb19c)link.
   - Import the project into your Voiceflow account if needed.

2. **Set Up API Key:**
   - Go to the API block in Voiceflow and input a valid Cliniko API key.

3. **Test the Chatbot:**
   - Use Voiceflow’s **Test Mode** to interact with the chatbot.

## Postman API Testing
- **Postman Evidence:**
  Screenshots of successful API testing for:
  - `GET /patients`
  - `GET /patients/{id}`
- These screenshots are included in the `api-testing` folder of this repository.

## Additional Use Cases
Here are a few suggested enhancements for the chatbot:
1. **Appointment Management:**
   - Allow patients to book, cancel, or reschedule appointments via the Cliniko API.

2. **Reminder Notifications:**
   - Send SMS or email reminders to patients for upcoming appointments.

3. **Medical History Integration:**
   - Display patient medical history, alerts, or custom fields stored in Cliniko.

4. **Integration with Third-Party Platforms:**
   - Connect the chatbot to other healthcare platforms for lab reports, prescriptions, or telemedicine services.


