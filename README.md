# NL to FOL Translation

## Overview
First-Order Logic (FOL), also known as predicate logic, extends propositional logic by allowing the use of quantifiers and predicates, which can express statements about objects and their relationships.

## Importance of Translating Natural Language (NL) to First-Order Logic (FOL)

Translating NL to FOL has significant importance in various fields due to the following reasons:

### Formal Reasoning
Translating NL to FOL allows the use of formal reasoning and logical proofs. FOL provides a rigorous framework for deducing new information from existing knowledge.

### Automated Theorem Proving
FOL is the foundation for many automated theorem provers. Translating NL statements into FOL enables machines to automatically prove or disprove logical statements.

### Artificial Intelligence (AI) and Natural Language Processing (NLP)
Understanding and processing natural language using formal logic is crucial for developing intelligent systems that can understand, reason, and interact using human language.

### Knowledge Representation
FOL is used to represent and reason about knowledge in AI systems. Translating NL descriptions of knowledge into FOL allows for the precise encoding of information.

## Challenges

### Ambiguity in Natural Language
NL is often ambiguous, and different interpretations can lead to different FOL translations. Disambiguating NL sentences is a significant challenge.

### Complexity of Logical Expressions
Natural language can express very complex ideas, and translating these accurately into FOL can result in very complex logical expressions.

### Domain-Specific Knowledge
Accurate translation often requires domain-specific knowledge and context to ensure the correct meaning is captured in the FOL representation.

## Using BART for NL to FOL Translation

### Overview of BART
BART (Bidirectional and Auto-Regressive Transformers) is a powerful sequence-to-sequence model designed by Facebook AI Research (FAIR). It combines the strengths of bidirectional and autoregressive transformers, making it highly effective for a range of text generation tasks, including translation, summarization, and text generation.

### Why BART is a Good Choice for NL to FOL Translation

1. **Sequence-to-Sequence Framework:**
   Translating NL to FOL is a sequence-to-sequence task where an input sequence (NL) needs to be transformed into an output sequence (FOL). BART is designed specifically for such tasks, making it an appropriate model choice.

2. **Contextual Understanding:**
   The bidirectional encoder of BART allows it to grasp the full context of the NL input, which is crucial for accurately interpreting the semantics of natural language sentences and converting them into logical formulas.

## Execution 
In this project Finetuning is done to the BART model with the yuan-yang/MALLS-v0 dataset from Hugging Face.
https://huggingface.co/datasets/yuan-yang/MALLS-v0
