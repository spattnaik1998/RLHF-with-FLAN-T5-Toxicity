# RLHF-with-FLAN-T5-Toxicity

Objective: Lower the Toxicity of the FLAN-T5 Dialogue Summarizer

While we are maximizing the reward, we do not want irrelevant outputs to secure a high reward score. Therefore, we use the fine-tuned LLM in tandem with a base model to make sure that the disparity between the responses is low.

Since the primary goal entails the lowering of toxicity, we use the evaluator model to compare the toxicity score before and after the Reinforcement Learning is applied to the model. The goal is to reduce the mean toxicity score after implementing the PPO.
