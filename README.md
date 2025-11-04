# Continual-Learning
# Elastic Weight Consolidation (EWC) on CIFAR-10 and Fashion-MNIST

This PyTorch script demonstrates continual learning using **Elastic Weight Consolidation (EWC)** across two distinct tasks:
1. **Task A**: Classification on CIFAR-10 (natural object images)
2. **Task B**: Classification on Fashion-MNIST (grayscale clothing images, resized and converted to RGB)

### Key Features:
- Trains a shared CNN model sequentially on both tasks.
- Computes Fisher Information Matrix after Task A.
- Applies EWC regularization during Task B training to retain knowledge from Task A.
- Measures performance drop (catastrophic forgetting) and task adaptation.

### Output:
- Accuracy on CIFAR-10 after Task A
- Accuracy on CIFAR-10 after Task B (with EWC)
- Accuracy on Fashion-MNIST after Task B


