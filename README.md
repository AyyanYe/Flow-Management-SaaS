# Flow Management SaaS

This project is a comprehensive Software as a Service (SaaS) application designed to streamline workflow management. It leverages modern web technologies and follows a monolithic architecture with an additional micro-service for payment and subscription handling.

## Features

- **Workflow Management**: Easily create, manage, and track workflows.
- **User Authentication**: Secure user management using Clerk.
- **Database Integration**: Prisma ORM connected to a MongoDB database.
- **Payment and Subscription**: Integrated payment processing and subscription handling.

## Technologies Used

- **Next.js**: Framework for server-side rendering and React-based applications.
- **Prisma**: ORM for database modeling and queries.
- **Clerk**: Authentication and user management solution.
- **MongoDB**: NoSQL database for flexible data storage.
- **Tailwind CSS**: Utility-first CSS framework for modern styling.

## Getting Started

To set up the project locally, follow these steps:

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm or yarn

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/AyyanYe/Flow-Management-SaaS.git
   cd Flow-Management-SaaS
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up environment variables**:

   Create a `.env` file in the root directory and add the required environment variables. Refer to the `.env.example` file for guidance.

4. **Run database migrations**:

   ```bash
   npx prisma migrate dev
   ```

5. **Start the development server**:

   ```bash
   npm run dev
   ```

   The application will be available at `http://localhost:3000`.

## Project Structure

The project is organized as follows:

- **`/app`**: Main application components and pages.
- **`/components`**: Reusable UI components.
- **`/lib`**: Utility functions and libraries.
- **`/prisma`**: Prisma schema and migration files.
- **`/public`**: Static assets like images and icons.
- **`/schema`**: GraphQL schemas (if applicable).
- **`/types`**: TypeScript type definitions.
- **`middleware.ts`**: Middleware configurations.
- **`next.config.mjs`**: Next.js configuration file.
- **`tailwind.config.ts`**: Tailwind CSS configuration.

## API Routes

The application includes several API routes for managing different functionalities. These routes are defined in the `/pages/api` directory:

- **Authentication Routes**: Handled by Clerk for user authentication and session management.
- **Workflow Routes**: CRUD operations for workflows.
- **Payment Routes**: Payment processing and subscription management.

Each route is implemented as a serverless function, leveraging Next.js API capabilities.

## Libraries and Dependencies

Key libraries used in this project:

- **Next.js**: React framework for server-side rendering.
- **React**: Library for building user interfaces.
- **Prisma**: Next-generation ORM for data interaction.
- **Clerk**: User authentication and management.
- **MongoDB**: Flexible NoSQL database.
- **Tailwind CSS**: Modern CSS framework for styling.
- **Axios**: HTTP client for API requests.
- **Stripe**: Payment processing platform for handling subscriptions.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Acknowledgements

Special thanks to the developers and contributors of the tools and frameworks used in this project.

---

