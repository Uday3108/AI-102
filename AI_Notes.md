Introduction:

The growth in the use of artificial intelligence (AI) in general, and generative AI in particular means that developers are increasingly required to create comprehensive AI solutions. These solutions need to combine machine learning models, AI services, prompt engineering solutions, and custom code.

What is AI?

The term "Artificial Intelligence" (AI) covers a wide range of software capabilities that enable applications to exhibit human-like behavior.

Common AI capabilities that developers can integrate into a software application include:

Generative AI: 
    The ability to generate original responses to natural language prompts. For example, software for a real estate business might be used to automatically generate property descriptions and advertising copy for a property listing.

Agents:
    Generative AI applications that can respond to user input or assess situations autonomously, and take appropriate actions. For example, an "executive assistant" agent could provide details about the location of a meeting on your calendar, or even attach a map or automate the booking of a taxi or rideshare service to help you get there.

Computer vision:
    The ability to accept, interpret, and process visual input from images, videos, and live camera streams. For example, an automated checkout in a grocery store might use computer vision to identify which products a customer has in their shopping basket, eliminating the need to scan a barcode or manually enter the product and quantity.

Speech:
    The ability to recognize and synthesize speech. For example, a digital assistant might enable users to ask questions or provide audible instructions by speaking into a microphone, and generate spoken output to provide answers or confirmations.

Natural language processing:
    The ability to process natural language in written or spoken form, analyze it, identify key points, and generate summaries or categorizations. For example, a marketing application might analyze social media messages that mention a particular company, translate them to a specific language, and categorize them as positive or negative based on sentiment analysis.

Information extraction:
    The ability to use computer vision, speech, and natural language processing to extract key information from documents, forms, images, recordings, and other kinds of content. For example, an automated expense claims processing application might extract purchase dates, individual line item details, and total costs from a scanned receipt.

Decision support:
    The ability to use historic data and learned correlations to make predictions that support business decision making. For example, analyzing demographic and economic factors in a city to predict real estate market trends that inform property pricing decisions.


Azure AI services:

Azure OpenAI:
    Azure OpenAI in Foundry Models provides access to OpenAI generative AI models including the GPT family of large and small language models and DALL-E image-generation models within a scalable and securable cloud service on Azure

Azure AI Vision:
    The Azure AI Vision service provides a set of models and APIs that you can use to implement common computer vision functionality in an application. With the AI Vision service, you can detect common objects in images, generate captions, descriptions, and tags based on image contents, and read text in images.

Azure AI Speech:
    The Azure AI Speech service provides APIs that you can use to implement text to speech and speech to text transformation, as well as specialized speech-based capabilities like speaker recognition and translation.

Azure AI Language:
    The Azure AI Language service provides models and APIs that you can use to analyze natural language text and perform tasks such as entity extraction, sentiment analysis, and summarization. The AI Language service also provides functionality to help you build conversational language models and question answering solutions.

Azure AI Foundry Content Safety:
    Azure AI Foundry Content Safety provides developers with access to advanced algorithms for processing images and text and flagging content that is potentially offensive, risky, or otherwise undesirable.

Azure AI Translator:
    The Azure AI Translator service uses state-of-the-art language models to translate text between a large number of languages.

Azure AI Face:
    The Azure AI Face service is a specialist computer vision implementation that can detect, analyze, and recognize human faces. Because of the potential risks associated with personal identification and misuse of this capability, access to some features of the AI Face service are restricted to approved customers.

Azure AI Custom Vision:
    The Azure AI Custom Vision service enables you to train and use custom computer vision models for image classification and object detection.

Azure AI Document Intelligence:
    With Azure AI Document Intelligence, you can use pre-built or custom models to extract fields from complex documents such as invoices, receipts, and forms.

Azure AI Content Understanding:
    The Azure AI Content Understanding service provides multi-modal content analysis capabilities that enable you to build models to extract data from forms and documents, images, videos, and audio streams.

Azure AI Search:
    The Azure AI Search service uses a pipeline of AI skills based on other Azure AI Services and custom code to extract information from content and create a searchable index. AI Search is commonly used to create vector indexes for data that can then be used to ground prompts submitted to generative AI language models, such as those provided in Azure OpenAI.

Azure AI services:
    The Azure AI Services resource type includes the following services, making them available from a single endpoint:
        Azure AI Speech
        Azure AI Language
        Azure AI Translator
        Azure AI Vision
        Azure AI Face
        Azure AI Custom Vision
        Azure AI Document Intelligence

Azure AI Foundry:
    The Azure AI Foundry resource type includes the following services, and supports working with them through an Azure AI Foundry project*:
        Azure OpenAI
        Azure AI Speech
        Azure AI Language
        Azure AI Foundry Content Safety
        Azure AI Translator
        Azure AI Vision
        Azure AI Face
        Azure AI Document Intelligence
        Azure AI Content Understanding

Azure AI Foundry

    Azure AI Foundry is a comprehensive platform on Microsoft Azure for building, managing, and deploying AI solutions. While individual Azure AI services can be used separately, Azure AI Foundry streamlines project organization, resource management, and AI development, making it the preferred approach for most AI projects.

It includes:

    Azure AI Foundry Portal – a visual, web-based interface for managing AI projects.
    Azure AI Foundry SDK – tools for programmatic AI solution development.

Projects in Azure AI Foundry come in two types:

Foundry Projects:
    Linked to an Azure AI Foundry resource.
    Support OpenAI models, Agent Service, Azure AI services, and responsible AI tools.
    Best suited for developing generative AI apps and chat agents with centralized management and minimal overhead.

Hub-Based Projects:

    Linked to an Azure AI Hub resource.
    Include managed compute, Prompt Flow development, Azure Storage, and Key Vault integration.
    Ideal for advanced AI development, such as model fine-tuning or collaborative work involving data scientists and ML engineers.
    Accessible via both Azure AI Foundry Portal and Azure Machine Learning Portal.        