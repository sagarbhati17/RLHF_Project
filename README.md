## Fine-Tune LLM With RLHF To Detoxify Summaries

- **Fine-tuned FLAN-T5** using Reinforcement Learning from Human Feedback (RLHF) to generate less toxic summaries.
- Conducted **Parameter-Efficient Fine-Tuning (PEFT)** using **LoRA** to optimize the model with fewer parameters.
- Utilized **Meta AI's RoBERTa-based hate speech model** to generate reward values for guiding the fine-tuning process.
- Employed **Proximal Policy Optimization (PPO)** to adjust the model based on the generated reward values, improving the quality of the summaries.
