4ª Week: Meeting 14/07/2026   
**8º ARTICLE:**  
**Search performed on the search engine** **: **  
Google Scholar   
**Search term:**  
Intelligent Adaptive Games  
**Selection Criteria:**  
Publication date from 2020 to 2026 – Year 2024   
Citations above 5 – Citations 15  
**Article ** **Title** **:**  
# Improved Belgian AI Algorithm for Dynamic Management in Action Role-Playing Games   
**Link:** ** **  
https://www.mdpi.com/2076-3417/12/22/11860  
**File name:**  
mi2024.pdf  
**Resume:**  
**ChatGPT prompt:** Summarize the following text in 300 words.  
This paper presents the **Improved Belgian Artificial Intelligence (IBAI)** algorithm, an enhanced combat management system for action role-playing games (ARPGs). It addresses the limitations of the original  **Belgian Artificial Intelligence (BAI)** algorithm, which manages enemy attacks using fixed rectangular grids. Although BAI improves upon earlier methods such as the Kung-Fu Circle, it suffers from limited adaptability, only supports melee combat, produces uneven interaction areas, and often results in repetitive enemy behavior and poor combat diversity.   
The proposed IBAI introduces four key improvements. First, it replaces BAI’s grid system with the **Melee-Ranged Buffer-Pursuit (MRBP) ring model**, a player-centered structure composed of concentric rings that accommodates both melee and ranged enemies while allowing flexible combat spacing. Second, it incorporates  **Dynamic Difficulty Adjustment (DDA)** by modifying combat parameters in real time according to player performance, maintaining an engaging challenge. Third, it introduces the  **Grid Priority (GP)** mechanism and the  **Real-Time Induction and Distribution (RID)** algorithm, enabling more efficient enemy positioning and attack allocation as combat conditions change. Finally, the algorithm adds  **Attack Weight Threshold (AWT)** and  **Global Cooldown (GCD)** mechanisms to prevent repetitive use of powerful attacks, thereby increasing combat variety and improving game balance.   
To evaluate the approach, the authors implemented both BAI and IBAI combat systems in **Unreal Engine 4** and conducted extensive static and dynamic tests, followed by gameplay experiments involving 55 participants. The experiments compared enemy management, attack allocation, interaction areas, combat diversity, and player experience. Results showed that IBAI successfully handled both melee and ranged enemies, adapted more effectively to changing combat scenarios, distributed attacks more intelligently, and produced more varied encounters. Questionnaire results further indicated higher player satisfaction, with IBAI achieving an average score  **10.086 points higher** than BAI while exhibiting  **lower score variance (0.079)**, reflecting more consistent player experiences. Overall, the study concludes that IBAI provides a more adaptive, balanced, and efficient combat management framework, improving gameplay quality while helping developers reduce implementation complexity and potentially increasing player retention.   
   
**9º ARTICLE:**  
**Search performed on the search engine** **: **  
Google Scholar   
**Search term:**  
Fighting Games DDA  
**Selection Criteria:**  
Publication date from 2020 to 2026 – Year 2020  
Citations above 5 – Citations 28  
**Article ** **Title** **:**  
# Mastering Fighting Game Using Deep Reinforcement Learning With Self-play  
**Link:** ** **  
https://ieeexplore.ieee.org/abstract/document/9231639  
**File name:**  
kim2020.pdf  
**Resume:**  
**ChatGPT prompt:** Summarize the following text in 300 words.  
This paper presents a deep reinforcement learning (DRL) approach for creating a high-performing AI agent for one-on-one fighting games using the **FightingICE** environment. The authors combine  **Proximal Policy Optimization (PPO)**,  **self-play**, and  **Monte Carlo Tree Search (MCTS)** to train an agent capable of outperforming previous competition-winning bots. Fighting games provide an ideal research platform because they are more complex than board games but less computationally demanding than real-time strategy games.  
The proposed method uses a carefully designed state representation that combines both **delayed game information** and a  **simulated prediction of the current state**, allowing the agent to compensate for the environment’s built-in observation delay. The reward function includes three components: damage dealt to the opponent (HP reward), match outcome (win/loss reward), and a time penalty that encourages faster victories. PPO was selected because it effectively handles continuous state spaces and provides stable policy updates.  
Training is divided into two stages. In the first stage, the agent learns by competing exclusively against an MCTS-based opponent, acquiring general gameplay knowledge. In the second stage, self-play is introduced while continuing to face MCTS opponents. Previous versions of the agent are stored in an opponent pool, and prioritized matchmaking selects stronger opponents more frequently, preventing the agent from overfitting to a single strategy.  
Extensive experiments examined state representations, reward shaping, and different opponent compositions. Results show that combining delayed and simulated states significantly improves learning. Using all three reward components produces the strongest overall performance, although the time penalty slightly slows learning while yielding faster victories. The best training strategy mixes **MCTS and self-play in a 1:3 ratio**, balancing broad tactical experience with continual adaptation.  
The final agent achieved an average **94.4% win rate** against top FightingICE competition bots, defeating nearly all previous champions. The trained AI learned sophisticated behaviors such as waiting for optimal attack opportunities rather than attacking continuously. The study demonstrates that integrating PPO, self-play, and MCTS creates a robust and highly competitive fighting game AI while establishing a strong baseline for future reinforcement learning research in real-time combat games.  
   
