---
title: "Generative AI and Large Language Models (LLMs)"
impact: CRITICAL
impactDescription: "Core MBA framework, foundational to domain"
tags: frameworks, generative, language, large, models, quantitative, technology
---

**Generative AI** creates new content: text, images, code, audio. Works by predicting the next token (word/image patch) based on previous tokens, iterating to generate coherent output.

**LLMs** are trained on vast text corpora to predict the next word. Applications:

- **Text generation**: Writing emails, reports, creative content
- **Question answering**: Answering user questions based on provided documents
- **Summarization**: Condensing long text
- **Code generation**: Writing or debugging code
- **Translation and paraphrasing**

**Transformer Architecture Components**:

- **Attention Mechanism**: Allows model to focus on relevant parts of input. Each word attends to other words, weighting their importance. Captures long-range dependencies and enables parallel processing.
- **Multi-Head Attention**: Multiple attention mechanisms running in parallel, each focusing on different aspects, enabling learning multiple types of relationships.
- **Feed-Forward Network**: Dense layers between attention mechanisms applying non-linear transformations.
- **Positional Encoding**: Adds position information to embeddings, essential since attention mechanism is order-agnostic.

**Stacked Layers**: Transformers stack many identical blocks. Early layers learn character-level patterns and grammar. Middle layers learn semantic relationships and abstract concepts. Later layers learn task-specific patterns and reasoning. Depth enables learning increasingly abstract patterns.

**Pre-Training and Fine-Tuning**:

- **Pre-training** uses self-supervised learning: given previous tokens, predict next token. Weights updated via backpropagation across billions of parameters. Training data is enormous and diverse (Internet text, Wikipedia, books, articles, code).
- **Emergent Capabilities** arise with scale: small models can't do math or coding; medium models handle simple tasks; large models reason, write code, explain concepts. Scaling laws show predictable improvements with more data/parameters.
- **Fine-tuning**: Taking a pre-trained model and training further on specialized data. A general LLM fine-tuned on legal documents becomes better at legal analysis. Requires less data and compute than training from scratch.
- **Instruction Fine-Tuning**: Train on examples of task + correct output, converting model to instruction-following assistant.
- **Reinforcement Learning from Human Feedback (RLHF)**: Humans rank outputs by quality; train reward model to predict quality; update model to maximize reward. Enables models like ChatGPT aligned with human values.

**Major LLM Models**:

- **GPT Series (OpenAI)**: GPT-4 (8+ trillion parameters, text and image), GPT-3.5 (175 billion parameters, cost-effective). Decoder-only architecture; strong at generation and storytelling.
- **BERT (Google)**: Bidirectional; attends to context before and after. Encoder-only; excellent for classification and understanding tasks.
- **Llama (Meta)**: Open-source, commercially usable, competitive with closed models. Enables fine-tuning without API dependency.

**Prompt Engineering**: The art of writing prompts to get desired outputs. Small wording changes yield large output differences. Techniques:

- **Specificity**: Be precise about desired output format and constraints.
- **Few-shot examples**: Provide input-output examples; models learn patterns without retraining.
- **Chain-of-thought**: Ask model to reason step-by-step for complex problems.
- **System prompts**: Set behavior without examples ("You are a customer service representative. Be friendly and professional.").
- **Structured output**: Specify desired format (JSON, bullet points) for downstream integration.

**Limitations and Risks**:

- **Hallucination**: LLMs generate plausible-sounding but false information. They've learned statistical patterns, not true facts. For critical applications (medical advice, legal interpretation), require human review.
- **Bias**: Training data reflects historical biases. Models perpetuate discrimination in hiring, lending, criminal justice. Audit for bias; diversify training data; use human oversight.
- **Token limits**: Context window constrains how much information LLMs can process at once.
- **Cost**: LLM API calls expensive at scale.

**Retrieval-Augmented Generation (RAG)**: Extend LLM knowledge without fine-tuning. Instead of LLM generating from training data (risk of hallucination), retrieve relevant documents and let LLM cite them.

- Store documents in searchable database (embeddings database)
- User asks question → retrieve relevant documents
- Pass documents to LLM along with question
- Model answers based on retrieved context, citing sources
- Enables current information, domain expertise, fact grounding, transparency
- Reduces hallucinations by providing sources and grounding answers
- Internal knowledge base Q&A, customer support with company-specific info, research assistants with academic literature, legal document analysis

**Example**: Customer support agent. Traditional: LLM generates answer from training data (might be wrong). RAG: Retrieve company's return policy, LLM answers based on actual policy (accurate).
