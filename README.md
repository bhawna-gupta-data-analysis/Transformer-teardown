# Transformer-teardown
Taking transformer architecture apart, piece by piece — notes and resources on how LLMs actually work under the hood.

RoPE Rotatory Positional Encodings
<img width="919" height="419" alt="image" src="https://github.com/user-attachments/assets/e96cd4b6-d99e-4b6d-ad0d-7714085f4a64" />

MoE - Mixture of Experts -> consider having multiple experts, router routing request based on probability to the expert likely to solve problem.
<img width="881" height="399" alt="image" src="https://github.com/user-attachments/assets/d5808302-3f2b-4975-8afe-c7206d9a629c" />

Mistral has 8 experts and 5.6B Parameters (Sparse Parameters) -> 8 x 5.6B parameter model to download.
It may use 2 experts (Active Parameters) at a time -> 2 x 5.6B parameters :
<img width="854" height="383" alt="image" src="https://github.com/user-attachments/assets/a1a1da01-431f-482c-824d-8da7b1ea9654" />












