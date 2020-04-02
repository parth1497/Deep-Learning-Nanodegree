# Introduction

Using PyTorch I have implemented the Word2Vec algorithm using the skip-gram architecture and using negative sampling.

## Word2Vec

The Word2Vec algorithm finds efficient representations by finding vectors that represent the words. These vectors also contain semantic information about the words. Words that show up in similar contexts will have vectors near each other. Different words will be further away from one another, and relationships can be represented by distance in vector space. Skip-gram architecture with negative sampling performs better than CBOW and trains faster with negative sampling. A word is passed and we try to predict the words surrounding it in the text. In this way, we can train the network to learn representations for words that show up in similar contexts.

