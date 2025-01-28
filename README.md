# Gaia: Women Safety App

## Overview
Gaia is an AI-powered safety application designed to enhance the security and well-being of women. The app provides real-time support through AI simulations, crime data visualization, emergency assistance, and route planning based on safety scores. By leveraging data analytics and machine learning, Gaia empowers users to navigate their surroundings with greater confidence and safety.

## Features

### 1. **Personal Information Management**
- Allows users to securely input personal details such as name, age, gender, email, and address.

### 2. **AI-Powered Support**
- Provides real-time conversational support powered by Groq's advanced AI model.
- Users can describe their concerns or feelings to receive instant AI responses.

### 3. **Emergency Call Assistance**
- Simulates emergency service calls with quick and responsive actions.
- Alerts users that help is on the way during emergencies.

### 4. **London Crime Map**
- Displays a detailed, interactive map of London's boroughs, highlighting safe and dangerous zones based on crime rates and safety scores.
- Boroughs are color-coded for easy identification of safety levels (green for safe, red for dangerous).

### 5. **Route Planning with OpenRouteService (ORS)**
- Provides optimized routes between boroughs in London based on user-selected start and destination points.
- Incorporates safety scores of boroughs into the route visualization.
- Displays the calculated route with markers and paths on an interactive map.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/M-Hamza-Hassaan/AI-GAIA.git
   ```
2. Navigate to the project directory:
   ```bash
   cd AI-GAIA
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up environment variables:
   - Create a `.env` file in the project root.
   - Add the following variables:
     ```
     GROQ_API_TOKEN=<your_groq_api_token>
     ORS_API_KEY=<your_openrouteservice_api_key>
     ```
5. Run the application:
   ```bash
   streamlit run app.py
   ```

## Usage

1. Launch the application using the command above.
2. Use the sidebar to navigate between features:
   - **Personal Information**: Enter your personal details securely.
   - **AI-Powered Support**: Simulate a conversation with Gaia AI for safety advice or reassurance.
   - **Emergency Call**: Trigger a simulated call for emergency assistance.
   - **London Crime Map**: Explore safe and dangerous zones within London.
   - **ORS Route**: Plan a route between boroughs with safety considerations.

## Dependencies

- **Python Libraries**: `streamlit`, `requests`, `folium`, `pandas`, `time`, `groq`
- **APIs Used**:
  - Groq API for AI-powered support.
  - OpenRouteService API for route planning.

## Folder Structure

```
project-directory/
|-- app.py                 # Main application file
|-- requirements.txt       # Python dependencies
|-- data/                  # Static data used for crime and borough details
|-- .env                   # Environment variables file
```

## Note

- This application is for informational purposes only. The safety scores and insights are generated using available data and may not always reflect real-time conditions.

## Contributing

1. Fork the repository.
2. Create a new branch for your feature/bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For inquiries or feedback, please contact me on [LinkedIn](https://www.linkedin.com/in/muhammad-hamza-hassaan/).

