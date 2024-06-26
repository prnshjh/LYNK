

# 🚀 Project Overview

## ⚙️ Tech Stack

- **Next.js**
- **TypeScript**
- **Clerk**
- **GetStream**
- **ShadCN**
- **Tailwind CSS**

## ⚙️Features

### Authentication & Security
- **Secure Login**: Authenticate via Clerk with social sign-on or email/password.
- **Real-time Security**: Ensure data integrity with secure, real-time interactions.

### Meetings & Controls
- **Start & Manage Meetings**: Initiate and control meetings with ease.
- **Meeting Customization**: Configure settings like recording, reactions, and screen sharing.

### Scheduling & History
- **Schedule Future Meetings**: Plan ahead and manage upcoming meetings effortlessly.
- **Access Past Meetings**: Review details and recordings of previous sessions.

### User Experience
- **Responsive Design**: Seamlessly adapts to various devices for optimal user experience.
- **Personal Meeting Rooms**: Instantly accessible with unique links for quick collaboration.

# 🛠️ Quick Setup

### Requirements

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

### Getting Started

1. **Clone the Repository**

   ```bash
   git clone https://github.com/adrianhajdin/zoom-clone.git
   cd zoom-clone
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Set Up Environment Variables**

   Create a `.env` file in the root directory and add your credentials:

   ```env
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_STREAM_API_KEY=
   STREAM_SECRET_KEY=
   ```

4. **Run the Project**

   ```bash
   npm run dev
   ```

5. **Explore Your Project**

   Open [http://localhost:3000](http://localhost:3000) in your browser to view and interact with your application.

---

This format emphasizes clarity, key features, and a step-by-step guide for easy setup, enhancing readability and user engagement.
