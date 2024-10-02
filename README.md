# StreamDocs

StreamDocs is a real-time collaborative text editor, designed to replicate the functionality of Google Docs. Built with Next.js and styled with TailwindCSS, it allows multiple users to collaborate on documents in real time. The app includes user authentication and document management features, ensuring a seamless and secure experience across all devices.

## Features

- **Authentication**
  - Secure sign-in and session management via GitHub using [NextAuth](https://next-auth.js.org/).
- **Collaborative Text Editor**
  - Real-time editing powered by [Liveblocks](https://liveblocks.io/), allowing multiple users to work on the same document simultaneously.
  - Built with [Lexical Editor](https://lexical.dev/) for rich-text editing capabilities.
- **Document Management**

  - **Create Documents**: Users can create new documents which are automatically saved.
  - **Delete Documents**: Documents can be deleted by the owner.
  - **Share Documents**: Share documents via email or link, with view and edit permissions.
  - **List Documents**: View and search through all owned and shared documents, with sorting functionality.

- **Comments**

  - Add inline comments directly in the document and engage in threaded discussions.

- **Active Collaborators**

  - Display real-time presence indicators for active collaborators working on the document.

- **Notifications**

  - Notify users when a document is shared, comments are made, or collaborators perform specific activities.

- **Responsive Design**
  - Fully responsive design that works across all device types.

## Tech Stack

- **Next.js**: Handles the front-end UI and server-side rendering.
- **TypeScript**: Used for type safety and enhanced development experience.
- **Liveblocks**: Powers real-time collaborative features.
- **Lexical Editor**: Rich text editing functionality.
- **ShadCN**: Provides accessible and customizable UI components.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

- [Node.js](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/StreamDocs.git
   cd StreamDocs
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:

   Create a `.env.local` file at the root of your project and add the following variables:

   ```bash
   NEXTAUTH_URL=http://localhost:3000
   GITHUB_ID=your_github_client_id
   GITHUB_SECRET=your_github_client_secret
   ```

4. Run the development server:

   ```bash
   npm run dev
   ```

   The app will be available at `http://localhost:3000`.

### Deployment

You can deploy this project to platforms like [Vercel](https://vercel.com/) for optimal performance.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
