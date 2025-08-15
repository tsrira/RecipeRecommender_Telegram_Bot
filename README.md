
# Recipe Recommender Telegram Bot 🍲

Welcome to the **Recipe Recommender Telegram Bot**, a simple and efficient way to discover vegetarian Indian recipes! Whether you’re craving North Indian, South Indian, or even Rajasthani delicacies, this bot has got you covered.

## 🧑‍🍳 About the Project
The **Recipe Recommender Telegram Bot** allows users to easily find vegetarian Indian recipes through interactive conversations. The bot uses an AI model trained with a variety of Indian recipes, integrated with the Telegram API, and connected to a Pinecone vector store for efficient data retrieval.

## ⚙️ Features
- **Recipe Recommendations:** Get personalized recipe suggestions based on user queries.
- **Categorized Recipes:** Recipes categorized by regional cuisine (e.g., Punjabi, Gujarati, Bengali).
- **Natural Language Understanding:** Interact with the bot using natural language, and it will provide recipe recommendations accordingly.
- **Instant Access:** No need to search online. Just send a message to the bot!

## 🔗 Demo

Check out the bot on Telegram: [Recipe Recommender Telegram Bot](https://t.me/indianreciperecommender_bot)

Live demo of the Telegram Bot --> [Watch Video](https://youtu.be/TkDT7mtq2cc)

## Sample Queries

1️⃣ Regional Recipes

“Show me a Punjabi recipe.”

“Give me a Rajasthani vegetarian dish.”

“What’s a popular South Indian recipe?”

“I want a Gujarati recipe for lunch.”

2️⃣ Ingredients-Based Queries

“I have paneer, what can I cook?”

“Give me a recipe with potatoes and peas.”

“Any recipes with spinach and paneer?”

“I only have lentils, suggest a recipe.”

3️⃣ Dish Type

“I want a curry recipe.”

“Suggest a dessert recipe.”

“Give me a recipe for snacks.”

“Any healthy salad recipes?”

4️⃣ Special Occasion / Festival Recipes

“Show me Diwali recipes.”

“Any Navratri vegetarian dishes?”

“Suggest a recipe for Onam.”

“Give me a Valentine’s Day special dish.”

5️⃣ Quick & Easy

“I want a recipe under 30 minutes.”

“Suggest a simple recipe for beginners.”

“Give me an easy breakfast recipe.”

6️⃣ Random / Fun Queries

“Surprise me with a random recipe.”

“Give me the most popular recipe.”

“I’m craving something spicy.”

“Suggest a kid-friendly vegetarian dish.”

## ⚙️ Technical Details

- **Telegram API**: Used to interact with users on Telegram and send responses.
- **AI Model**: The bot uses an OpenAI-powered AI model to interpret user messages and generate recipe suggestions.
- **Pinecone Vector Store**: Recipes are stored and indexed in Pinecone, enabling fast and efficient retrieval.
- **NLP**: The bot is capable of understanding natural language queries to provide relevant recipe recommendations based on user input.



## 🛠️ Installation

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/RecipeRecommender_Telegram_Bot.git
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your Telegram Bot API credentials by following these steps:
   - Create a new bot on Telegram by talking to [BotFather](https://core.telegram.org/bots#botfather).
   - Copy the API token generated for your bot.

4. Configure the bot with the necessary credentials:
   - Set up your `credentials.json` with your Telegram API credentials and other configurations.

## 🧠 How It Works
1. The bot listens for user messages using the Telegram API.
2. It uses the AI agent to interpret the user's message and generate recipe recommendations.
3. The AI model interacts with Pinecone, where the recipes are stored, and retrieves the most relevant recipes based on the user’s query.
4. The bot then sends the recommended recipes back to the user.

## 📚 Data Sources
The bot is trained on a variety of **Indian vegetarian recipes**, ranging from **North Indian** to **South Indian** and includes a variety of dishes such as **Paneer Butter Masala**, **Dal Tadka**, and **Chole Bhature**.

- **Recipe Dataset:** The recipes are categorized and stored in a structured JSON format.
- **Vector Store:** Recipes are indexed in Pinecone, enabling fast and efficient retrieval.

## 📥 Files Included
- **IndianVegRecipeRecommender.pdf:** A comprehensive guide to Indian vegetarian recipes. (e.g., Paneer, Rajma, Aloo Gobi)
- **Recipe Recommender.json:** Configuration for the Telegram Bot’s NLP model, including the logic for text recognition and response generation.
- **Vector Creation Recipe Recommender.json:** Data processing and vector creation logic for storing and retrieving recipes.

## 💡 Usage
1. After setting up, start the bot using the following command:
   ```bash
   python bot.py
   ```

2. Open your Telegram app, search for **Recipe Recommender Bot**, and start a conversation.

3. Ask for recipes, and the bot will provide recommendations based on your input, such as:
   - "Show me a Punjabi recipe."
   - "I want to make a vegetarian curry."
   - "Give me a recipe for Chole Bhature."

## 🌍 Contributing
Contributions are always welcome! If you have an idea for an improvement or a bug fix, feel free to fork this repository, make changes, and open a pull request.

## 🏷️ License
This project is open-source and available under the [MIT License](LICENSE).

---

Feel free to try out the **Recipe Recommender Bot** and share your feedback!
