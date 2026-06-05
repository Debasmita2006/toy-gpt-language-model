# toy-GPT Language Model - Project

## What I Built
A GPT (Generative Pre-trained Transformer) language model
trained on Shakespeare's complete works - built from scratch
using only Python and PyTorch.

This is the same architecture that powers ChatGPT!

## Technologies Used
- Python
- PyTorch (Deep Learning Framework)
- Google Colab (Cloud GPU Training)
- CUDA (GPU Acceleration)

## Model Architecture
- Type: Decoder-only Transformer (same as GPT)
- Parameters: 211,777
- Embedding size: 64
- Attention heads: 4 (running in parallel)
- Layers: 4 Transformer blocks
- Block size: 64 characters context window
- Dropout: 0.2 (prevents overfitting)

## Training Results
- Dataset: Tiny Shakespeare (1,115,394 characters)
- Training split: 90% train / 10% validation
- Initial loss: 4.32
- Final loss: 1.91
- Improvement: 55% reduction in loss!
- Training time: ~5 minutes on free GPU

## What the Model Learned
- Shakespeare dialogue structure (NAME: dialogue)
- English word patterns and endings
- Punctuation placement
- Sentence structure
- Character name formatting

## Key Concepts Implemented
- Tokenization (text to numbers and back)
- Token + Positional Embeddings
- Self-Attention (Query, Key, Value)
- Multi-Head Attention (4 parallel heads)
- Feed Forward Networks
- Residual Connections (skip connections)
- Layer Normalization
- Dropout Regularization
- Autoregressive Text Generation
- Cross Entropy Loss
- AdamW Optimizer

## Paper This Is Based On
'Attention Is All You Need' (Vaswani et al., 2017)
The landmark paper that introduced the Transformer
architecture - the foundation of all modern AI including
ChatGPT, GPT-4, Gemini and Claude!
