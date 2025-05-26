# 👋 Hello, I'm Tetra! A Developer's Journey into Code & Creation

Welcome to my little corner of the digital world! I'm a 18 years old (as of 2025) JavaScript developer hailing from Russia, currently navigating the exciting challenges of university studies at MTUCI (Moscow Technical University of Communications and Informatics) after a solid foundation in physics and mathematics from the 23rd Lyceum.

My moniker, "Tetra," isn't just a random string of characters. It’s a nod to the **tetrahedron** – a geometric figure I deeply admired for its perfect simplicity, four faces, and four vertices. This shape, a fundamental building block, mirrors my philosophy towards software development: I strive for **structural integrity, inherent elegance, and foundational robustness** in every line of code I write. Like the tetrahedron, good software should be solid, well-balanced, and elegantly designed.

---

## 💡 My Coding Philosophy & Approach

My journey into programming began roughly seven years ago, initially sparked by a desire to create games. While an early brush with C++ almost veered me off course, I soon found my footing in web development, crafting my first clicker games and interactive narratives. This initial phase was significantly shaped by the supportive community at SoloLearn, especially friends like Alisa and Squad69.

My learning style is distinct: I don't rely heavily on traditional courses or textbooks. Instead, I **set a clear objective, deconstruct it into manageable components, identify knowledge gaps, and then immerse myself in practical application** – often for 10-15 hours at a stretch – until the goal is achieved. It's a hands-on, goal-driven process that has allowed me to explore diverse domains.

**A Note on AI in Development:**
While I recognize the advancements in AI, particularly Large Language Models (LLMs), my stance is that **over-reliance on AI for code generation can diminish a developer's critical thinking, problem-solving skills, and deep understanding of the underlying mechanisms.** Code crafted by a human, with careful thought and consideration for context and nuance, often leads to more robust, maintainable, and truly optimized solutions. **I primarily use AI tools like LLMs as advanced search engines for accessing documentation or exploring theoretical concepts**, rather than for generating executable code. I believe true craftsmanship in software development comes from human ingenuity and a deep understanding of the craft.

Beyond code, I have a passion for:
*   🎨 **Visual Arts:** I enjoy sketching and drawing, often capturing scenes from daily life – a quiet house, a forest clearing, or a park bench.
*   ✍️ **Creative Writing:** I dabble in crafting short stories, typically in the fantasy or science fiction genres, often weaving in mathematical or physics-related concepts for readers who appreciate a bit more depth.

---

## 🛠️ My Technical Arsenal: Languages, Tools, & Expertise

Here's a rundown of the technologies I work with:

**Core Programming Languages:**
*   **JavaScript:** My primary language and area of deep expertise. I've spent years working with its ecosystem, particularly on the server-side with Node.js.
*   **Lua:** Specifically used for modding Scrap Mechanic, where it's the primary scripting language for custom behaviors and game logic.
*   **C#:** Employed in game development contexts, including experiments with game engines.
*   **Java:** Another language encountered primarily through Minecraft (e.g., Forge/Fabric) and Mindustry modding.
*   **SQL:** Proficient in designing and interacting with relational databases, primarily MySQL, for local project deployments.
*   **Arc:** Explored this Lisp dialect for experimental scripting and to broaden my understanding of different programming paradigms.
*   **Windows Scripting:** Familiar with `.bat` and `.vbs` for automation tasks on Windows environments (a relic from my "old-school" days!).

**Frameworks, Libraries & Environments:**
*   **Node.js:** Extensive experience building backend systems, APIs, and, of course, bots.
*   **Express.js:** Familiar with this framework for building web applications and APIs on Node.js.
*   **React:** **Currently, I am passionately dedicating time to mastering React.** I'm diving deep into its concepts and best practices through official documentation and hands-on projects.
*   **Bot Development Libraries:** Well-versed in `telegraf.js`, `grammy.js` (for Telegram bots), and other utility libraries like `node-canvas` (for image manipulation) and `path` (for file system operations).

