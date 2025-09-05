# Definição do Método Analítico para Análise de Sentimentos em Companhias Aéreas

### Sumário
- [Introdução](#introdução)
- [Metadados](#metadados)
- [Metadatas](#Metadata)
- [Colaboradores](#colaboradores)

---

### Introdução

O crescimento exponencial da produção editorial e a digitalização do acesso a livros têm ampliado significativamente as possibilidades de leitura, mas também gerado um desafio para leitores que precisam escolher entre milhares de opções disponíveis. Nesse cenário, os sistemas de recomendação surgem como ferramentas essenciais para personalizar a experiência do usuário, sugerindo conteúdos que se alinham ao seu perfil e preferências de leitura.
Para este projeto, será utilizado o Book Recommendation Dataset, disponível na plataforma Kaggle, que reúne informações de usuários, livros e avaliações. O conjunto de dados contém aproximadamente 270 mil usuários, mais de 270 mil livros e mais de 1 milhão de avaliações, permitindo a aplicação de diferentes técnicas de recomendação, como filtragem colaborativa, recomendação baseada em conteúdo e abordagens híbridas. O uso deste dataset possibilita o desenvolvimento de um sistema capaz de apoiar a democratização da leitura, tornando o acesso ao conhecimento mais inclusivo e alinhado aos Objetivos de Desenvolvimento Sustentável (ODS), em especial o ODS 4 – Educação de Qualidade.


---

### Metadados

### Fonte dos Dados

Os dados foram obtidos do conjunto ["Book Recommendation Dataset"](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset) disponível no Kaggle.

### Método de Coleta

Os tweets foram coletados em fevereiro de 2015 e classificados manualmente por sentimento (positivo, neutro ou negativo) em relação às principais companhias aéreas dos EUA.

### Formato do Arquivo

- **Tipo de Arquivo**: CSV (Comma-Separated Values).

### Licença de Uso

Os dados são disponibilizados no Kaggle para fins de pesquisa, análise e desenvolvimento, sendo permitida sua utilização para esses propósitos. No entanto, o uso comercial ou a redistribuição sem autorização expressa pode estar sujeito a restrições.

### Contato

Para mais informações ou dúvidas sobre o uso dos dados, consulte a [página do conjunto de dados no Kaggle](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment) ou utilize os canais de comunicação da plataforma.

---

### Metadata

| Nome da Coluna                 | Tipo    | Descrição                                                                                                                                         |
|--------------------------------|---------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| **tweet_id**                   | int64   | Identificador único do tweet.                                                                                                                     |
| **airline_sentiment**          | object  | Classificação do sentimento do tweet (por exemplo, positivo, negativo ou neutro).                                                                |
| **airline_sentiment_confidence** | float64 | Nível de confiança associado à classificação do sentimento.                                                                                     |
| **negativereason**             | object  | Motivo associado à classificação negativa, quando aplicável (nem todos os tweets possuem esse valor).                                             |
| **negativereason_confidence**  | float64 | Nível de confiança na identificação do motivo negativo.                                                                                         |
| **airline**                  | object  | Nome da companhia aérea mencionada no tweet.                                                                                                      |
| **airline_sentiment_gold**   | object  | Anotação de sentimento padrão (gold standard) para validação, disponível para uma amostra restrita.                                                 |
| **name**                     | object  | Nome ou identificador do usuário que postou o tweet.                                                                                              |
| **negativereason_gold**      | object  | Anotação gold do motivo negativo, usada para validação, disponível em poucos casos.                                                               |
| **retweet_count**            | int64   | Número de vezes que o tweet foi retweetado.                                                                                                       |
| **text**                     | object  | Conteúdo textual completo do tweet.                                                                                                               |
| **tweet_coord**              | object  | Coordenadas geográficas (latitude e longitude) do tweet, quando disponíveis.                                                                      |
| **tweet_created**            | object  | Data e hora em que o tweet foi criado.                                                                                                            |
| **tweet_location**           | object  | Localização informada no tweet, quando disponível.                                                                                              |
| **user_timezone**            | object  | Fuso horário do usuário que postou o tweet, quando disponível.                                                                                    |

---

### Colaboradores

**Alunos**  
- Felipe Fagion Longarini  
- Lucas Oliveira  
- Gleider Mackedanz de Campos  
- Gabriel Henrique Titanegro Zanelatto  

**Professor**  
- Felipe Albino Dos Santos


<br>
