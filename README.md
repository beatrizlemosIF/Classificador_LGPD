# Classificador de Dados Sensíveis conforme a LGPD

Projeto de Iniciação Científica voltado ao desenvolvimento e avaliação de modelos de *Machine Learning* para identificação automática de dados pessoais e sensíveis, conforme a Lei Geral de Proteção de Dados (LGPD), a partir de textos em língua portuguesa.


---

## 🎯 Objetivo

Desenvolver, comparar e avaliar abordagens de classificação de dados sensíveis em textos, analisando:

- Um modelo **baseline**, sem uso de NER, baseado em palavras-chave;
- Um modelo **aprimorado**, com extração de entidades nomeadas (NER);
- A influência do tipo de dataset utilizado no desempenho dos modelos.

---

## 🧪 Metodologia

Foram avaliadas duas abordagens principais:

### 1️⃣ Abordagem Baseline (sem NER)
- Classificação baseada em palavras-chave
- Técnicas tradicionais de pré-processamento de texto
- Modelos de *Machine Learning* supervisionados

### 2️⃣ Abordagem com NER
- Extração de entidades nomeadas (ex.: nomes próprios, documentos, localizações)
- Enriquecimento do texto antes da etapa de classificação
- Comparação direta com o modelo baseline

---

## 📊 Conjuntos de Dados

Foram utilizados dois tipos de datasets:

### 🔹 Dataset 1 — Palavras-chave
Conjunto inicial contendo apenas palavras-chave associadas a categorias de dados pessoais e sensíveis.

### 🔹 Dataset 2 — Registros Simulados
Conjunto ampliado contendo **registros textuais simulados**, representativos de dados pessoais, construídos exclusivamente para fins acadêmicos, sem uso de dados reais sensíveis.

> ⚠️ Todos os dados utilizados respeitam princípios éticos e a LGPD. Nenhuma informação pessoal real é armazenada no repositório. (são dados fictícios)

---

## 🧪 Testes e Validação

A validação dos modelos foi realizada utilizando textos extraídos de:

- **Sites de prefeituras** (domínio público)
- **Documentos em formato PDF** de acesso público

Esses testes visam avaliar o comportamento dos modelos em cenários próximos ao uso real, fora do conjunto de treinamento.

Os resultados encontram-se organizados na pasta 

---

## 📁 Estrutura do Repositório


---

## 🚀 Tecnologias Utilizadas

- Python
- Pandas
- Scikit-learn
- NLP (NLTK / spaCy)
- Google Colab

---

## 📌 Resultados Esperados

- Comparação de métricas entre as abordagens com e sem NER
- Análise do impacto do enriquecimento semântico no desempenho do classificador
- Avaliação da robustez dos modelos em textos reais de domínio público

---

## 👩‍🎓 Autora

Beatriz Lemos
Orientadores : Andreiwid Sheffer Correa e Luis Carlos Kakimoto
Projeto de Iniciação Científica  
Área: Ciência de Dados / Processamento de Linguagem Natural

---

## 📄 Licença

Este projeto é destinado exclusivamente a fins acadêmicos e de pesquisa.

