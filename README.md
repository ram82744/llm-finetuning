# llm-finetuning
Fine Tuning Large language models like Llama2, MistralAI, Zephyr using PEFT, TRL, GPTQ and accelerate libraries.

Fine-tuning in the context of LLMs typically results in the transformation of a general-purpose base model (e.g. GPT-3) into a specialized model for a specific use case (e.g. ChatGPT). The main advantage of this approach is that models can perform better while requiring (far) fewer manually labeled examples than models that rely solely on supervised training. While strictly self-supervised base models can perform admirably on a wide range of tasks with the assistance of prompt engineering [2], they are still word predictors and may generate completions that are not entirely helpful or accurate.

Large language models (LLMs) have unquestionably altered how we interact with information. They do, however, have some limitations in terms of what we can ask of them. Base LLMs (for example, Llama-2-70b, gpt-4) are only aware of the information they've been trained on and will fall short when we ask them to know more. LLM applications based on retrieval augmented generation (RAG) address this specific issue and extend the utility of LLMs to custom specific data sources. In this series of python notebooks i've tried to use the latest llms to build chat applications for general purpose usage.


