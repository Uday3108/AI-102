Introduction:
AI and generative AI require combined solutions: models, AI services, prompt engineering, and custom code.
What is AI? / Common capabilities
Generative AI: create text/images from prompts (e.g., property descriptions).
Agents: autonomous apps that act on inputs (e.g., assistant booking rides).
Computer Vision: interpret images/video (e.g., automated checkout).
Speech: speech-to-text and text-to-speech, speaker recognition, translation.
Natural Language Processing: analysis, extraction, summarization, sentiment.
Information Extraction: combine vision/speech/NLP to extract structured data.
Decision Support: predictions from historical data to aid decisions.
Azure AI services (key services & brief)
Azure OpenAI: access to GPT family and DALL·E via Foundry models.
Azure AI Vision: object detection, captions, OCR.
Azure AI Speech: TTS/STT, speaker recognition, translation.
Azure AI Language: entity extraction, sentiment, summarization, conversational QA.
Azure AI Foundry Content Safety: flag offensive/risky text and images.
Azure AI Translator: multilingual text translation.
Azure AI Face: face detection/recognition (restricted access).
Azure AI Custom Vision: train custom image classifiers/detectors.
Azure AI Document Intelligence: extract fields from invoices/receipts/forms.
Azure AI Content Understanding: multimodal extraction from images/video/audio.
Azure AI Search: AI skill pipelines and vector indexes to ground generative models.
Consolidated resource types
Azure AI Services resource: groups Speech, Language, Translator, Vision, Face, Custom Vision, Document Intelligence under one endpoint.
Azure AI Foundry resource: includes OpenAI plus Speech, Language, Content Safety, Translator, Vision, Face, Document Intelligence, Content Understanding.
Azure AI Foundry (platform)
Purpose: portal + SDK for building, managing, and deploying AI projects; recommended for most solutions.
Benefits: project organization, centralized resource management, tooling for evaluation and responsible AI.
Project types in Foundry
Foundry Projects:
Linked to an Azure AI Foundry resource.
Support Foundry/OpenAI models, Agent Service, Azure AI services, responsible AI tooling.
Suited for generative chat apps and agents with minimal overhead.
Hub-Based Projects:
Linked to an Azure AI Hub resource.
Add managed compute, Prompt Flow support, connected Storage and Key Vault.
Suited for advanced scenarios (fine-tuning, Prompt Flow, collaborative ML/data-science).