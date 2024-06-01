# The Three Ways of Attention and Dot Product Attention

In this notebook, you'll explore the three ways of attention (encoder-decoder attention, causal attention, and bi-directional self-attention) and how to implement the latter two with dot product attention.

Attention Models constitute powerful tools in the NLP practitioner's toolkit. Like LSTMs, they learn which words are most important to phrases, sentences, paragraphs, and so on. Moreover, they mitigate the vanishing gradient problem even better than LSTMs. You've already seen how to combine attention with LSTMs to build encoder-decoder models for applications such as machine translation.

## Objectives 🎯
- Integrate attention into transformers.
- Understand the ease of parallelizing and accelerating transformers compared to sequential models.
- Explore various applications of transformers such as:
  - Machine translation
  - Auto-completion
  - Named Entity Recognition
  - Chatbots
  - Question-Answering
  - And more!
 
## Components 🛠️
Along with embedding, positional encoding, dense layers, and residual connections, attention is a crucial component of transformers. At the heart of any attention scheme used in a transformer is dot product attention.


## Implementation 🚀
- **Encoder-Decoder Attention:** Implement the encoder-decoder attention mechanism.
- **Causal Attention:** Implement causal attention with masking.
- **Bi-directional Self-Attention:** Implement bi-directional self-attention using dot product attention.

