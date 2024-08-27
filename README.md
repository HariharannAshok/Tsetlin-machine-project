# Sentiment Analysis and Machine Translation of UK (British) Slang Using Tsetlin Machines

## Project Overview

This project explores the innovative application of Tsetlin Machines for sentiment analysis and machine translation, with a focus on UK (British) slang. Slang, being informal and constantly evolving, presents significant challenges for traditional natural language processing (NLP) models. By leveraging the rule-based, interpretable nature of Tsetlin Machines, this research aims to develop a robust NLP system capable of accurately translating British slang into standard English while preserving the sentiment and contextual nuances of the original text.

## Aims and Objectives

- **Develop a Slang Dictionary**: Construct a comprehensive dictionary of UK slang terms paired with their formal English equivalents to facilitate accurate translation.
- **Preprocessing Pipeline**: Implement a preprocessing pipeline to normalize slang in text data, ensuring that the informal language is effectively transformed for subsequent analysis.
- **Tsetlin Machine Model**: Develop and train a Tsetlin Machine model for sentiment analysis, tailored to handle the complexities of slang-influenced language.
- **Model Evaluation**: Evaluate the performance of the Tsetlin Machine model using cross-validation and benchmark it against other state-of-the-art models like Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs).
- **Interpretability**: Examine the interpretability of the Tsetlin Machine’s decision-making process, particularly in how it translates slang and analyzes sentiment, providing insights into its predictions.

## Methodology

1. **Data Acquisition**: The dataset includes 127 distinct British slang terms and their formal English translations, alongside a sentiment analysis dataset containing 500 records sourced from various social media platforms.
2. **Data Preprocessing**: The preprocessing involves text cleaning, slang normalization using a custom-built slang dictionary, tokenization, padding & truncating to a uniform length, and one-hot encoding to prepare the text data for the Tsetlin Machine.
3. **Model Implementation**: The Tsetlin Machine model is trained through a unique reward and penalty mechanism, allowing it to accurately learn the translation of slang terms and the sentiment behind informal language.

## Results and Discussion

### Performance Metrics
The Tsetlin Machine demonstrates superior performance compared to traditional deep learning models (CNNs and RNNs) in terms of accuracy, precision, recall, and F1 score, particularly in handling the nuanced sentiment of British slang.

### Interpretability
Unlike "black-box" models, the Tsetlin Machine’s rule-based approach offers transparency in its decision-making process, making it particularly valuable in domains where understanding the rationale behind predictions is critical.

### Efficiency
The model is computationally efficient, making it suitable for deployment in resource-constrained environments like mobile devices, edge computing platforms, or real-time applications.

## Conclusion

This project successfully demonstrates the potential of Tsetlin Machines in addressing the challenges posed by informal language, particularly British slang, in sentiment analysis and machine translation. The Tsetlin Machine’s ability to deliver high performance, combined with its interpretability and computational efficiency, makes it a promising tool for future NLP applications. The findings of this research contribute valuable insights to the field of NLP, particularly in processing and understanding informal and context-dependent language.

## Future Work

- **Dataset Expansion**: Expand the slang dataset to include a wider variety of terms and phrases, further improving the model’s accuracy and robustness.
- **Model Optimization**: Explore advanced tuning and optimization of the Tsetlin Machine, as well as experimenting with hybrid models combining CNNs, RNNs, and Tsetlin Machines to enhance overall performance.
- **Contextual Understanding**: Investigate models that incorporate deeper contextual understanding to improve performance on tasks involving highly informal or slang-filled language.
- **Real-time Application**: Develop and deploy a real-time translation and sentiment analysis web application capable of instantly translating UK slang to proper English and providing sentiment analysis. This tool could be invaluable for social media monitoring, customer sentiment tracking, and other real-time NLP tasks.

## References

1. Granmo, O. (2018). "The Tsetlin Machine - A Game Theoretic Bandit Driven Approach to Optimal Pattern Recognition with Propositional Logic." arXiv preprint arXiv:1804.01508.
2. Saha, R., Granmo, O.-C., & Goodwin, M. (2021). "Using Tsetlin Machine to discover interpretable rules in natural language processing applications." Expert Systems, 38(5), e12873.
3. Zhang, X., Zhou, H., Yu, K., Zhang, X., Wu, X., & Yazidi, A. (2022). "Sentiment Analysis for Chinese Dataset with Tsetlin Machine." In Proceedings of the 2022 International Symposium on Tsetlin Machine (ISTM).
4. Kusum, & Panda, S. (2022). "Sentiment Analysis on Tweets with Deep Learning and Natural Language Processing." In Proceedings of the 2022 International Conference on Computers, Information, and Communication Technology (COM-IT-CON). IEEE.
5. Li, D., Rzepka, R., Ptaszynski, M., & Araki, K. (2019). "A Novel Machine Learning-based Sentiment Analysis Method for Chinese Social Media Considering Chinese Slang Lexicon and Emoticons." In Proceedings of the AAAI Conference on Artificial Intelligence.
6. Toral, A., & Sánchez-Cartagena, V. M. (2017). "A Multifaceted Evaluation of Neural versus Phrase-Based Machine Translation for 9 Language Directions." In Proceedings of the 15th Conference of the European Chapter of the Association for Computational Linguistics: Volume 1, Long Papers.
7. Derbentsev, V. D., Bezkorovainyi, V. S., Matviychuk, A. V., Pomazun, O., & Hrabariev, A. V. (2022). "A Comparative Study of Deep Learning Models for Sentiment Analysis of Social Media Texts." In Proceedings of the 2022 International Conference on Mathematical Models and Methods in Environmental and Energy Systems (M3E2).
8. Wu, Z., Li, Z., Wei, D., Shang, H., Guo, J., Chen, X., Rao, Z., Yu, Z., Yang, J., Li, S., Xie, Y., Wei, B., Zheng, J., Zhu, M., Lei, L., Yang, H., & Jiang, Y. (2023). "Improving Neural Machine Translation Formality Control with Domain Adaptation and Reranking-based Transudative Learning." In Proceedings of the 2023 International Workshop on Spoken Language Translation.

