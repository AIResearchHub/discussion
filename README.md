# Discussion


## TODO
 - [ ] Experiment - Longformer @Yuetian
 
 - [ ] Combine Longformer with XL (code needs review)
 - [ ] Upgrade DDPG to TD3 (code needs review)
 - [ ] Block Recurrent Transformer from scratch (code needs review)
 
 - [ ] Integrate Flash Attention
 - [ ] Modify ReplayBuffer for any recurrent states
 - [ ] Finish BERT Evaluation for Gallery (Perplexity etc...)
 - [ ] Finish Recurrent Training Trainer for any transformer
 - [ ] Include stock indicators and time into model inputs (Volume, earnings etc...)

## Notes

 - Transformer XL states can't fit into ReplayBuffer
 - Block Recurrent Transformer states can only fit if seqlen is <50
 - ReplayBuffer can only save states per block not per timestep

## Resources


### TransformerXL
 - arXiv Paper: https://arxiv.org/abs/1901.02860
 - 

### Longformer
 - arXiv Paper: https://arxiv.org/abs/2004.05150
 - Longformer: The Long-Document Transformer (Yannic Kilcher): https://www.youtube.com/watch?v=_8KNb5iqblE
 - How much memory does Longformer use? (Yannic Kilcher): https://www.youtube.com/watch?v=gJR28onlqzs
 - Longformer Blog: https://towardsdatascience.com/longformer-the-long-document-transformer-cdfeefe81e89


### Big Bird
 - Huggingface: https://huggingface.co/blog/big-bird
 - Variants of attention: https://huggingface.co/blog/big-bird


### Block Recurrent Transformer
 - arXiv Paper: https://arxiv.org/abs/2203.07852


### Twin Delayed DDPG
 - arXiv Paper: https://arxiv.org/pdf/1802.09477.pdf
 - OpenAI Spinning Up: https://spinningup.openai.com/en/latest/algorithms/td3.html


### Other
 - One Write-Head is All You Need: https://arxiv.org/abs/1911.02150
 - Flash Attention: https://arxiv.org/abs/2205.14135
 - Diagonal State Space Models for long sequences: https://arxiv.org/abs/2206.11893
 - 

### Repo

 [![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=augustwester&repo=transformer-xl)](https://github.com/augustwester/transformer-xl)

 [![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=lucidrains&repo=block-recurrent-transformer-pytorch)](https://github.com/lucidrains/block-recurrent-transformer-pytorch)
 
 [![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=allenai&repo=longformer)](https://github.com/allenai/longformer)


## Links

