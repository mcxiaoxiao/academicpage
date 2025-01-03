---
title: "QDA-SQL: Questions Enhanced Dialogue Augmentation for Multi-Turn Text-to-SQL"
collection: publications
permalink: /publication/QDA-SQL
excerpt: 'Fine-tuning LLMs for Text-to-SQL tasks is effective, but they often struggle with multi-turn queries due to ambiguity. QDA-SQL, a data augmentation method that generates diverse multi-turn Q&A pairs using LLMs. Fine-tuning with QDA-SQL improves SQL statement accuracy and enhances the models&apos; ability to manage challenging, unanswerable questions. The generation script and test set are released at [Github](https://github.com/mcxiaoxiao/QDA-SQL).'
date: 2024-06-15
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2406.10593'
---

Fine-tuning large language models (LLMs) for specific domain tasks has achieved great success in Text-to-SQL tasks. However, these fine-tuned models often face challenges with multi-turn Text-to-SQL tasks caused by ambiguous or unanswerable questions. It is desired to enhance LLMs to handle multiple types of questions in multi-turn Text-to-SQL tasks. To address this, we propose a novel data augmentation method, called QDA-SQL, which generates multiple types of multi-turn Q&A pairs using LLMs. In QDA-SQL, we introduce a method incorporating validation and correction mechanisms to handle complex multi-turn Text-to-SQL tasks. Experimental results demonstrate that QDA-SQL enables fine-tuned models to exhibit higher performance on SQL statement accuracy and enhances their ability to handle complex, unanswerable questions in multi-turn Text-to-SQL tasks. The generation script and test set are released at [Github](https://github.com/mcxiaoxiao/QDA-SQL). <br/><br/><img src='/images/qda.svg'>
