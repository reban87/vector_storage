# Basic embedding retrieval with Chroma

This project demonstrates the most basic use of Chroma to store and retrieve information using embeddings. This core building block is at the heart of many powerful AI applications.

## What are embeddings?

Embeddings are the A.I-native way to represent any kind of data, making them the perfect fit for working with all kinds of A.I-powered tools and algorithms. They can represent text, images, and soon audio and video.

To create an embedding, data is fed into an embedding model, which outputs vectors of numbers. The model is trained in such a way that 'similar' data, e.g. text with similar meanings, or images with similar content, will produce vectors which are nearer to one another, than those which are dissimilar.

## Embeddings and retrieval

We can use the similarity property of embeddings to search for and retrieve information. For example, we can find documents relevant to a particular topic, or images similar to a given image. Rather than searching for keywords or tags, we can search by finding data with similar semantic meaning.
