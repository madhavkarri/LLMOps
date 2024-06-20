# LLMOps

- Go through the LLMOps pipeline of pre-processing training data for supervised instruction tuning, and adapt a supervised tuning pipeline to train and deploy a custom LLM. 
- Useful in creating an LLM workflow for specific application. For example, creating a question-answer chatbot tailored to answer Python coding questions.
- Go through key steps of creating the LLMOps pipeline:
  * Retrieve and transform training data for supervised fine-tuning of an LLM.
  * Version the data and tuned models to track your tuning experiments. 
  * Configure an open-source supervised tuning pipeline and execute that pipeline to train and deploy a tuned LLM.
  * Output and study safety scores to responsibly monitor and filter LLM application’s behavior.
  * Tools used include BigQuery data warehouse, the open-source Kubeflow Pipelines, and Google Cloud.
