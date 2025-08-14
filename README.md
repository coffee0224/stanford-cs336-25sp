# CS336: Language Modeling from Scratch. Spring 2025

- [ ] [Assignment 1: Basics](https://github.com/stanford-cs336/assignment1-basics/tree/main) [leaderboard]
    - Implement all of the components (tokenizer, model architecture, optimizer) necessary to train a standard Transformer language model.
    - Train a minimal language model.
- [ ] [Assignment 2: Systems](https://github.com/stanford-cs336/assignment2-systems/tree/main) [leaderboard]
    - Profile and benchmark the model and layers from Assignment 1 using advanced tools, optimize Attention with your own Triton implementation of FlashAttention2.
    - Build a memory-efficient, distributed version of the Assignment 1 model training code.
- [ ] [Assignment 3: Scaling](https://github.com/stanford-cs336/assignment3-scaling/tree/main)
    - Understand the function of each component of the Transformer.
    - Query a training API to fit a scaling law to project model scaling.
- [ ] [Assignment 4: Data](https://github.com/stanford-cs336/assignment4-data) [leaderboard]
    - Convert raw Common Crawl dumps into usable pretraining data.
    - Perform filtering and deduplication to improve model performance.
- [ ] [Assignment 5: Alignment and Reasoning RL](https://github.com/stanford-cs336/assignment5-alignment)
    - Apply supervised finetuning and reinforcement learning to train LMs to reason when solving math problems.
    - Optional Part 2: implement and apply safety alignment methods such as DPO.