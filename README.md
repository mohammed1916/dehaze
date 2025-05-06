# Deep Guided Dehazing

1. Teacher training from scale x4 to x times for super resolution: [dehaze/dehaze-kernel copy.ipynb at fe534aa834de4c08355cf56391879a2e4e055098 · mohammed1916/dehaze](https://github.com/mohammed1916/dehaze/blob/fe534aa834de4c08355cf56391879a2e4e055098/dehaze-kernel%20copy.ipynb)

   For log files with tensorboard refer: runs/sr_training_logs_teacher

2. Teacher finetuning from scale x2 to x for super resolution: [dehaze/dehaze-kernel copy.ipynb at c59b98bac4c31204bfde54574e59d77f606fb825 · mohammed1916/dehaze](https://github.com/mohammed1916/dehaze/blob/c59b98bac4c31204bfde54574e59d77f606fb825/dehaze-kernel%20copy.ipynb)

   For log files with tensorboard refer: runs/sr_training_logs_teacher_stepLR

## Ablation Study

Refer files: with final `ValidationB` function:

1. Without guided filter: `reside-dehaze-student-only-max-train.ipynb`
2. With Guided filter: `reside-dehaze-student-only.ipynb`