**Databases:**
*   **MySQL:** Experience with designing schemas, writing queries, and managing databases for various projects, always deployed locally.

**Tools & Platforms:**
*   **Version Control:** **Git & GitHub.** I'm actively deepening my understanding and usage of Git for version control and GitHub for collaboration and project showcasing. This is a key area of development for me.
*   **IDE/Editors:** My coding journey started with Notepad (yes, really!), moved to Atom, and for the past ~six months, I've been a dedicated **VS Code** user.
*   **Hosting:** Experience with self-hosting projects and using platforms like `Bisquit.host` for MC server when local resources weren't sufficient.

**Unique Skill:**
*   I possess the ability to quickly **reactivate and re-familiarize myself with languages or technologies I've worked with in the past**, typically getting back up to speed within 9-10 hours of focused effort.

---

## 🚀 Featured Projects: A Glimpse into My Work

I've had the opportunity to work on a diverse range of projects. Here are a few highlights that I'm particularly proud of:

### 1. 💰 MoneyBot: A Telegram-Based Economic Ecosystem
This was one of my most ambitious early projects, a Telegram bot that evolved into a complex virtual economy.
*   **Core Functionality:** Users earned "Coins" (a virtual currency) for activity in my chat, which also featured custom-built spam and flood protection.
*   **Advanced Features:**
    *   A "job market" where users could "hire" others to post content in their channels, with the bot facilitating and tracking these interactions.
    *   **Real-world Monetization:** Implemented a system where users could purchase "Coins" (1 RUB for 100 Coins), involving integration with Sberbank's payment systems (a significant undertaking at the age of 16, navigated with my father's help).
    *   Robust Terms of Service to ensure fair use and delineate responsibilities.
*   **Technical Achievement – Security:** The bot's data integrity was paramount. I designed a **custom triple-database system**:
    1.  **Current DB:** Handled live transactions and user data.
    2.  **Buffer DB:** Acted as a "log stream" for all changes.
    3.  **Final DB:** A verified snapshot of the data.
    Changes were written to Current and Buffer, then validated against Final before committing. These databases were hosted on different machines with a proprietary algorithm for synchronization. This system successfully **withstood numerous hacking attempts.**
*   **Scale & Impact:** At its peak, MoneyBot served over **10,000 users**. The underlying project ("Amigo Bot," its predecessor) also became the base for a side venture where I developed and hosted around **300 custom bots for clients**, providing a significant income stream for me at the age of 16.
*   **Development Principle:** This entire system was built **without reliance on AI code generators**, ensuring every security aspect was meticulously hand-crafted and understood.

### 2. 🧠 Fenix.AI: A JavaScript Library for Simplified Neural Networks
Driven by a desire to demystify AI, I developed Fenix.AI, a JavaScript library aimed at making neural network creation more accessible.
*   **Core Goal:** To enable the creation of a basic, untrained neural network with a single, intuitive line of code, abstracting away much of the boilerplate. For instance: `let AI = Fenix.AI.create(10, 19, 22, 4, 3)` would establish the data structures to store and manage neuron states, connection weights, and propagation values for a neural network configured with 10 inputs, 3 hidden layers (with 19, 22, and 4 neurons respectively), and 3 outputs.
*   **User-Friendliness:** The library provided a simplified API for training and interacting with the network.
*   **Success Story:** The abstraction was effective enough that my 12-year-old cousin was able to use Fenix.AI to create and train her first neural network for a tic-tac-toe game.
*   **Ethical Development:** The library itself was built through traditional coding practices, focusing on clarity and understanding of the implemented algorithms.
*   **Future:** I plan to revisit and further develop Fenix.AI with my friend Teresh.

### 3. 🎮 Game Modding Adventures
Modding games has been a long-standing passion, allowing me to dissect and extend game mechanics.
*   **Terraria – "Disaster Mod":**
    *   An ambitious mod focused on creating a novel magic weapon system with fluid, incremental progression.
    *   The core concept involved a single "spellbook" weapon that could be augmented with thousands of different craftable improvements (power, damage, homing, etc.).
    *   To manage the sheer number of crafting recipes (which would have been ~1.2GB of data), I wrote custom scripts that **generated these recipes dynamically at runtime** when the mod loaded.
    *   Unfortunately, due to this runtime code generation, the mod did not pass the TModLoader moderation process and remained a local project.
