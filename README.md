## 👋 Hi, I'm Alan Yong

I'm a third-year Computer Science student passionate about building tools, games, and automation scripts that solve real problems. Below is a curated overview of my most notable projects, with links to full write-ups and source code.

&nbsp;
## 📌 Featured Projects
### [TFT Matchup Predictor](https://github.com/yourusername/another-repo)
Real-time overlay tool for predicting upcoming opponents in *Teamfight Tactics*, using only screen data and a custom-built OCR system.

🔧 **Tech:** AutoHotkey (AHK)  

✨ **Features:**  
- Custom OCR using AHK’s `ImageSearch` to identify player names across two UI elements  
- Real-time overlay showing which opponents can appear next, adapting to matchmaking rules and dynamic lobbies  
- Screen region calibration using static UI anchors for reliable detection  
- Functional in high-ranked competitive matches, where accuracy and timing were critical  

📸 **Visuals:** *(Include a GIF or screenshot demonstrating the overlay and name detection in action)*

💡 *Used in competitive play before Riot Games implemented this feature natively — matched their logic exactly.*

[*🔗 Full write-up*](https://github.com/yourusername/link)  

  
&nbsp;
### 🔹 [AEGIS Multi-Agent Rescue AI](https://github.com/yourusername/aegis-rescue-ai)
A Python AI for the AEGIS multi-agent simulation (CPSC383 assignment) that coordinates multiple rescue robots under messaging delays to save survivors in minimal turns.

**Tech:** Python, AEGIS API

✨ **Highlights:**  
- **Simulation-Based Coordination:** Each agent locally simulates *every* agent’s upcoming moves per turn, effectively creating “instant” shared memory and bypassing the 1-turn message delay.  
- **Distributed Systems Insight:** Overcame communication constraints to keep agents perfectly synchronized without extra messaging.  
- **Team Leadership:** Championed and implemented the core simulation strategy, guiding the team’s design and integration.

📸 *(Include a GIF of agents coordinating on a sample map and a graph comparing total turns with/without the simulation strategy.)*

💡 Achieved 100% assignment score and significantly reduced rescue turns across varied test worlds.  

[*🔗 Full write-up*](https://github.com/yourusername/link)  
  
&nbsp;
### [Project Name 3](https://github.com/yourusername/ahk-script-repo)
> *An AutoHotkey script to automate tedious UI interactions in a desktop app or game.*

- 🔧 **Tech:** AutoHotkey, ImageSearch
- ⚡ **Utility:** Clicks dynamic screen regions based on visual input
- 🖼️ ![Script Preview](assets/ahk-preview.png)

[*🔗 Full write-up*](https://github.com/yourusername/link)  

&nbsp;
### 📂 Other Projects
> <details>
>   <summary>Click to expand</summary>
>
> ### [(Google Sheets) League of Legends – Kha’Zix Item DPS Calculator](https://github.com/yourusername/r-simulator)
> 
> Interactive spreadsheet tool for comparing item builds and DPS outcomes on the champion Kha’Zix, factoring in in-game variables like level, combo path, armor, and existing items. 
> 
> **🔧 Tech:**  
> Google Sheets (no scripts)
> 
> **✨ Notable Features:**  
> - Dynamic checkbox-and dropdown-based UI for skill selection, level, item choices, and enemy stats  
> - Calculates marginal benefit of new items based on current build (e.g. "How much does this item improve my damage if I already own X and Y?")  
> - Graph plots relative damage increases over time (enemy level on X-axis)  
> - Fully formula-driven: uses hundreds of excel-formulas (ie. `IF`, `VLOOKUP`), and reference tabs to model game logic  
> - No scripting or macros used — all logic embedded in spreadsheet cells
> 
> **📸 Visuals:**  
> - GIFs and screenshots available (tool in use + formula breakdowns)  
> - [YouTube tutorial video](#) explaining usage and showcasing features  
> - [Reddit post](#) sharing the tool with the community
> 
> 💡 Used personally and by others to optimize high-level Kha’Zix item builds by quantifying damage tradeoffs. 
>
> [*🔗 Full write-up*](https://github.com/yourusername/link)  
>
> &nbsp;
> ### [HSR Jingliu/Bronya Turn-Order Simulator](https://github.com/yourusername/hsr-simulator)
> A console-based Java tool that models turn order and damage trade-offs for two characters in Honkai Star Rail, then brute-forces every speed-vs-damage combination to find optimal setups.
> 
> **🔧 Tech:** Java  
>
> **✨ Notable Features:**  
> - **Simulation Engine:** Accurately tracks state changes (energy, buffs, strong/weak phases, out-of-turn ults).  
> - **Parameter Search:** Divides speed ranges into user-defined brackets and finds the highest DPS combinations in each.  
> 
> 📸 *Include a GIF or screenshot of console output for one bracket and the corresponding performance graph.*
>
> 💡 Confirmed community-recommended speed strategy with independent simulation.
>
> [*🔗 Full write-up*](https://github.com/yourusername/link)  
> </details>

&nbsp;
## 💼 Résumé & Contact

- 📄 [View My Résumé](link-to-resume.pdf)
- 🔗 [LinkedIn](https://linkedin.com/in/yourprofile)
- 📫 Email: you@example.com

&nbsp;
## 🧠 About Me

I'm particularly interested in systems programming, game development, and automation. I enjoy building tools from scratch and learning new platforms to get things done. My goal is to intern at a company where I can contribute meaningfully to software that reaches users.
