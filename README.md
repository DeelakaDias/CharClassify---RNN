# CharClassify - RNN
<p>This repository contains implementations of character-level Natural Language Processing (NLP) models for tasks like language modeling and text classification. It features multiple models, including Uniform, Frequency-based, and Recurrent Neural Network (RNN) models.</p>
<h1>Features</h1>
<ul>
  <li>Language Modeling: Computes metrics such as log-probability and perplexity of given text sequences.</li>
  <li>Text Classification: Differentiates between consonant- and vowel-related datasets using trained models.</li>
  <li>Customizable Vocabulary: Works with lowercase letters (a-z) and spaces.</li>
  <li>Dataset Evaluation: Evaluates models on training and development datasets./li>
</ul>

<h1>
  File Overview
</h1>
<ul>
  <li>lm.py: Handles training and evaluation of language models.</li>
  <li>lm_classifier.py: Handles text classification tasks.</li>
  <li>models.py: Core implementation of models (Uniform, Frequency-based, RNN).</li>
  <li>utils.py: Helper utilities for indexing, processing, and managing datasets.</li>
</ul>

<h1>
  Classifier Model
</h1>
<p>The classifier model distinguishes between text categories, specifically datasets related to consonants and vowels. It uses features derived from text patterns and applies either a Frequency-based or RNN-based approach to classify input examples. The model evaluates accuracy by comparing predicted labels with actual categories, making it effective for tasks requiring text categorization or pattern detection</p>

<h1>
  Language Model
</h1>
<p>The language model in this repository learns to predict the probability of a sequence of characters, making it suitable for tasks like text generation and analysis. It calculates key metrics such as log-probability, average log-probability, and perplexity, which measure how well the model understands the structure of the input text. Implementations include a Uniform baseline model and an RNN-based model for more complex, context-aware predictions.</p>
