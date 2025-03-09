# MovieLLMApp
It is a movie recommender system using LangChain and OpenAI's GPT models.

Technologies Used:
✅ LangChain (for LLM-powered workflows)
✅ OpenAI GPT (for generating responses)
✅ Python-dotenv (for API key management)

Key Components:
🔹 Messages & Prompt Templates – Structures conversations & dynamic prompts for responses.
🔹 Chaining & Composed Chain – Executes multiple steps logically.
🔹 RunnableLambda – Custom functions to filter/refine movie recommendations.
🔹 Pipe Function – Connects multiple transformations before sending queries to LLM.
🔹 Parallel Chaining (RunnableParallel) – Runs multiple tasks (recommendation, rating, translation) simultaneously.

Purpose:
🎬 Dynamically suggests movies based on user preferences.
🌍 Supports translations for multilingual users.
⚡ Optimized with parallel execution for efficiency.

