### Chemistry assistant
This project focused on the development of a chemistry-focused conversational Telegram bot powered by a fine-tuned version of the TinyLlama-1.1B language model. The base model, TinyLlama/TinyLlama-1.1B-Chat-v1.0, was selected for its balance between performance and computational efficiency, making it suitable for deployment in resource-constrained environments.

The model was fine-tuned using the LoRA (Low-Rank Adaptation) method on the "camel-ai/chemistry" dataset from Hugging Face. This dataset contains structured question–answer pairs covering key topics in chemistry, enabling the model to adapt to domain-specific content and improve the quality of responses within chemistry-related dialogues.

In the final phase, the fine-tuned model was integrated into a Telegram bot using the Telegram Bot API. The bot allows users to interact in natural language and receive real-time answers to questions on general chemistry topics.


