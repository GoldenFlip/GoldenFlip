# GoldenFlip - A Provably Fair Coin Flip Game 🎲

Welcome to **GoldenFlip**, the ultimate decentralized coin flip game built for transparency and fairness. Flip the coin, test your luck, and win big with provably fair results! 💰

## 🚀 Features

- **Provably Fair**: Ensures each flip is verifiably random.
- **95% Payout**: Earn up to 95% of your bet amount on each win.
- **Decentralized & Transparent**: All bets and outcomes are publicly logged.
- **Simple UI**: Easy-to-use interface with smooth animations.

---

## 🎮 How It Works

1. **Place Your Bet**: Enter your desired bet amount in SOL.
2. **Choose Your Side**: Select either "Heads" or "Tails."
3. **Flip the Coin**: Watch as the coin spins and lands on a random result.
4. **Win or Lose**: If your choice matches the result, you win!

---

## 🔒 Provably Fair Mechanism
GoldenFlip uses the following formula to ensure fairness:

```
result = SHA256(playerSeed + serverSeed + roundID) % 2
```

- **Player Seed**: Provided by the player for added randomness.
- **Server Seed**: Generated and revealed post-flip to ensure transparency.
- **Round ID**: A unique identifier for each coin flip.

> Players can verify the fairness of each result using the SHA256 hash and seeds.

---

## 🛠️ Installation

Clone the repository and run it locally:

```bash
git clone https://github.com/GoldenFlip/GoldenFlip.git
cd GoldenFlip
npm install
npm start
```

---

## 📊 Game Stats

- Total Flips: `1000`
- Total Wins: `480`
- Total Winnings: `960 SOL`

Stay updated with your performance and game history.

---

## 📬 Contact

For inquiries or feedback, feel free to reach out:
- Email: support@goldenflip.com
- Discord: [GoldenFlip Community](https://discord.gg/goldenflip)

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

🌟 **Enjoy flipping and may the odds be ever in your favor!** 🌟
