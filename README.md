# Hamim AI Backend

## Backend Setup

1. **Install dependencies:**
   ```bash
   cd backend
   npm install
   ```

2. **Create a `.env` file:**
   - In the `backend` folder, create a file named `.env`.
   - Add your OpenRouter API key:
     ```env
     OPENROUTER_API_KEY=your_openrouter_api_key_here
     ```

3. **Run the server:**
   ```bash
   npm start
   ```
   The server will run on port 5000 by default.

## Frontend Update
- Change your frontend fetch URL from `https://openrouter.ai/api/v1/chat/completions` to `/api/ask` (or `http://localhost:5000/api/ask` if running separately).
- Do **not** expose your API key in the frontend.

---

This backend securely proxies requests to OpenRouter using your API key from the environment file. 