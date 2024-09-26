# Disaster-SNS

Disaster-SNS is a social networking platform designed to help people stay connected and informed during disasters. The platform integrates real-time disaster information, emergency contacts, social networking features, and automatic danger notifications to ensure the safety and well-being of its users.

## Features

- **Disaster Information**: Get real-time updates on ongoing disasters, such as earthquakes, floods, and more.
- **Emergency Contact**: Quickly reach out to your emergency contacts and let them know you are safe.
- **Social Networking**: Post updates, share information, and connect with others during emergencies.
- **Automatic Danger Notification**: Receive alerts when you are in a dangerous area based on your location.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [Next.js](https://nextjs.org/)
- [Firebase](https://firebase.google.com/) account for real-time data and notifications.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/iCyanCorporation/disaster-sns.git
   ```
2. Navigate to the project directory:
   ```bash
   cd disaster-sns
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up Firebase configuration in a `.env` file:
   ```
   NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project_id.firebaseapp.com
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project_id.appspot.com
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
   ```
5. Run the development server:
   ```bash
   npm run dev
   ```
6. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Usage

1. Sign up and create your profile.
2. Add emergency contacts to your profile.
3. Post updates and view disaster information on the dashboard.
4. Receive notifications based on your location and subscribed disaster alerts.

## Mobile Version

The mobile version of this platform will be developed in a separate repository. Stay tuned for updates!

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your improvements or features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Feel free to modify it according to your project's requirements!
