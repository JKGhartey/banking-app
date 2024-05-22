---

# FinVista: A Modern Fintech Banking Application

FinVista is a comprehensive financial platform designed to help users manage their finances effortlessly. With FinVista, users can connect multiple bank accounts, view real-time transaction updates, transfer money within the platform, and monitor their financial health with ease. Built using Next.js, FinVista offers a robust and user-friendly experience tailored to meet the needs of modern users.

📋 **Contents**

- 🤖 [Overview](#overview)

- ⚙️ [Technology Stack](#technology-stack)

- 🔋 [Core Features](#core-features)

- 🤸 [Getting Started](#getting-started)

- 🕸️ [Code Samples](#code-samples)

- 🔗 [Resources](#resources)

- 🚀 [Additional Information](#additional-information)

- 🚨 [Video Tutorial](#video-tutorial)

---

### 🤖 Overview

FinVista is a financial SaaS platform created with Next.js. It allows users to connect multiple bank accounts, view real-time transaction updates, transfer money to other platform users, and manage their finances all in one place.

For support and community discussions, join our active Discord community of over 34k+ members.

---

### ⚙️ Technology Stack

- **Next.js**

- **TypeScript**

- **Appwrite**

- **Plaid**

- **Dwolla**

- **React Hook Form**

- **Zod**

- **TailwindCSS**

- **Chart.js**

- **ShadCN**

---

### 🔋 Core Features

- **Secure Authentication:** Implement server-side rendering (SSR) with thorough validation and authorization mechanisms.

- **Bank Account Integration:** Use Plaid to link multiple bank accounts.

- **Dashboard Overview:** Display a comprehensive overview of the user's financial status, including balances, recent transactions, and spending categories.

- **Bank Management:** List all connected banks along with account details and balances.

- **Transaction Records:** Provide pagination and filtering for viewing transaction history.

- **Live Updates:** Automatically update relevant sections when new bank accounts are connected.

- **Funds Transfer:** Facilitate money transfers via Dwolla to other accounts, requiring necessary fields and recipient bank IDs.

- **Responsive Design:** Ensure the app works smoothly across various devices, including desktops, tablets, and smartphones.

These features, along with a focus on code structure and reusability, make this app robust and user-friendly.

---

### 🤸 Getting Started

Set up the project locally by following these steps.

**Prerequisites**

Ensure you have the following installed:

- Git

- Node.js

- npm (Node Package Manager)

**Clone the Repository**

```sh

git clone https://github.com/adrianhajdin/banking.git

cd banking

```

**Install Dependencies**

```sh

npm install

```

**Configure Environment Variables**

Create a `.env` file in the project root and add your credentials:

```sh

#NEXT

NEXT_PUBLIC_SITE_URL=

#APPWRITE

NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1

NEXT_PUBLIC_APPWRITE_PROJECT=

APPWRITE_DATABASE_ID=

APPWRITE_USER_COLLECTION_ID=

APPWRITE_BANK_COLLECTION_ID=

APPWRITE_TRANSACTION_COLLECTION_ID=

APPWRITE_SECRET=

#PLAID

PLAID_CLIENT_ID=

PLAID_SECRET=

PLAID_ENV=

PLAID_PRODUCTS=

PLAID_COUNTRY_CODES=

#DWOLLA

DWOLLA_KEY=

DWOLLA_SECRET=

DWOLLA_BASE_URL=https://api-sandbox.dwolla.com

DWOLLA_ENV=sandbox

```

Fill in the placeholders with your actual account credentials, which you can obtain from Appwrite, Plaid, and Dwolla.

**Run the Project**

```sh

npm run dev

```

Visit [http://localhost:3000](http://localhost:3000) in your browser to see the project in action.

