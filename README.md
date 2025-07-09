# Sentiment-RLHF-GPT2 [Reinforcement Learning from Human Feedback (RLHF)]

In this project, I did a mini experiment with `RLHF`, used `GPT-2` model, a sentiment-based reward model from Huggingface: `cardiffnlp/twitter-roberta-base-sentiment-latest`, also `PPO` or Proximal Policy Optimization training with the trl library.

- I found rewards can be repetitive and provide some junk outputs, so I need very careful focus on designing a better reward function.
- Also I need to work on tuning different params for training stability, as for now it just work the minimal purpose.
- Also, we need to see how the token-wise reward feedback works rather than the response-level reward in this experiment.

But, this helps to understand how to implement RLHF with a sentiment-based reward model
