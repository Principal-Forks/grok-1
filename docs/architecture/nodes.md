# Architecture Nodes

## user_input
- **Type**: user_input
- **Position**: (100, 200)
- **Content**: User Input Raw text input from user

## tokenizer
- **Type**: tokenizer
- **Position**: (300, 200)
- **Content**: Tokenizer SentencePiece tokenizer

## language_model
- **Type**: language_model
- **Position**: (500, 200)
- **Content**: Grok-1 Model 314B parameter MoE

## transformer_1
- **Type**: transformer
- **Position**: (700, 100)
- **Content**: Transformer 1 First layer

## transformer_2
- **Type**: transformer
- **Position**: (700, 212)
- **Content**: Transformer 2 Second layer

## transformer_n
- **Type**: transformer
- **Position**: (700, 316)
- **Content**: Transformer N Final layer (64)

## attention
- **Type**: attention
- **Position**: (920, 115)
- **Content**: Attention 48Q/8KV heads

## moe_layer
- **Type**: moe_layer
- **Position**: (920, 207)
- **Content**: MoE Layer 8 experts, 2 active

## checkpoint
- **Type**: checkpoint
- **Position**: (510, 351)
- **Content**: Checkpoint Model weights

## inference_runner
- **Type**: inference_runner
- **Position**: (1085, 260)
- **Content**: Inference JAX execution

## model_output
- **Type**: model_output
- **Position**: (1300, 200)
- **Content**: Output Generated text

