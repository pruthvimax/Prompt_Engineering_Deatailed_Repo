Prompt Engineering

Remember how an LLM works; it's a prediction engine. The model take takes sequential texts as an input and then predicts what the following token should be , based on the data it was trained  on. The LLM is a operationalized to do this over and over again, adding the previously predicted token to the end of the sequential text for predicting the following token . The next token prediction is based on the relationship between what's the previous token and what the LLM  has seen during its training.

When you write a prompt, you are attempting to set up the LLM to predict the right sequence of tokens.Prompt engineering is the process of designing high-quality prompts that guide LLMs to produce accurate outputs.
This process involves tinkering to find the best prompt,optimizing prompt length, and evaluating a prompt's writing style and structure in relation to the task. in the context of natural language processing and LLMs, a prompt is an input provide to the model to generate a response or prediction.

These prompts can be used to achieve various kinds of understanding and generation
tasks such as text summarization, information extraction, question and answering, text
classification, language or code translation, code generation, and code documentation
or reasoning.

Please feel free to refer to Google’s prompting guides2,3 with simple and effective
prompting examples.

When prompt engineering, you will start by choosing a model. Prompts might need to be
optimized for your specific model, regardless of whether you use Gemini language models in
Vertex AI, GPT, Claude, or an open source model like Gemma or LLaMA.

Besides the prompt, you will also need to tinker with the various configurations of a LLM.