# Clone-Website
# Orchids SWE Intern Challenge Template

This project consists of a backend built with FastAPI and a frontend built with Next.js and TypeScript.

## Setup Instructions from Anshul
1. **You need to get an OpenAI API Key**
- Visit (https://platform.openai.com/)
- Create a new API key through your account

2. **Set the Variables in the Environment**
   For Windows:
   ```powershell
   # Temporary (Command Prompt)
   set OPENAI_API_KEY=your-api-key-here

   # Temporary (PowerShell)
   $env:OPENAI_API_KEY="your-api-key-here"

   # Permanent (System Environment Variables)
   1. Press Windows + R
   2. Type 'sysdm.cpl'
   3. Go to 'Advanced' tab
   4. Click 'Environment Variables'
   5. Under 'User variables', click 'New'
   6. Variable name: OPENAI_API_KEY
   7. Variable value: your-api-key-here

For Mac/Linux:
   ```bash
   # Temporary Setup
   export OPENAI_API_KEY="your-api-key-here"

   # Permanent Setup
   echo 'export OPENAI_API_KEY="your-api-key-here"' >> ~/.bashrc
   ```

## Backend

The backend uses `uv` for package management.

### Installation

To install the backend dependencies, run the following command in the backend project directory:

```bash
uv sync
```

### Running the Backend

To run the backend development server, use the following command:

```bash
uv run fastapi dev
```

## Frontend

The frontend is built with Next.js and TypeScript.

### Installation

To install the frontend dependencies, navigate to the frontend project directory and run:

```bash
npm install
```

### Running the Frontend

To start the frontend development server, run:

```bash
npm run dev
```
