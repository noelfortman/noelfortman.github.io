## SmartSnip: Learning with AI-Powered Dynamic Flashcards

Have you ever spent hours creating flashcards only to realize you're memorizing the cards rather than truly understanding the material? Or found yourself constantly switching between tabs, copying important information into your notes app? If so, you're not alone.

That's why I built this app for my own AWS certification study. SmartSnip is a Chrome extension that transforms how you capture, process, and retain information from the web. With just a right-click, it converts any selected text into intelligently crafted flashcards, using advanced AI to ensure you're testing your understanding, not just memorization skills.

Note that this app is intended for showcase purposes only - to show the power of applications you can build with AWS AI Technology like Amazon Bedrock.

### How does it work?

* Select text on any webpage that contains information you want to remember
* Right-click and choose "Send to SmartSnip"
* Continue browsing while AI processes your selection
* Review generated flashcards later when you're ready to study

<img width="422" alt="Screenshot 2025-05-20 at 9 01 48 AM" src="https://github.com/user-attachments/assets/3c2bd518-05dc-460b-abae-1efb4c500633" />

Behind the scenes, SmartSnip leverages Amazon Bedrock's foundation models to transform raw content into effective learning materials. The extension doesn't just copy your text - it tries to understand it, extract key concepts, and formulates questions that test true comprehension.

### How does it help me learn?

Each time you review a card, the AI can subtly rephrase questions and answers, preventing the common pitfall of memorizing specific wording rather than grasping concepts.

<img width="1584" alt="Screenshot 2025-05-20 at 9 02 05 AM" src="https://github.com/user-attachments/assets/a2ace54f-bbf5-410b-8c5e-a2ae321a4c61" />

This approach aligns with cognitive science research showing that:
* Information presented in slightly different contexts enhances long-term retention
* Testing yourself on knowledge is more effective than passive review
* Spaced repetition with varied questioning leads to deeper understanding

<img width="1584" alt="Screenshot 2025-05-20 at 9 02 17 AM" src="https://github.com/user-attachments/assets/ccfe06b6-da6d-4218-9ff6-8e624fbb08f0" />
<img width="1584" alt="Screenshot 2025-05-20 at 9 02 24 AM" src="https://github.com/user-attachments/assets/e5e19ec3-2821-4db7-9998-068a5236652a" />

### What are the technical details?

SmartSnip harnesses the power of Amazon Bedrock's large language models to:

* Extract essential information from complex content
* Generate questions that target core concepts rather than superficial details
* Provide clear, concise answers that reinforce understanding
* Automatically determine the appropriate difficulty level based on content

The extension uses Nova Pro to process your snippets instantly, without sending sensitive data to third-party servers. Your knowledge base stays private and secure while benefiting from cutting-edge AI. Your knowledge base is stored locally and is only interacted with through the chrome extension.

*What you learn, stays with you.*

