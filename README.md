# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm
tep 1: Select the Topic

Choose a technical article for summarization.

Selected Topic: The Basics of Blockchain Technology

The article includes:

1.Definition of blockchain
2.Decentralized ledger concept
3.Blocks and cryptographic hashing
4.Consensus mechanisms
5.Applications of blockchain
6.Advantages and challenges

Step 2: Choose AI Platforms

The following AI tools were selected for experimentation:

1.ChatGPT
2.Google Gemini
3.Claude AI
4.Microsoft Copilot

Step 3: Prepare Prompting Techniques
Five prompting strategies were used.
A. Basic Prompt
The AI is directly asked to summarize the article.

Example:
Summarize the following article on "The Basics of Blockchain Technology" in simple English for undergraduate students.

B. Role Prompt
The AI is assigned a specific role before generating the summary.

Example:
You are a university professor. Summarize the following article on "The Basics of Blockchain Technology" in simple English for undergraduate students.

C. Context Prompt
Additional background information is provided before the task.

Example:
The summary is intended for undergraduate engineering students who have no prior knowledge of blockchain technology. Summarize the article in clear and easy-to-understand language.

D. Constraint Prompt
Specific rules are given to control the output.

Example:
Summarize the article in less than 100 words using simple English and bullet points. Mention only the key concepts, applications, and challenges.

E. Output Format Prompt
The AI is instructed to generate the summary in a fixed format.

Example:
Summarize the article using the following format:

Title
Definition
Key Concepts
Applications
Advantages
Challenges
Conclusion

Step 4: Generate Responses
The same blockchain article was provided to all AI platforms.

Each prompting strategy was tested individually:
Basic Prompt
Role Prompt
Context Prompt
Constraint Prompt
Output Format Prompt
The generated summaries were collected and analyzed.

Step 5: Organize Results
The responses were compared based on:
Accuracy
Coherence
Simplicity
Speed
User Experience

## Result

## ChatGPT + Basic Prompt

Prompt Used
Summarize the following article on "The Basics of Blockchain Technology" in simple English for undergraduate students.

## Summary: The Basics of Blockchain Technology

Blockchain is a secure digital technology that stores data across many computers instead of one central system. Information is saved in connected blocks, each containing transaction details, a timestamp, and a unique hash, making the data secure and difficult to change.

Before a transaction is added, the network verifies it using consensus methods such as Proof of Work (PoW) or Proof of Stake (PoS). These methods help ensure that only valid transactions are recorded.

Although blockchain is best known for cryptocurrencies like Bitcoin and Ethereum, it is also used in banking, healthcare, supply chain management, digital identity, voting systems, and smart contracts.

The main advantages of blockchain are security, transparency, decentralization, traceability, and reduced reliance on intermediaries. However, it also has challenges, including high energy consumption (especially with PoW), scalability issues, slower transaction speeds, storage needs, and regulatory concerns.

Overall, blockchain is an important emerging technology that provides secure and reliable data sharing and is expected to have a major impact on many industries in the future.

## Evaluation:
1.Accuracy: High
2.Coherence: Excellent
3.Simplicity: Excellent
4.Speed: Very Fast
5.User Experience: Excellent

## Google Gemini + Role Prompt

Prompt Used:
You are a university professor. Summarize the following article on "The Basics of Blockchain Technology" in simple English for undergraduate students.
Summary: The Basics of Blockchain Technology
1. What is Blockchain?
Blockchain is a secure digital system for storing information. Unlike traditional databases controlled by a single central company or server, blockchain is a decentralized ledger. This means a copy of the data is shared across many computers in a network.

Information is organized into blocks. Each block contains:

Transaction details

A timestamp

A cryptographic hash (a unique digital fingerprint)

Blocks are securely linked together in chronological order, forming a continuous "chain."

2. Key Features and Security
Immutable (Unchangeable): Once data is saved in a block, it is almost impossible to alter or delete. To change a single block, an attacker would have to modify that block and every block that comes after it across all computers in the network.

Consensus Mechanisms: Before a new transaction is added to the chain, the network must verify it. Common agreement methods include:

Proof of Work (PoW): Computers solve complex math puzzles to validate data.

