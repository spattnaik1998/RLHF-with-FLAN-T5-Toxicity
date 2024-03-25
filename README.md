# RLHF-with-FLAN-T5-Toxicity

FLAN-T5 Dialogue Summarizer is used to reduce toxicity in social media comments. The methodology involves preparing a reward model that will calculate the reward score in tandem with KL Divergence to make sure that the model doesn't circumvent the policies in place to achieve a high reward score. The response of the fine-tuned model is compared with the instruct model to meadure the value of KL Divergence. With each epoch we observe the value of KL Divergence plumetting as we ideally want least disparity in the response from the instruct and the fine-tuned model.
