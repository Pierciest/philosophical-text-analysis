# Semantic Analysis of Philosophical Texts

This project conducts a semantic analysis of major philosophical works by **Albert Camus**, **Franz Kafka**, **Immanuel Kant**, and **Jean-Paul Sartre**. Using Word2Vec models, it calculates semantic distances between existential concepts such as **Death**, **Life**, and **Justice**, offering insights into how these themes are explored across different philosophical traditions.

By leveraging computational techniques, this analysis maps out thematic focuses in each text, providing a data-driven approach to understanding philosophical discourse. Visualizations such as **word clouds**, **ternary plots**, and **radar charts** are used to present these relationships in an accessible manner, offering new perspectives on existential and metaphysical philosophy.

[Kaggle Link](https://www.kaggle.com/code/mertozcan/philosophical-text-analysis-with-word2vec)

## Key Features

### 1. Text Preprocessing
- **Text Extraction**: Extracts raw text from `.txt` files of philosophical works acquired using Amazon AWS Textractor.
  - **Note**: Due to copyright restrictions, these `.txt` files cannot be included in this repository.
- **Tokenization & Lemmatization**: Tokenizes, lemmatizes, and removes filler words, punctuation, and stop words to prepare the text for analysis.
- **NLP**: Ensures clean input data for word embedding using Natural Language Processing (NLP) techniques.

### 2. Word Embedding and Semantic Distance Calculation
- **Word2Vec Training**: Trains Word2Vec models on preprocessed texts to capture the contextual relationships between words.
- **Semantic Distance Calculation**: Computes Euclidean distances between word vectors for key existential concepts like **Death**, **Life**, and **Justice**.
- **Contextual Aggregation**: Aggregates contextually similar words to these concepts, enabling thematic analysis.

### 3. Visualizations
- **Word Clouds**: Generates word clouds to visualize words closely associated with **Death**, **Life**, and **Justice**. The size of each word represents its semantic proximity to the key concept.
- **Ternary Plots**: Displays the relative semantic distances between **Death**, **Life**, and **Justice** in 3D space for each text.
- **Radar Charts**: Visualizes how each work relates to these three key concepts, showing the thematic emphasis across different authors.

## Philosophical Text Corpus

This project analyzes texts from existential and moral philosophy, including:

- Albert Camus: *The Stranger*, *The Plague*, *The Myth of Sisyphus*
- Franz Kafka: *Metamorphosis*, *The Trial*, *The Castle*
- Immanuel Kant: *Groundwork of the Metaphysics of Morals*, *Critique of Pure Reason*
- Jean-Paul Sartre: *Nausea*, *Existentialism is Humanism*

These texts provide a basis for comparative thematic analysis of existential and moral philosophy.

## Comprehensive Thematic Comparison

The analysis provides quantifiable insights into how concepts of **Death**, **Life**, and **Justice** are treated across different philosophical works, enabling a deeper understanding of existential and moral philosophy.

### Key Insights:

- **Albert Camus**: 
  - *The Stranger* has a strong thematic focus on **Death** with close ties to **Life**, reflecting absurdist themes.
  - *The Myth of Sisyphus* emphasizes **Justice** in relation to rebellion and human struggle.
  - *The Plague* provides a balanced treatment of **Death**, **Life**, and **Justice**, exploring human suffering and morality.
- **Franz Kafka**: 
  - *The Trial* distances **Justice** from **Life** and **Death**, critiquing bureaucratic absurdity.
  - *Metamorphosis* focuses on **Life**, with **Death** playing a significant secondary role, capturing existential despair.
- **Immanuel Kant**: 
  - In *Groundwork* and *Critique of Pure Reason*, **Justice** dominates, while **Death** plays a minor role, reflecting Kant’s ethical structures.
- **Jean-Paul Sartre**: 
  - *Nausea* focuses heavily on **Life**, with **Death** and **Justice** playing peripheral roles, representing existential nausea and freedom.
  - *Existentialism is Humanism* balances **Life**, **Justice**, and **Death**, highlighting the interconnections between human freedom, morality, and existential reality.

## Visualizations

The project includes a range of visualizations:

- **Ternary Plot**: Displays each book's relative focus on **Death**, **Life**, and **Justice**.
- **Radar Charts**: Provides a comparative view of each book's treatment of these concepts.
- **Word Clouds**: Illustrates the most contextually similar words to the target concepts in each text.

## Acknowledgments

This project is made possible by the profound contributions of **Albert Camus**, **Franz Kafka**, **Immanuel Kant**, and **Jean-Paul Sartre** to existential and moral philosophy, and by open-source tools like `NLTK`, `Gensim`, `Matplotlib`, and `Plotly`.

---