**10º ARTICLE:**  
**Search performed on the search engine** **: **  
Google Scholar   
**Search term:**  
Fighting Games DDA  
**Selection Criteria:**  
Publication date from 2020 to 2026 – Year 2022  
Citations above 5 – Citations 10  
**Article ** **Title** **:**  
# Dynamic Difficulty Adjustment in a Multiplayer Minecraft Server  
**Link:** ** **  
https://dl.acm.org/doi/abs/10.1145/3572921.3572946  
**File name:**  
zeng2022.pdf  
**Resume:**  
**Gemini prompt:** Summarize the following text in 300 words.  
## **Overview of Multiplayer Minecraft DDA**  
In multiplayer Minecraft survival and MMORPG servers, players with varying skill levels often fight non-player enemies (mobs) together. Because these servers typically operate on a fixed difficulty, this setup can lead to frustration for novices and boredom for experienced players. To address this mismatch, Zeng and Sweetser (2022) proposed a **Multiplayer Minecraft Dynamic Difficulty Adjustment (DDA) Framework** that automatically scales mob strength to accommodate all nearby players.   
## **The DDA Framework Structure**  
The proposed framework relies on three core operational components:   
- **Data Collection:** Gathers heuristics of player performance—such as shooting accuracy, success at blocking, deaths, and skill levels—and tracks when mobs were last damaged to avoid confusing players with mid-fight attribute changes.   
- **When to Adjust:** Triggers adjustments when a player dies, when a mob spawns, or periodically every five seconds (100 ticks).   
- **How to Adjust:** Quantifies player performance and maps it to mob strength levels. Using a Gaussian function, the algorithm heavily weights the influence of closer players on a mob's level to ensure local relevance.   
## **Evaluation and Results**  
The authors evaluated their system with 23 participants across three gameplay configurations: static difficulty (Scenario 1), adjustment only at spawn (Scenario 2), and continuous real-time adjustment (Scenario 3).   
- **Difficulty:** Perceived difficulty successfully shifted from "somewhat easy" in the static setup to a balanced "just right" in Scenario 3.   
- **Enjoyment:** Overall enjoyment remained high across all three configurations, indicating players appreciated the tailored challenge.   
- **Feedback:** Participants actively disliked sudden mid-combat level changes, noting that mobs leveling up right before dying caused frustration.   
## **Future Directions**  
While effective for combat, the study is limited by its small sample size and its sole focus on mobs. Future research aims to integrate objective game telemetry and expand DDA systems to encompass non-combat Minecraft activities, such as construction and resource gathering.   
   
