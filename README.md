 # Fine-Tuning Falcon for Mental Health Q&A using LoRA and PEFT
 This project demonstrates fine-tuning the [Falcon-7B BF16 model](https://huggingface.co/ybelkada/falcon-7b-sharded-bf16) for domain-specific mental health question answering using parameter-efficient LoRA tuning.
## 📌 Summary
- Adapted Falcon-7B to the mental health support domain
- Used [PEFT](https://github.com/huggingface/peft) + LoRA + k-bit quantization for memory-efficient training
- Trained using SFTTrainer for simplified supervised fine-tuning
- Frameworks: Transformers, PEFT, Accelerate
- Environment: T4 via Colab for LoRA

## Example Outcome
![image](https://github.com/user-attachments/assets/8c8d2cad-2ae2-4d98-ae92-7e8e32f181fe)
