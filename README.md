# MergeKit to merge LLMs

mergekit is a toolkit for merging pre-trained language models. mergekit uses an out-of-core approach to perform unreasonably elaborate merges in resource-constrained situations. Merges can be run entirely on CPU or accelerated with as little as 8 GB of VRAM. Many merging algorithms are supported, with more coming as they catch my attention.

Features:

Supports Llama, Mistral, GPT-NeoX, StableLM, and more
Many merge methods
GPU or CPU execution
Lazy loading of tensors for low memory use
Interpolated gradients for parameter values (inspired by Gryphe's BlockMerge_Gradient script)
Piecewise assembly of language models from layers ("Frankenmerging")