*   **Mindustry – "KaDD Mod":**
    *   A large-scale overhaul mod that introduced an entirely new planet, completely devoid of vanilla content.
    *   Featured new crafting systems, unique enemies, distinct weaponry, a new campaign, and a more perilous progression where core resources were often flammable or explosive, meaning "one mistake and you're done."
    *   The main GitHub repository for this mod was unfortunately lost, but a "Lite" version (with significantly less content, JSON adapted version) still exists on my old GitHub profile (Demon EVD).
*   **Minecraft Server Development:**
    *   I've run and developed for my own Minecraft server (still accessible!).
    *   This involved writing core modifications (Java), custom world and structure generation, and creating KubeJS add-ons for new entities, recipes, etc.
    *   Initially self-hosted, I later migrated to `Bisquit.host` to handle the server load.
*   **Scrap Mechanic:**
    *   Contributed to and developed mods focusing on numerical logic, custom gates, and blocks with new mathematical functions, accelerometers, etc.

---

## 🌱 Current Endeavors & Learning Path

I'm a firm believer in continuous learning and improvement. Here's what's currently on my radar:

*   ⚛️ **Deep Dive into React:** I am intensely focused on mastering React, working through official documentation and building practical projects to solidify my understanding of its patterns, ecosystem, and best practices.
*   🐙 **Mastering Git & GitHub:** While I've used Git, I'm dedicated to achieving a deeper proficiency in its advanced features and collaborative workflows on GitHub. I believe this is crucial for effective teamwork and open-source participation.
*   💡 **Project Revival & Development:**
    *   **Fenix.AI:** Collaborating with Teresh to enhance and potentially re-launch this neural network library.
    *   **Tamagotchi Bot:** Breathing new life into a sophisticated Tamagotchi-style bot project that has been on the back burner but holds a lot of potential.
*   🧩 **Exploring WebAssembly (Wasm):** Investigating how Wasm can be integrated into web projects for performance-critical tasks.

**My Commitment to Ethical & Effective Coding:**
*   I actively **avoid using AI code generators** like ChatGPT or GitHub Copilot for writing primary application logic.
*   My use of LLMs is **strictly limited to looking up documentation, understanding complex theoretical concepts, or exploring alternative approaches** – essentially, as a highly advanced search and learning tool.

---

## 🎯 What I'm Seeking & How I Like to Collaborate

I'm eager to apply my skills and continue growing in a professional environment.

*   **Opportunities:** I am actively **seeking an interesting part-time role or summer internship** in IT or software development. I want to contribute to meaningful projects, gain new experiences, and learn from seasoned developers.
*   **Collaboration:** I'm open to collaborating on innovative projects. If you have an idea where my skills in JavaScript, bot development, game modding, or even my budding React knowledge could be beneficial, I'd love to hear about it!
*   **Growth Areas for Collaboration:**
    *   I'm keen to work with teams or individuals who can offer **mentorship in performance optimization** and advanced architectural patterns.
    *   I enjoy tackling **complex problems** and thrive in environments that encourage deep thinking and creative solutions.
    *   I value working with **documentation-focused teams** who prioritize clarity and maintainability.
*   **Visibility & Community:** I aim to make my projects more visible and connect with a broader community of developers and innovators.

---

## 📫 Let's Connect!

I'm always open to interesting conversations and potential collaborations.
*   **GitHub:** You're already here! Feel free to explore my repositories or open an Issue.
*   **Email:** You can reach me at `megrm.dir@gmail.com` for professional inquiries.
*   **Telegram:** [@TetraJoker]

---

*"Good code needs human hands and stubborn minds."*
*- Tetra, 2025*

Thanks for taking the time to read about my journey. I look forward to connecting!
