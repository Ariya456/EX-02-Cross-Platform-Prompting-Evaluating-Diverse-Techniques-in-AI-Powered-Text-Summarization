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
With platforms confirmed—ChatGPT for the structured, student-oriented summary and Gemini for the concise, list-based one—here's a deeper breakdown. I evaluate based on your criteria, scoring each (1-10) with evidence from the texts, then tally for an overall verdict. This highlights how prompting techniques (ChatGPT's "clear, student-friendly summary of a 500-word article" vs. Gemini's casual "demystify... concise summary") shaped outputs.

Accuracy (ChatGPT: 9.5 | Gemini: 8.0)
Accuracy measures factual completeness and precision without myths or omissions.
ChatGPT strengths: Nails all essentials—decentralization, block structure (transactions + timestamp + hash), consensus (PoW/PoS details), cryptography (public/private keys), smart contracts, applications (supply chain, healthcare), and challenges (scalability, energy). No fluff; cites Bitcoin/Ethereum accurately.
Gemini strengths: Covers structure (data/hash/previous hash), immutability, consensus basics correctly.
Gemini weaknesses: Omits smart contracts, cryptography details, real-world apps beyond "supply chains to voting," and challenges. PoS simplified to "coins they hold" (ignores staking nuances).

Why ChatGPT wins: Broader, balanced scope mirrors a "technical article," avoiding incomplete primers.

Coherence (ChatGPT: 9.0 | Gemini: 7.5)
Coherence assesses logical flow, transitions, and unified narrative.
ChatGPT strengths: Paragraph-by-paragraph build: intro → structure → decentralization → consensus → cryptography → smart contracts → apps → conclusion. Phrases like "Another essential component" create seamless links; reads like a cohesive essay.
Gemini strengths: Headers ("What is Blockchain?", "The Structure") organize well; metaphor ("shared digital spreadsheet") ties ideas.
Gemini weaknesses: Abrupt shifts (e.g., from security to "Why It Matters"); lists feel fragmented, like notes vs. story.

Why ChatGPT wins: Narrative arc fosters better retention, ideal for student learning.

Simplicity (ChatGPT: 8.5 | Gemini: 8.5)
Simplicity evaluates plain language, analogies, and accessibility for non-experts.
ChatGPT strengths: Everyday terms ("chain of blocks," "digital fingerprint" via hash explanation); avoids jargon overload while defining terms inline.
Gemini strengths: Vivid metaphors ("no boss," "glue that creates the chain"); short sentences/lists for quick grasp.
Shared traits: Both shun equations/code; target beginners.

Tie: ChatGPT slightly more formal (student-friendly), Gemini punchier—both excel.

Speed (ChatGPT: 7.0 | Gemini: 9.5)
Speed gauges readability time and scanability (word count, formatting).
ChatGPT strengths: ~350 words; dense but efficient (2-min read).
ChatGPT weaknesses: Prose requires linear reading.
Gemini strengths: ~250 words; bullets/headers allow 1-min skim; numbered lists prioritize key facts.

Why Gemini wins: Format suits mobile/fast-paced users; "Key Takeaway" speeds closure.

User Experience (ChatGPT: 9.0 | Gemini: 8.0)
User experience covers engagement, tone, visuals, and follow-ups.
ChatGPT strengths: Friendly/professional tone; explicit options ("Make it shorter... bullet points or slides") empower users. Feels tailored (e.g., "exam-ready/UPSC").
Gemini strengths: Conversational hook ("demystify... misunderstood"); offers diagram—interactive spark.
Gemini weaknesses: Fewer customizations; hype-y intro may distract.

Why ChatGPT wins: Proactive, versatile extensions enhance satisfaction/utility.

## Result
Conclusion: ChatGPT Takes the Crown
ChatGPT's structured, student-friendly summary outperforms Gemini's concise primer across accuracy, coherence, and user experience, earning a slight edge (43/50 vs. 41.5/50). Its comprehensive coverage, logical flow, and customization options make it the best for solid, educational blockchain overviews—ideal for students or deep learners. Gemini excels in speed and engagement for quick hits but sacrifices depth. Ultimately, ChatGPT + precise prompting yields the top combination for balanced, high-quality summaries on technical topics.




