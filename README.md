# ChessMate: AI Chess Coach & Opponent

## 🎯 Overview
**ChessMate** is an Android application that combines the power of a professional chess engine with the conversational abilities of modern AI. Unlike traditional silent chess apps, ChessMate offers a witty, personable opponent or coach who can guide, tease, or even mislead you—just like a real human player.

## ✨ Key Features
- **Strong Chess Engine Integration**  
  Powered by [Stockfish](https://stockfishchess.org/), ensuring accurate rules and competitive gameplay.
- **AI Conversation Layer**  
  Integrated with Gemini or OpenAI-compatible APIs to provide real-time commentary, banter, and coaching.
- **Multiple Personas**  
  Choose your opponent’s style:  
  - Coach: patient and instructive  
  - Beginner: playful and self-deprecating  
  - Advanced Player: analytical and sarcastic  
  - Master: philosophical and high-level
- **Context Awareness**  
  AI receives live board state (FEN/PGN) and can recall past games, recognizing repeated mistakes or familiar traps.
- **Multilingual Support**  
  Play and chat in English, Chinese, or Greek.
- **Game Analysis**  
  Automatic post-game reports highlighting mistakes, brilliant moves, and improvement tips.

## 🛠️ Tech Stack
- **Frontend**: Android (Kotlin + Jetpack Compose)  
- **Chess Engine**: Stockfish (embedded)  
- **AI Layer**: Gemini API / OpenAI API (user-provided key)  
- **Architecture**: MVVM, modular services for chess logic, AI dialogue, and user data  
- **Data Formats**: FEN/PGN for board state and history  

## 🔐 Privacy & Security
- API keys are stored locally and securely, never uploaded to external servers.  
- Game history and preferences remain on-device unless explicitly exported.  
- Users can clear all stored data at any time.

## 🚀 Roadmap
- [ ] MVP: Core chess engine + AI dialogue integration  
- [ ] Game history memory and personalized feedback  
- [ ] Voice interaction for commentary and banter  
- [ ] Achievements and leaderboard system  
- [ ] Cross-platform expansion (Web/Desktop)

## 🤝 Contributing
Contributions are welcome! Please open issues or submit pull requests to help improve ChessMate.

## 📜 License
This project uses the GPL license for Stockfish integration and MIT license for application code. See [LICENSE](LICENSE) for details.
