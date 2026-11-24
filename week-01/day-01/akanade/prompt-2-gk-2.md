# Prompt (General Knowledge): 

Explain the differences between Artificial Intelligence (AI), Machine Learning (ML), Deep Learning (DL), Generative AI, and Agentic AI.

For each concept:
1. Provide a simple definition.
2. Explain how it works at a high level.
3. Give a real-world example.
4. Explain how it relates to the other concepts.

Present the answer in a structured format with a comparison table at the end. Use simple language suitable for someone with a technical background but who is new to these concepts.

# Observations
- The platform informs the user when the requested model is unavailable. However, the response was still generated using a different model. This behavior indicates that the platform may have a fallback mechanism for handling model unavailability.
- The model generated the response in the expected format, including explanations and a comparison table.
- The response was citation-backed, with links provided to support the information presented.
- The response was well-structured and covered the requested concepts.

# Additional Experiment: Model Availability
- Attempted to generate the response using the Groq model.
- The response was generated using DeepSeek V4.1 Flash (Standard).
- At the end of the response, the platform displayed a notification stating that the selected Groq model was unavailable.

# Model Details
- Model: DeepSeek V4.1 Flash
- Mode: Standard
- Latency: 21 seconds

# Answer : 

The short version

Four of these terms nest inside each other like Russian dolls — AI ⊃ ML ⊃ DL ⊃ Generative AI. Agentic AI is different: it describes behaviour (acting on its own toward a goal) rather than a way of building a system, which is why it cuts across the others aigovernance.study.

1. Artificial Intelligence (AI)

Definition: The field of building computer systems that do tasks we associate with human thinking — recognising patterns, understanding language, making predictions, creating content sts.doit.wisc.edu.
How it works: An umbrella term covering any technique that makes computers act smartly, including hand-written if-then rules with no learning at all. AI doesn't think like you do; it learns or encodes patterns and applies them to new situations sts.doit.wisc.edu.
Real-world example: Spam filters, map traffic prediction, face unlock on your phone, search ranking sts.doit.wisc.edu.
Relation to the rest: The outermost box. ML, DL, generative and agentic AI are all subsets or flavours of it ai.gov.uk.
2. Machine Learning (ML)

Definition: AI that learns patterns from data instead of following fixed rules a programmer wrote by hand aigovernance.study.
How it works: You supply features (the clues, e.g. "says 'free prize'?", "number of links") and labels (the answer, e.g. spam / not spam). The model learns the mapping from training data, and its accuracy is checked against held-back test data. It improves with experience rather than being reprogrammed sts.doit.wisc.edu. Models split into discriminative (tell categories apart) and generative (learn what the data looks like well enough to produce more of it) aigovernance.study.
Real-world example: A bank's loan-default model that gets better as repayment histories accumulate — AI? yes. ML? yes. Generative? no. Agentic? no aigovernance.study.
Relation to the rest: A type of AI. DL is a type of ML; generative AI is built on DL. Traditional ML suits simpler tasks and small data; DL handles complex, high-volume problems ai.gov.uk.
3. Deep Learning (DL)

Definition: ML built on neural networks with many layers, loosely inspired by the brain aigovernance.study.
How it works: Each unit takes numbers in, multiplies each by a weight, sums them, and passes the total through an activation function (the simplest such unit is a perceptron). Training is a loop: predict, measure the error, nudge the weights, repeat — using gradient descent and backpropagation, millions of times. In an image model, early layers spot edges, middle layers find shapes and textures, later layers recognise whole objects sts.doit.wisc.edu. It's trained on GPUs because they run thousands of parallel calculations aigovernance.study.
Real-world example: Face recognition, speech understanding, image classification ai.gov.uk.
Relation to the rest: A subset of ML. It's particularly good with unstructured data — photos, audio, free text — which older methods needed a human to characterise aigovernance.study. It's the engine underneath almost all generative AI.
4. Generative AI

Definition: Deep learning used to create new content — text, images, video, audio or code aigovernance.study.
How it works: Probabilistic models trained on large, curated datasets learn the underlying patterns and structure of the data, then sample from what they learned to produce new output consistent with it — resembling the training data without copying it ai.gov.uk. Having learned what cats look like, a model can produce a cat picture that never existed aigovernance.study.
Real-world example: ChatGPT (OpenAI), Gemini (Google), Copilot (Microsoft), Claude (Anthropic), Firefly (Adobe) aigovernance.study.
Relation to the rest: A subset of DL, hence of ML and AI. It predicts and produces rather than merely classifying — that's the line between it and a spam classifier aigovernance.study.
5. Agentic AI

Definition: AI that works toward a goal with some independence — figuring out the steps, making decisions, using tools, and adjusting when things change — rather than waiting to be told each step educators.ailiteracyforall.ca.
How it works: An integrated control loop of perception, reasoning, planning and action. Given an objective, the agent breaks it into sub-tasks, executes them, and adapts dynamically — often improving through reinforcement learning. It typically relies on language models augmented with planners, memory systems and tool interfaces, and operates within set boundaries with human oversight to review or step in ai.gov.uk. It is not complete autonomy educators.ailiteracyforall.ca.
Real-world example: A gen AI app tells you the best time to climb Mt. Everest around your work schedule; an agent goes further and books the flight and reservation through an online travel service ibm.com.
Relation to the rest: Overlaps the others but isn't nested in them — it's a behaviour, not an architecture. Most of today's agents are built on generative models, but an agent doesn't have to be generative: a reinforcement-learning system that acts without creating content still counts aigovernance.study. More autonomy means fewer human checkpoints, which is why it's treated as a separate governance question aigovernance.study.
Comparison table

AI	ML	DL	Generative AI	Agentic AI
What it is	Any technique making computers act smartly	AI that learns from data instead of fixed rules	ML with many-layered neural networks	DL that creates new text/images/audio/code	AI that pursues goals with limited oversight
Needs training data?	Not necessarily	Yes	Yes, large amounts	Yes, large curated sets	Inherits from its base model; learns by reinforcement
Core mechanism	Rules or learning	Features → labels, fit on training data	Weights, activation functions, gradient descent, GPUs	Learn data structure, sample new output	Perceive → reason → plan → act loop, with tools and memory
Typical example	Spam filter, face unlock	Loan-default predictor	Face/speech recognition	ChatGPT, Gemini, Claude	Agent that books your flights end-to-end
Creates content?	Sometimes	No — it predicts/classifies	No, it's the machinery	Yes	Only if built on a generative model
Acts on its own?	No	No	No	No	Yes, within boundaries
Nesting	Outermost	⊂ AI	⊂ ML	⊂ DL	Overlaps all; defined by behaviour
One test that works on any system: ask in order — Is it AI? Does it improve with experience (ML)? Is it a deep network (DL)? Does it create content (generative)? Does it act on its own (agentic)? aigovernance.study

