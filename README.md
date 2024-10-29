# Classificação de Segmentos de Clientes com Árvore de Decisão

Este projeto utiliza uma Árvore de Decisão para classificar segmentos de clientes com base em dados fornecidos. O código foi implementado em Python, com otimização de hiperparâmetros feita por meio do Optuna, e uma interface de predição criada com Gradio.

## Tabela de Conteúdos
- [Sobre o Projeto](#sobre-o-projeto)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Arquitetura do Projeto](#arquitetura-do-projeto)
- [Uso do Projeto](#uso-do-projeto)
- [Exemplo de Interface Gradio](#exemplo-de-interface-gradio)
- [Otimização de Hiperparâmetros](#otimização-de-hiperparâmetros)
- [Visualização da Árvore de Decisão](#visualização-da-árvore-de-decisão)
- [Salvamento e Carregamento do Modelo](#salvamento-e-carregamento-do-modelo)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Sobre o Projeto

Este projeto visa classificar clientes em diferentes segmentos usando uma Árvore de Decisão. Algumas das principais etapas incluem:
1. Preparação e pré-processamento dos dados.
2. Otimização de hiperparâmetros da Árvore de Decisão utilizando Optuna.
3. Treinamento do modelo com validação cruzada.
4. Construção de uma interface com Gradio para permitir que usuários façam upload de arquivos `.csv` para predição.

## Pré-requisitos

Certifique-se de ter instalado:
- Python 3.7 ou superior
- Pandas
- Scikit-Learn
- Optuna
- Gradio
- Joblib
- Matplotlib (opcional, para visualização da árvore de decisão)

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu_usuario/classificacao_segmentos_arvore_decisao.git
   cd classificacao_segmentos_arvore_decisao