**11º ARTICLE:**  
**Search performed on the search engine** **: **  
Google Scholar   
**Search term:**  
Fighting Games DDA  
**Selection Criteria:**  
Publication date from 2020 to 2026 – Year 2022  
Citations above 5 – Citations 33  
**Article ** **Title** **:**  
### Diversifying dynamic difficulty adjustment agent by integrating player state models into Monte-Carlo tree search  
**Link:** ** **  
https://www.sciencedirect.com/science/article/pii/S0957417422009757  
**File name:**  
moon2022.pdf  
**Resume:**  
**ChatGPT prompt:** Summarize the following text in 300 words.  
This paper proposes a novel **dynamic difficulty adjustment (DDA)** framework that improves player experience by adapting game AI according to players’  **affective states** rather than relying solely on traditional performance measures such as health points, scores, or win rates. The authors argue that conventional DDA methods focus mainly on player proficiency, producing predictable gameplay that may not satisfy diverse player preferences. To address this limitation, they integrate  **machine learning-based player state models** with  **Monte Carlo Tree Search (MCTS)**, enabling AI opponents to dynamically modify their strategies based on estimated player emotions and experiences.   
The proposed system predicts four player states derived from the **Game Experience Questionnaire (GEQ)**:  **challenge, competence, valence, and flow**. Instead of using external sensors, the player-state models rely only on in-game features collected from gameplay logs. Machine learning classifiers estimate the probability of each player state, and these predictions become the scoring function for the MCTS algorithm. During gameplay, MCTS simulates future actions, combines simulated and real gameplay data, and selects moves that maximize the targeted player state rather than simply increasing the AI’s chances of winning.   
The authors evaluated the approach using a fighting game and trained their models on gameplay data collected from 43 participants. A user study involving 20 players compared four state-specific AI agents with a traditional health-point-based DDA agent. Results showed that the proposed agents generated distinct playing styles tailored to different emotional objectives. Agents targeting **competence, valence, and flow** significantly improved both their intended psychological states and overall player experience compared with the baseline. However, the challenge-focused agent did not achieve a significant improvement, likely due to limitations of the game environment.   
Overall, the study demonstrates that incorporating affective player modeling directly into AI decision-making creates more personalized and engaging gameplay. The authors conclude that their approach can support diverse player preferences, reduce manual game balancing, and potentially extend beyond games to applications such as education and healthcare, while acknowledging that future work should improve state prediction accuracy and validate the method across more complex games and AI techniques.   
   
**12º ARTICLE:**  
**Search performed on the search engine** **: **  
Google Scholar   
**Search term:**  
procedural content generation in games  
**Selection Criteria:**  
Publication date from 2020 to 2026 – Year 2020  
Citations above 5 – Citations 281  
**Article ** **Title** **:**  
# PCGRL: Procedural Content Generation via Reinforcement Learning  
**Link:** ** **  
https://ojs.aaai.org/index.php/AIIDE/article/view/7416  
**File name:**  
Khalifa2020.pdf  
**Resume:**  
**ChatGPT prompt:** Summarize the following text in 300 words.  
This paper introduces **PCGRL (Procedural Content Generation via Reinforcement Learning)**, a novel framework that applies reinforcement learning (RL) to automatically generate game levels. Unlike traditional procedural content generation (PCG) methods that rely on handcrafted rules, optimization algorithms, or supervised learning from existing levels, PCGRL treats level generation as a sequential decision-making problem. Instead of searching directly for complete game levels, the approach learns a policy that determines the best sequence of modifications to maximize the final quality of the generated level. This enables fast level generation after training without requiring example levels for supervision.   
The framework models level generation as a **Markov Decision Process (MDP)** in which an agent iteratively edits a randomly initialized level. At every step, the agent observes the current level, performs a small modification, receives a reward based on how much the change improves the level, and continues until a termination condition is met. The framework consists of three main components: a  **problem module** defining the generation objectives and reward function, a  **representation module** describing the state and action spaces, and a  **change percentage** parameter that limits the number of modifications allowed during an episode. Three different level representations are explored:  **Narrow**, where edits occur at predetermined locations;  **Turtle**, where the agent moves through the map while editing; and  **Wide**, where the agent has complete control over edit locations.   
The authors evaluated PCGRL on three game environments: **Binary maze generation**,  **The Legend of Zelda**, and  **Sokoban**, using the  **Proximal Policy Optimization (PPO)** algorithm. Results showed that all three representations successfully generated playable levels, although performance varied depending on the game. Binary levels achieved the highest success rates, while Zelda and Sokoban required longer training and stronger solvers to create more challenging levels. Importantly, the trained agents typically modified only a small fraction of the map, preserving the original structure instead of overwriting it completely. Different representations also produced distinct design styles despite similar success rates.   
The paper concludes that reinforcement learning is a promising alternative for procedural content generation. By learning content-generation policies rather than searching directly for levels, PCGRL offers efficient runtime generation, supports diverse design styles, and can be integrated into mixed-initiative design tools where humans and AI collaboratively create game content. Future work includes extending the framework to more complex games, improving reward design, supporting human-AI collaboration, and exploring advanced RL techniques such as self-play, hierarchical agents, and cooperative multi-agent generation.   
   
