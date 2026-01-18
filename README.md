# My Portfolio

This is a personal portfolio website built with Next.js and Tailwind CSS.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repo-url>
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Build the project for production:
   ```bash
   npm run build
   ```

5. Deploy to Azure:
   - Ensure you have the Azure CLI installed.
   - Run the following command:
     ```bash
     az webapp up --name portfolio --resource-group portfolio-group
     ```

## Features

- Dark mode toggle
- Sections: Projects, About Me, Contact
- Responsive design

## Technologies Used

- Next.js
- Tailwind CSS
- Azure Static Web Apps