# Modelos_de_Linguagem_e_Generativos
rogerio.oliveira@mackenzie.br

<br>

### **Link dos Encontros Síncronos**

> * [27 Outubro](https://teams.microsoft.com/l/meetup-join/19%3ameeting_YTgyOGU2YTgtYTNjNi00ZTFjLWJjNDItOWJlODk3NzY4ZmVj%40thread.v2/0?context=%7b%22Tid%22%3a%2251da9440-4e5e-47b3-8e5c-4817f6f43c04%22%2c%22Oid%22%3a%22e7fc012e-6f57-4879-9416-93179af90e74%22%7d)
| [10 Novembro](https://teams.microsoft.com/l/meetup-join/19%3ameeting_YTgyOGU2YTgtYTNjNi00ZTFjLWJjNDItOWJlODk3NzY4ZmVj%40thread.v2/0?context=%7b%22Tid%22%3a%2251da9440-4e5e-47b3-8e5c-4817f6f43c04%22%2c%22Oid%22%3a%22e7fc012e-6f57-4879-9416-93179af90e74%22%7d)
| [18 Novembro](https://teams.microsoft.com/l/meetup-join/19%3ameeting_YTgyOGU2YTgtYTNjNi00ZTFjLWJjNDItOWJlODk3NzY4ZmVj%40thread.v2/0?context=%7b%22Tid%22%3a%2251da9440-4e5e-47b3-8e5c-4817f6f43c04%22%2c%22Oid%22%3a%22e7fc012e-6f57-4879-9416-93179af90e74%22%7d)
| [24 Novembro](https://teams.microsoft.com/l/meetup-join/19%3ameeting_YTgyOGU2YTgtYTNjNi00ZTFjLWJjNDItOWJlODk3NzY4ZmVj%40thread.v2/0?context=%7b%22Tid%22%3a%2251da9440-4e5e-47b3-8e5c-4817f6f43c04%22%2c%22Oid%22%3a%22e7fc012e-6f57-4879-9416-93179af90e74%22%7d)
| [08 Dezembro](https://teams.microsoft.com/l/meetup-join/19%3ameeting_YjZmNzVkYTUtNTI4NS00ZTEzLThlNzEtNThjYzM4ZDc3ZTQz%40thread.v2/0?context=%7b%22Tid%22%3a%2251da9440-4e5e-47b3-8e5c-4817f6f43c04%22%2c%22Oid%22%3a%22e7fc012e-6f57-4879-9416-93179af90e74%22%7d)

<br>

### **Projetos**

Trabalho em grupo, máximo 6 alunos. Entrega e apresentação do projeto em 09.12. Cada grupo escolhe um dos temas para o projeto:

Projetos de no máximo 2 grupos:
> 1. **Vanilla LLM 1**. Implemente uma solução de Text Zero-Shot Classification com dados de um dos sites https://www.gutenberg.org/, http://arxiv.org/, https://www.imdb.com/ ou bulário eletrônico (https://consultas.anvisa.gov.br/#/bulario/). A solução deve mostrar e comparar os resultados (métricas) do modelo original e de uma solução com fine-tuning ou RAG (Retrieval-Augmented Generation).  
> 2. **Vanilla LLM 2**. Implemente uma solução de *Sentiment Analysis* sobre notícias em português empregando esses dados para a predição de algum indicador temporal. Por exemplo, notícias do mercado financeiro para predição de indicadores econômicos (selic, preço de ações, inflação), notícias gerais sobre uma cidade/local e indicadores de turismo (número de turistas, passagens etc.). Empregue dados originais/primários de notícias.
   
Projetos de no máximo 1 grupo:
> 4. **MCP (Model Context Protocol)**. Apresente, implemente e discuta uma solução de MCP envolvendo múltiplas fontes de dados.
> 5. **Text Style**. Implemente uma solução prática de Text Style (texto ou áudio).
> 6. **Code Learning**. Empregue um LLM para criar um question-answer de geração de código de uma nova linguagem. Empregue uma pequena linguagem nova (criada) ou uma linguagem de programação não usual. 
> 7. **GPU & resources**. Explore, mostrando resultados práticos, como pode ser feito o planejamento de recursos como GPU, memória, batch size etc. tendo em vista diferentes alternativas de fine-tunning de modelos LLM (considere texto e imagem).
> 8. **Segmentação de Imagens**. Apresente, implemente e discuta soluções (abertas) de segmentação de imagens médicas e compare seus resultados. Por exemplo, soluções de segmentação supervisionada e não supervisionada, uso de U-Net.
> 9. Algum outro projeto em mente?

Para todos projetos:
1. Empregar somente modelos e recursos abertos.
2. Ser 100% executável e aberto. Pode executar 100% em um notebook Colab ou em uma aplicação do tipo Streamlit. 
3. **GitHub**. Implementar um GitHub com o projeto com instruções de uso e informações básicas do projeto, incluindo Introdução, Referencial Teórico, Metodologia, Resultados e Conclusão (empregue o readme e arquivos adicionais de texto de precisar).
4. **YouTube**. Apresentação máximo 5min, YouTube.
5. **Mini-plano de negócios**. Na apresentação, não constando vídeo, apresentar/discutir uma potencial aplicação real para o tipo de projeto implementado.
   
<br>

## Aula 1

* [Questionário pré-curso](https://forms.gle/LkD3H8LBB6GpvZLv7)
* [Plano de Ensino](https://github.com/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/Plano_de_Ensino_Modelos_de_Linguagem_e_Generativos_20250416.pdf)
* [Introdução](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/MLG_01_Introducao.ipynb)

> * Leitura complementar (Cap 1): Alammar, Jay, and Maarten Grootendorst. [Hands-on large language models: language understanding and generation.](https://github.com/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/Hands-On-LLM/Jay%20Alammar%2C%20Maarten%20Grootendorst%20-%20Hands-On%20Large%20Language%20Models_%20Language%20Understanding%20and%20Generation%20(2024%2C%20O%E2%80%99Reilly%20Media)%20-%20libgen.pdf) O'Reilly Media, Inc., 2024.
<br>

> *Programa; Visão geral do curso; Introdução ao processamento de linguagem natural; representações vetorais BOW, TF-IDF; similaridade cosseno; outras representações vetorais; tarefas de modelos de linguagem; importância dos termos no aprendizado de máquina.*

## Aula 2

* [Luhn e Zipf Law](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/Zipf_Law.ipynb) 
* [Aprendizado de Máquina Supervisionado](https://github.com/Rogerio-mack/Machine-Learning-I) *Cap. 1, 4, 5* | [Exercício Resolvido](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/MLG_02_ML_Supervisionado_review.ipynb) | [Exercício](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/MLG_02_ML_Supervisionado_exercicio.ipynb) | [Solução](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/MLG_02_ML_Supervisionado_solucao.ipynb)
* [TF-IDF, TfidfVectorizer e Feature Importance](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/TFIDF_Feature_Importance.ipynb)

<br>

> *Lei de Zipf; Revisão Aprendizado de Máquina (Supervisionado): Cap1. Classificação e Regressão; Cap4. Sobreajuste e Conjuntos de Treinamento e Teste; Cap4. Métricas de Classificação; Cap5. Seleção de Atributos; TF-IDF, TfidfVectorizer para ML.*

## Aula 3

* [TF-IDF, TfidfVectorizer e Feature Importance](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/TFIDF_Feature_Importance.ipynb)
* [Redes Neurais e Deep Learning](https://github.com/Rogerio-mack/Deep-Learning-I) *Cap. 3, 4* | [Exercício](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/TF_TFIDF_classification.ipynb) | [Solução](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/TF_TFIDF_classification_solucao.ipynb)

> * Leitura complementar (explore): Zhang, A., Lipton, Z. C., Li, M., & Smola, A. J. (2023). [Dive into deep learning](https://d2l.ai/). Cambridge University Press.

> * [Exercício 1](https://forms.gle/pCuauRw1kcH4FqvS8) *Bom para, 07.Nov*
<br>

> *Modelos de redes neurais; Frameworks de Deep Learning; Auto Gradiente; GPU; TensorFlow Sequentical; Cross Entropy*

## Aula 4

* [Word Embedding](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/Word_Embedding_spaCy_Gensim.ipynb)
> * [PCA, by defition (math)](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/IMT_PCA_by_definition.ipynb)
> * [PCA, scikit-learn, Clustering and Classification](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/IMT_PCA_scikitlearn.ipynb)
> * [TensorFlow Embedding](https://www.tensorflow.org/text/tutorials/word_embeddings)

> * Leitura complementar: Christopher Manning, Richard Socher. [Natural Language Processing with Deep Learning. Lecture Notes: Part I Word Vectors I: Introduction, SVD and Word2Vec](https://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes01-wordvecs1.pdf)

> * [Exercício 2](https://forms.gle/SeQ9NZok2GH3CERn8) Empregando o como modelo [TensorFlow & Word2Vec](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/TF_word2vec.ipynb), treine um modelo próprio em português exibindo alguns resultados. *Bom para, 15.Nov*

> *Word embedding; Representação interna em uma rede neural; Redução de Dimensionalidade; Word2Vec; CBOW e Skip-gram*

## Aula 5 

* [Como os Transformers Funcionam?](https://github.com/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/4.md)
> * [Explorando os mecanismos de Atenção e a arquitetura Transformers](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/Attention_and_Transformers_Explorer.ipynb)

> * Link complementar: https://poloclub.github.io/transformer-explainer/
> * Leitura complementar: Guillaume Klein et. al [OpenNMT: Open-Source Toolkit for Neural Machine Translation](https://nlp.seas.harvard.edu/2018/04/03/attention.html#encoder-and-decoder-stacks), also [**The Annotated Transformer**](https://nlp.seas.harvard.edu/2018/04/03/attention.html#encoder-and-decoder-stacks). Ou se preferir de uma forma mais didática
[**How Transformers Work: A Detailed Exploration of Transformer Architecture**](https://www.datacamp.com/tutorial/how-transformers-work)

> *Mecanismo de Atenção; Tokenization e Models Transformers*

## Aula 6

* [De Volta a Representação Interna em uma Rede Neural](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/Representacao_Interna_NN.ipynb)
* [Deep dive into Atenção e Transformers](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/Atencao_QKV_transformers.ipynb)
* [Diferentes Tarefas com LLMs: *o pulo do gato!*](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/LLMs_Text_Classification.ipynb)

> *Cabeças de leitura, Paralelismo e Camadas Transformers; Diferentes Tarefas com LLMs: Modelos específicos, de incorporação e com modelos Generativos; Zero-shot Classification*

> * [Exercício 3](https://forms.gle/aV6xAF2SsKzVGkj77) *Bom para, 22.Nov*

## Aula 7

* [TF Classificação de Dígitos MNIST, MLP X Conv2D](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/MLG_TF_MNIST_Classifier.ipynb)
* [TF Classificação de Imagens, Conv2D](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/MLG_TF_ImageClassifier.ipynb)
* [CNN Explainer](https://poloclub.github.io/cnn-explainer/)

## Aula 8

* [Classificação de Imagens com VGG16, Flowers](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/AI_TF_ImageClassifier_VGG16.ipynb)
* [Object Detection (Yolo5, ResNet)](https://colab.research.google.com/github/Rogerio-mack/IA_2025S1/blob/main/Yolov5_Resnet50_object_detection.ipynb)
* [Yolo11, e outras tarefas de visão computacional](https://colab.research.google.com/github/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/Yolo11_Detection_Image_Video_Pose.ipynb)

* [Capítulo 6: Chabots Inteligentes na Saúde: Implementações com Modelos Abertos e Dados Próprios](https://github.com/Rogerio-mack/Modelos_de_Linguagem_e_Generativos/blob/main/Capitulo_6_LLM.pdf)