Proof of Stake (PoS): Participants (validators) are chosen based on the cryptocurrency they hold and lock up as a guarantee.

3. Real-World Applications
While best known for powering cryptocurrencies like Bitcoin and Ethereum, blockchain has many other practical uses:

Finance & Banking: Secure, direct money transfers.

Healthcare: Safe storage of patient medical records.

Supply Chain: Tracking goods from production to store shelves.

Smart Contracts: Digital agreements that execute automatically when set rules are met.

Other Areas: Digital IDs, secure voting systems, and education.

4. Advantages and Challenges
Benefits:
High security and transparency
Reduced need for middlemen (like banks or intermediaries)
Traceable records that make fraud very difficult

## Drawbacks:
High energy consumption (particularly in networks using Proof of Work)

Slower transaction speeds compared to centralized systems
Large storage requirements and evolving government regulations

## Conclusion
Blockchain is a transformative technology that allows secure, trustworthy, and transparent data sharing without relying on a central authority. As it evolves, it will continue to reshape major global industries.

## Evaluation
1.Accuracy: Excellent
2.Coherence: Excellent
3.Simplicity: Excellent
4.Speed: Fast
5.User Experience: Very Good

## Claude AI + Context Prompt

Prompt Used:
The summary is intended for undergraduate engineering students who have no prior knowledge of blockchain technology. Summarize the following article in clear and easy-to-understand language.
What is Blockchain?

Blockchain is a way of storing digital information across many computers instead of one central server. Everyone in the network keeps an identical copy of the data, which is why it's called a "decentralized ledger."

How It Works

Data is stored in "blocks," each containing transaction details, a timestamp, and a unique code called a cryptographic hash. These blocks are linked together in order, forming a chain — hence the name "blockchain." Because each block depends on the one before it, altering any single block would require changing every block after it on every computer in the network. This makes tampering extremely difficult and keeps the data trustworthy.

Verifying Transactions

Before a new transaction is added, the network must agree it's valid. This is done through "consensus mechanisms," with two common types:

Proof of Work (PoW): Computers compete to solve difficult math problems.
Proof of Stake (PoS): Validators are chosen based on how much cryptocurrency they own and are willing to put up as collateral.

Where It's Used

Blockchain powers cryptocurrencies like Bitcoin and Ethereum, but its uses go much further, including:

Secure banking transactions
Healthcare recordkeeping
Supply chain tracking
Digital identity verification
Voting systems
Smart contracts (agreements that execute automatically when conditions are met)

Pros and Cons

## Advantages:
Transparency, security, decentralization, traceability, and less reliance on middlemen. Since records are permanent, fraud becomes harder to commit.

## Challenges: 
High energy use (especially with PoW), scalability limits, slower transaction speeds, storage demands, and evolving government regulations.

Why It Matters

Blockchain is seen as a major emerging technology because it allows secure, transparent, and reliable data sharing without relying on a single central authority. As the technology matures, it's expected to play a growing role in finance, healthcare, education, and logistics.

## Evaluation
1.Accuracy: Excellent
2.Coherence: Excellent
3.Simplicity: Excellent
4.Speed: Moderate
5.User Experience: Excellent

## Microsoft Copilot + Constraint Prompt

Prompt Used:
Summarize the following article on "The Basics of Blockchain Technology" in less than 100 words using simple English and bullet points. Mention only the key concepts, applications, and challenges.

