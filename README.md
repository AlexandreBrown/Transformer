# Transformer
PyTorch implementation of transformer model architecture presented in the paper "Attention Is All You Need"

Original Paper : https://arxiv.org/abs/1706.03762

My Implementation : [see Notebook](./step_by_step_transformer.ipynb)  
Note: The implementation is meant to be used for learning purposes (step-by-step and explicit style), a more efficient implementation can be achieved but some optimization tricks (like using a single nn.Linear layer to compute all QKV projections) were left behind to keep it simpler and closer to the paper's text.  

# ViT  
Original Paper : https://arxiv.org/abs/2010.11929  
  
My Implementation : [see Notebook](./vit.ipynb)  
Note: The implementation is meant to be used for training and learning purposes. It uses the [high-performance PyTorch Scaled Dot Product Attention (SDPA)](https://pytorch.org/tutorials/intermediate/scaled_dot_product_attention_tutorial.html#beta-implementing-high-performance-transformers-with-scaled-dot-product-attention-sdpa). I tried to keep the code as clean as possible without sacrificing on performance.