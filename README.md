# GMeet Based Mentor Connect App

**Mentor Connect** is a platform designed to facilitate seamless mentorship sessions using Google Meet. Built with a Serverless Function Architecture (SFU) and integrated with the Caledly API, this app simplifies scheduling and connecting mentors and mentees.

## Features

- Schedule mentoring sessions effortlessly
- Auto-generate Google Meet links for meetings
- Integrate with Caledly for advanced scheduling options
- Real-time notifications and updates
- Secure user authentication and authorization

## Technologies Used

- **SFU Architecture** for a scalable, serverless backend
- **Caledly API** for scheduling management
- **Google Meet API** for meeting link generation
- Frontend framework ( React)
- Authentication (Auth, OAuth)

## Setup Instructions

### Prerequisites

- Node.js & npm installed
- Google Cloud project with Calendar and Meet APIs enabled
- Caledly account with API access
- (Optional) Firebase project for authentication

### Installation

1. Clone the repository:

```bash
git clone https://github.com/GiteshDewangan/MentorConnect.git
cd MentorConnect
```

2. Install dependencies:

```bash
npm install
```

3. Configure environment variables:

Create a `.env` file in the root directory and add your API keys and credentials:

```env
# Example
CALENDLY_API_KEY=your-calendly-api-key
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
FIREBASE_API_KEY=your-firebase-api-key
```

4. Deploy the backend functions (if applicable):

```bash
# Commands depending on your deployment setup
```

5. Run the app locally:

```bash
npm start
```

### Usage

- Users can sign in and connect their Caledly account
- Schedule mentorship sessions using Caledly
- Sessions automatically generate Google Meet links
- Mentors and mentees receive notifications and reminders

## Contributing

Contributions are welcome! Please fork the repository and create pull requests.