Blockchain is a digital technology that stores information securely across many computers instead of keeping it in one central location. It is called a decentralized ledger because every participant in the network has a copy of the same data. Information is stored in blocks, and each block contains transaction details, a timestamp, and a unique cryptographic hash. Every new block is linked to the previous one, forming a secure chain of blocks known as a blockchain.
One of the main features of blockchain is that once data is recorded, it is extremely difficult to modify or delete. This is because changing one block would require changing all the following blocks across every computer in the network. Cryptographic hashing helps protect the integrity of the data by generating a unique digital fingerprint for every block.
Blockchain networks use consensus mechanisms to verify transactions before adding them to the ledger. Two popular methods are Proof of Work (PoW), where computers solve complex mathematical problems, and Proof of Stake (PoS), where validators are selected based on the amount of cryptocurrency they own and are willing to stake.
Blockchain technology is widely known for supporting cryptocurrencies such as Bitcoin and Ethereum. However, its applications extend beyond digital currencies. It is used in banking for secure financial transactions, healthcare for maintaining patient records, supply chain management for tracking products, digital identity verification, voting systems, and smart contracts that automatically execute agreements when predefined conditions are met.
The technology offers several advantages, including transparency, security, decentralization, traceability, and reduced dependence on intermediaries. Since every transaction is recorded permanently, fraud becomes more difficult. However, blockchain also has some challenges. Public blockchain networks may consume large amounts of energy, especially those using Proof of Work. Scalability, transaction speed, storage requirements, and government regulations are additional issues that need continuous improvement.
Overall, blockchain is considered one of the most important emerging technologies because it enables secure, transparent, and reliable data sharing across distributed networks. As research and development continue, blockchain is expected to play a significant role in finance, healthcare, education, logistics, and many other industries.

## Evaluation
1.Accuracy: Good
2.Coherence: Good
3.Simplicity: Excellent
4.Speed: Fast
5.User Experience: Good

## ChatGPT + Output Format Prompt

Prompt Used:
Summarize the following article on "The Basics of Blockchain Technology" using the following format: Title Definition,Key Concepts,Applications,Advantages,Challenges,Conclusion

# The Basics of Blockchain Technology

## Definition

Blockchain is a digital technology that securely stores information across multiple computers instead of a single central system. It works as a decentralized ledger where all participants have the same copy of the data.

## Key Concepts

* Data is stored in blocks linked together to form a blockchain.
* Each block contains transaction details, a timestamp, and a unique cryptographic hash.
* Once data is recorded, it is very difficult to change or delete.
* Consensus mechanisms such as **Proof of Work (PoW)** and **Proof of Stake (PoS)** verify transactions before they are added to the blockchain.

## Applications

* Cryptocurrencies (Bitcoin and Ethereum)
* Banking and financial transactions
* Healthcare record management
* Supply chain tracking
* Digital identity verification
* Voting systems
* Smart contracts

## Advantages

* High security
* Transparency
* Decentralization
* Better traceability
* Reduced dependence on intermediaries
* Permanent records help reduce fraud

## Challenges

* High energy consumption, especially with PoW
* Scalability issues
* Slower transaction speed
* Large storage requirements
* Government regulations and legal concerns

## Conclusion

Blockchain is an important emerging technology that provides secure, transparent, and reliable data sharing. With continuous development, it is expected to play a major role in industries such as finance, healthcare, education, logistics, and many others.

Evaluation
1.Accuracy: Excellent
2.Coherence: Excellent
3.Simplicity: Excellent
4.Speed: Very Fast
5.User Experience: Excellent

Comparison Table:
| Platform          | Prompting Technique  | Accuracy  | Coherence | Simplicity | Speed     | User Experience |
| ----------------- | -------------------- | --------- | --------- | ---------- | --------- | --------------- |
| ChatGPT           | Basic Prompt         | High      | Excellent | Excellent  | Very Fast | Excellent       |
| Google Gemini     | Role Prompt          | Excellent | Excellent | Excellent  | Fast      | Very Good       |
| Claude AI         | Context Prompt       | Excellent | Excellent | Excellent  | Moderate  | Excellent       |
| Microsoft Copilot | Constraint Prompt    | Good      | Good      | Excellent  | Fast      | Good            |
| ChatGPT           | Output Format Prompt | Excellent | Excellent | Excellent  | Very Fast | Excellent       |

## Final Result

Different prompting techniques were tested across multiple AI platforms for summarizing a technical article on "The Basics of Blockchain Technology."

ChatGPT with the Basic Prompt generated a simple and easy-to-understand summary.
Google Gemini with the Role Prompt produced a structured and academic-style summary.
Claude AI with the Context Prompt generated the most coherent and detailed summary suitable for beginners.
Microsoft Copilot with the Constraint Prompt produced a concise summary within the specified limits.
ChatGPT with the Output Format Prompt generated the most organized summary with clear headings.

Overall, ChatGPT with the Output Format Prompt provided the best balance of accuracy, organization, readability, and user experience.







## Result


