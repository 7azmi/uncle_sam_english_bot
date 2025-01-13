# Uncle Sam AI 🤖

Uncle Sam AI is a Telegram bot designed to make learning a new language engaging, personalized, and interactive. It leverages AI to provide real-time conversational practice, grammar corrections, and progress tracking for users of all skill levels.

## Key Features

1. **User Login and Profile Creation:**
   - Users can set up their profiles by providing their name, language of interest, and current skill level. This ensures personalized interactions.

2. **Daily Conversation Prompts:**
   - The bot generates daily prompts tailored to the user’s skill level. Beginners receive simple sentences, while advanced learners get idioms and cultural phrases to practice.

3. **Grammar Correction:**
   - Analyzes user input for grammatical errors and provides corrections along with explanations, helping users improve their language skills.

4. **Progress Milestone Tracking:**
   - Tracks user progress and celebrates milestones with encouraging messages and virtual badges.

## AI Theoretical Framework

### Knowledge Representation (KR)
The bot’s behavior is guided by the following KRs:
- **User Profile and Skill Level:**
  - Tracks user details and adapts prompts and feedback accordingly.
- **Daily Prompts:**
  - Stores a library of prompts categorized by difficulty.
- **Grammar Rules:**
  - Maintains rules for identifying and correcting errors.
- **Progress Tracking:**
  - Logs user interactions and milestones.

### State Space Search
The user’s journey through the bot can be represented as a state space:
1. **Initial State:** User has no profile.
2. **Intermediate States:** User engages with prompts, receives corrections, and practices.
3. **Goal State:** User achieves milestones (e.g., mastering 30 prompts).

**Transitions:**
- Actions like profile creation, responding to prompts, and achieving milestones drive state transitions.

### PEAS Model
- **Performance Measure:** Increased engagement, improved grammar, and milestone achievements.
- **Environment:** User interactions via Telegram.
- **Actuators:** Text-based responses, corrections, and progress updates.
- **Sensors:** User inputs and history logs.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/7azmi/uncle_sam_english_bot.git
    ```
2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```
3. Set up environment variables:
    ```sh
    export BOT_TOKEN=<Telegram Bot Token>
    export GEMINI_API_KEY=<Gemini API Key>
    ```
4. Personalize AI instructions in `ai_instructions.txt`.
5. Run the bot locally:
    ```sh
    python app.py
    ```
   
## Contributing
Contributions are welcome to enhance the bot’s features and expand its language capabilities. Feel free to submit a pull request or suggest improvements.

## License
You see it, it's yours.