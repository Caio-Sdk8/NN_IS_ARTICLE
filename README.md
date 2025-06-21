# COMPARAÇÃO ENTRE REDES NEURAIS E SISTEMAS IMUNOLÓGICOS ARTIFICIAIS PARA IDENTIFICAÇÃO DE DOENÇAS CARDIOVASCULARES

Este repositório contempla o desenvolvimento de duas inteligências artificiais preditivas: uma baseada em **redes neurais** e outra em **sistemas imunológicos artificiais**. O objetivo é realizar uma comparação científica entre os modelos quanto à sua aplicação na predição (ou auxílio na predição) de **doenças cardiovasculares**.

Ambos os modelos foram desenvolvidos de forma simples e clara, para permitir uma comparação direta, sem interferência de otimizações complexas.

## Conjuntos de Dados Utilizados

- [UCI Heart Disease (Cleveland)](https://archive.ics.uci.edu/dataset/45/heart+disease)
- [Kaggle Cardiovascular Disease Dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset/data)

A comparação detalhada está sendo realizada por meio de um artigo científico. O link será adicionado aqui assim que o artigo estiver concluído ou publicado.

## Como Testar os Modelos

As seções abaixo explicam como executar os modelos desenvolvidos neste repositório.

### Requisitos

Certifique-se de ter as seguintes ferramentas instaladas:

- [Git](https://git-scm.com/downloads)
- [Visual Studio Code](https://code.visualstudio.com/download)
- [Python 3.11](https://www.python.org/downloads/release/python-3110/)

> ⚠️ A versão 3.11 do Python foi escolhida por garantir compatibilidade com bibliotecas como TensorFlow, que podem não funcionar corretamente em versões mais recentes. Esta versão só usada para os modelos de redes neurais.

### Etapas - Redes Neurais

#### 1. Clonar o repositório, acessar a pasta dos modelos e abrir no VS Code:

```bash
git clone https://github.com/Caio-Sdk8/NN_IS_ARTICLE.git
cd NN_IS_ARTICLE/heart_disease_prediction_article/models
code .
```

#### 2. Instalar as dependências:

No terminal do VS Code, execute:

```bash
pip install -r requirements.txt
```

Se houver múltiplas versões do Python instaladas, utilize:

```bash
py -3.11 -m pip install -r requirements.txt
```

#### 3. Executar os modelos de rede neural:

Os arquivos de redes neurais terminam com `_NN.py`. O nome anterior indica qual dataset foi utilizado.

Para executar um modelo, use:

```bash
py nome_do_modelo_NN.py
```

Ou, especificando a versão do Python:

```bash
py -3.11 nome_do_modelo_NN.py
```

> 📌 **Exemplo:**
>
> ```bash
> py cleveland_NN.py
> ```

## Autores
<table>
  <tr>
    <td width="400px">
      <p>
        Este projeto foi desenvolvido por 3 estudantes da FATEC - Mogi das cruzes, para mais informações de cada um dos integrantes, clique no card ao lado ou no link para o LinkedIn de cada um deles.
      </p>
    </td>
    <td align="center">
      <a href="https://github.com/Caio-Sdk8">
        <img src="https://avatars.githubusercontent.com/u/82384954?v=4" width="220px" style="border-radius: 50%;" />
      </a>
      <br />
      <b>Caio Soares</b><br />
      Desenvolvedor<br />
      <a href="https://www.linkedin.com/in/caio-soares-a866b4215/?locale=en_US">LinkedIn</a>
    </td>
    <td align="center">
      <a href="https://github.com/1rg0">
        <img src="https://avatars.githubusercontent.com/u/54910774?v=4" width="220px" style="border-radius: 50%;" />
      </a>
      <br />
      <b>Igor Fernandes</b><br />
      Desenvolvedor e PO<br />
      <a href="https://www.linkedin.com/in/fernades-igor/">LinkedIn</a>
    </td>
    <td align="center">
      <a href="https://github.com/lucas-athie">
        <img src="https://avatars.githubusercontent.com/u/175664651?v=4" width="220px" style="border-radius: 50%;" />
      </a>
      <br />
      <b>Lucas Athié</b><br />
      Desenvolvedor<br />
      <a href="https://www.linkedin.com/in/lucas-athi%C3%A9/?locale=en_US">LinkedIn</a>
    </td>
  </tr>
</table>

## Contribuição

Sinta-se à vontade para abrir *issues* com sugestões de melhorias, novas métricas de comparação ou otimizações nos modelos.  
Caso deseje desenvolver algo a partir do código disponibilizado aqui, fique à vontade para criar um *fork* deste repositório.
