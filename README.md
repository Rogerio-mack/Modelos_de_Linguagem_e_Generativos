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
