# MGSKD
This repository contains the implementation of our proposed knowledge distillation method MGSKD (i.e., Multi-Granularity Structural Knowledge Distillation for Language Model Compression, ACL 2022).

Our method is implemented mainly based on [TinyBERT](https://github.com/huawei-noah/Pretrained-Language-Model/tree/master/TinyBERT). We initialize our student model with the generally distilled [TinyBERT-4-312](https://huggingface.co/huawei-noah/TinyBERT_General_4L_312D) and distill the student on the same augmented datasets. We provide the [checkpoints](https://drive.google.com/file/d/1BuQXpgFuUwzDn8S97KTT6sxdy-rFZFzY/view?usp=sharing) after MGSKD distillation for further evaluation. One can directly fine-tune them on GLUE or further distill them by the teacher's prediction distribution for evaluation.
