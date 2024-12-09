# -CheckMate-Chill-The-Little-AI-That-Could-
developing an agent that plays chess under strict CPU and memory limitations.


FIDE & Google Efficient Chess AI Challenge
Overview
In this simulation competition, participants are tasked with developing a chess-playing AI agent under strict CPU and memory limitations. The focus is on creating efficient, elegant, and innovative solutions to play chess competitively against other AI agents.

Objective
The challenge shifts the emphasis from brute-force computation to efficiency and strategic thinking, encouraging participants to explore optimized algorithms that expand the boundaries of AI research.

Key Features
Efficiency Over Brute Force: Forget massive pre-computed tables and endless search trees. The competition emphasizes smart and efficient designs.
Strategic Gameplay: Compete with other bots in matches where foresight, calculation, and adaptability are critical.
AI Research Expansion: Explore novel, optimized techniques applicable to broader AI challenges beyond chess.
Rules and Constraints
Matches Overview
Time Control: 10 seconds per move with a 0.1-second simple delay (unused time is not banked).
Openings: Randomly selected from a predefined assortment (subject to change during the competition).
Match Pairs: Matches are scheduled in pairs with colors swapped.
Draw Rules:
Threefold repetition automatically results in a draw.
A 50-move rule applies (no captures or pawn moves).
System Constraints
Memory Limit: 5 MiB of RAM (with a stricter update expected).
CPU Allocation: A single 2.20 GHz core.
Submission Size: 64 KiB (compressed).
Evaluation
Skill Ratings
Each bot’s skill is represented as a Gaussian distribution, N(μ,σ²):
μ: The estimated skill level.
σ: The uncertainty of the estimate, which decreases with more games played.
Leaderboard Updates
Wins/Losses/Ties: Affect μ values as follows:
Wins increase μ, losses decrease it, and ties adjust both closer to their mean.
Uncertainty Reduction: σ decreases based on the information gained from match results.
Final Leaderboard
The leaderboard resets after the submission deadline.
Final games determine the leaderboard ranking.
Timeline
Start Date: November 18, 2024.
Entry Deadline: February 4, 2025.
Team Merger Deadline: February 4, 2025.
Final Submission Deadline: February 11, 2025.
Final Evaluation Period: February 11, 2025 - February 25, 2025.
Winner Announcement: February 25, 2025 (estimated).
All deadlines are at 11:59 PM UTC.

Prizes
1st Place: $15,000
2nd Place: $10,000
3rd Place: $10,000
4th Place: $10,000
5th Place: $5,000
Submission Guidelines
Each team can submit up to 5 agents daily.
Older submissions will be deactivated once the team reaches two active agents.
Submissions must pass a self-play validation episode to ensure functionality.
Compressed submission size must not exceed 64 KiB.
Citation
If referencing this competition in academic or research work:

arduino
Copy code
Bovard Doerschuk-Tiberi, Addison Howard, Maggie Demkin, Will Cukierski, and D. Sculley. FIDE & Google Efficient Chess AI Challenge. https://kaggle.com/competitions/fide-google-efficiency-chess-ai-challenge, 2024. Kaggle.
Notes
Chess remains a proving ground for AI innovation, with this competition challenging participants to focus on elegance and efficiency under constraints.
Take advantage of precomputed openings, lightweight evaluations, and dynamic resource allocation to optimize your bot.
