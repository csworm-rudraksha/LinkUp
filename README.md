# LincUp

LincUp is a modern social networking platform designed to enhance real-time communication and community engagement.

## Features

- 🔐 **Authentication**: Secure and seamless user authentication powered by [Clerk](https://clerk.com/).
- 📡 **Real-Time Streaming**: Integrated with [GetStream API](https://getstream.io/) for dynamic content streaming and real-time interactions.
- 💬 **Instant Messaging**: Engage in smooth, real-time conversations.
- 🏷️ **Customizable Profiles**: Personalize user profiles for a unique identity.
- 📢 **Notifications**: Stay updated with real-time alerts and notifications.
- 🎨 **Modern UI/UX**: Intuitive and responsive design for an engaging experience.

## Tech Stack

- **Frontend**: React, Next.js, Tailwind CSS
- **Backend**: Node.js, Express, MongoDB
- **Authentication**: Clerk
- **Streaming & Chat**: GetStream API
- **Deployment**: Vercel

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/lincup.git
   cd lincup
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   ```env
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   NEXT_PUBLIC_GETSTREAM_API_KEY=your_getstream_api_key
   GETSTREAM_API_SECRET=your_getstream_api_secret
   ```
4. Run the development server:
   ```bash
   npm run dev
   ```
5. Open `http://localhost:3000` in your browser.

## Contributing

Contributions are welcome! Feel free to fork the repo, create a new branch, and submit a pull request.

---

🚀 **LincUp - Connecting People in Real Time!**
