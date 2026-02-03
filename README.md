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

The Basics of Blockchain Technology

Blockchain technology is a decentralized digital system used to record transactions securely, transparently, and immutably. Originally developed as the underlying technology for Bitcoin, blockchain has evolved into a general-purpose technology with applications across finance, healthcare, supply chains, governance, and more. At its core, blockchain functions as a distributed ledger maintained by a network of participants rather than a central authority.

A blockchain consists of a series of data units called blocks, which are linked together in chronological order. Each block contains a list of transactions, a timestamp, and a cryptographic hash of the previous block. This hash linkage creates a secure chain structure; altering the data in one block would require changing all subsequent blocks, making unauthorized modifications extremely difficult. This property gives blockchain its key feature of immutability.

One of the defining characteristics of blockchain technology is decentralization. Instead of relying on a single centralized server or institution, the ledger is distributed across multiple nodes in a peer-to-peer network. Every participant maintains a copy of the blockchain, ensuring redundancy and resilience. Decentralization reduces the risk of single points of failure and increases trust among participants who may not know or trust each other.

To ensure that all nodes agree on the current state of the blockchain, consensus mechanisms are used. Consensus mechanisms are protocols that allow distributed nodes to validate and agree on transactions. Common mechanisms include Proof of Work (PoW), where nodes solve complex mathematical problems to add new blocks, and Proof of Stake (PoS), where nodes validate transactions based on the amount of cryptocurrency they hold. These mechanisms prevent double-spending and malicious attacks on the network.

Cryptography plays a crucial role in blockchain security. Transactions are digitally signed using public-key cryptography, ensuring authenticity and non-repudiation. Hash functions are used to generate unique digital fingerprints for blocks, providing data integrity. Together, these cryptographic techniques ensure that blockchain systems are secure, transparent, and tamper-resistant.
<img width="197" height="256" alt="image" src="https://github.com/user-attachments/assets/4674af63-1933-4a49-812d-4def3794b99e" />

Beyond cryptocurrencies, blockchain supports programmable logic through smart contracts. Smart contracts are self-executing programs stored on the blockchain that automatically enforce predefined rules and conditions. They eliminate the need for intermediaries and enable automated processes such as asset transfers, voting systems, and supply chain tracking.

Despite its advantages, blockchain technology also faces challenges. Scalability, high energy consumption (especially in Proof of Work systems), regulatory uncertainty, and integration with existing systems remain significant concerns. Researchers and developers are actively working on solutions such as layer-2 scaling, energy-efficient consensus models, and interoperability frameworks.

In conclusion, blockchain technology provides a novel way to manage data and trust in decentralized environments. By combining distributed systems, cryptography, and consensus protocols, blockchain enables secure and transparent digital transactions without centralized control. As the technology continues to mature, it is expected to play a key role in shaping future digital infrastructures.

## Result

Platform: ChatGPT
Prompting Technique: Role-based + Structured prompting

This combination provided the most accurate, coherent, and student-friendly summary, making it ideal for an educational content curation platform focused on undergraduate learners.


