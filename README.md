# ALX Rick and Morty App (GraphQL Integration)

This project is part of the **alx-graphql-0x01** repository. It serves as an introduction to integrating **GraphQL** with **React** (via Next.js) using **Apollo Client**. The application fetches data from the public [Rick and Morty API](https://rickandmortyapi.com/graphql).

## 📂 Project Structure

This directory (`alx-rick-and-morty-app`) contains the Next.js application configured with TypeScript, Tailwind CSS, and Apollo Client.

### Key Files Created/Modified
* **`graphql/apolloClient.ts`**: Initializes the Apollo Client instance and connects to the Rick and Morty GraphQL endpoint.
* **`graphql/queries.ts`**: Contains defined GraphQL queries (e.g., `GET_EPISODES`) to fetch data.
* **`pages/_app.tsx`**: Wraps the entire application in the `ApolloProvider` to make the client available throughout the component tree.

---

## 🚀 Getting Started

Follow these instructions to set up the project locally.

### Prerequisites
* Node.js installed
* npm or yarn

### Installation

1.  **Navigate to the project directory:**
    ```bash
    cd alx-rick-and-morty-app
    ```

2.  **Install dependencies:**
    This includes Next.js defaults, Apollo Client, and GraphQL.
    ```bash
    npm install
    # Explicitly install Apollo and GraphQL dependencies used in this task
    npm install @apollo/client graphql @types/graphql
    ```

### Running the Application

Start the development server:

```bash
npm run dev
