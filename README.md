# Cancer Cross Prediction


## **Introduction**

The project aims to assess the possibility of machine learning models trained with a specific type of cancer predicting the 3-year survival after the disease diagnosis for patients with other types. Two analyses were conducted, one using the six most incident types of cancer (skin, breast, prostate, lung, colorectal, and cervical) and another with types related to the digestive system (mouth, oropharynx, esophagus, stomach, small intestine, colorectal, and anus). Metrics were obtained for each type individually and compared with the results obtained when using mixed types to train the models.

## **Introdução**

O projeto visa avaliar a possibilidade de modelos de aprendizado de máquina treinados com um tipo específico de câncer preverem a sobrevida de 3 anos após o diagnóstico da doença para pacientes com outros tipos. Foram conduzidas duas análises, uma utilizando os seis tipos de câncer mais incidentes (pele, mama, próstata, pulmão, colorretal e cervical) e outra com tipos relacionados ao sistema digestivo (boca, orofaringe, esôfago, estômago, intestino delgado, colorretal e ânus). Métricas foram obtidas para cada tipo individualmente e comparadas com os resultados obtidos ao usar tipos mistos para treinar os modelos.

## Como Utilizar

Para começar a usar os recursos deste repositório, siga estas etapas:

1. Clone este repositório para o seu ambiente local usando o comando:

    ```git clone https://github.com/DCD-NSEE/introduction_to_data_science```


2. Abra os notebooks em seu ambiente de desenvolvimento Python, de preferência o [Google Colaboratory](https://research.google.com/colaboratory/), porém pode se usar localmente o [Jupyter Notebook](https://jupyter.org/) ou o [VSCode](https://code.visualstudio.com/).

3. Instale as bibliotecas necessárias no python
   
## Configurando o projeto para rodar

### Criando o ambiente virtual (venv)

#### Windows

```console
python -m venv venv
```

#### Linux

```
virtualenv -p python3.10 venv
```

### Ativando a venv

#### Windows

```console
venv\Scripts\activate
```

#### Linux

```console
source venv/bin/activate
```

### Instalando os pacotes

```console
pip install -e .

pip install -r requirements.txt
```

## Contribuições

Encorajamos contribuições de outros alunos, professores, pesquisadores ou entusiastas da ciência de dados. Se você deseja contribuir com seu próprio conteúdo, correções ou melhorias nos notebooks, siga estas etapas:

1. Faça um fork deste repositório.

2. Faça suas alterações no seu fork.

3. Envie um pull request descrevendo suas alterações e motivos.

## Contato

Se você tiver dúvidas ou precisar de assistência, sinta-se à vontade para entrar em contato com o autor:

Enviar email para [Pedro Mesquita](mailto:pedro.gjmesquita@gmail.com) ou para [Lucas Buk](maailto:lucasbukcardoso@gmail.com).

## **Authors**

* Lucas Buk Cardoso - Instituto Mauá de Tecnologia
* Vanderlei Cunha Parro - Instituto Mauá de Tecnologia
* Jones Egydio - Instituto Mauá de Tecnologia
* Pedro Mesquita - Instituto Mauá de Tecnologia
* Bryan Chin - Instituto Mauá de Tecnologia 
* Adeylson Ribeiro - Fundação Oncocentro de São Paulo
* Maria Paula Curado - A.C. Camargo Cancer Center
* Gisele Fernandes - A.C. Camargo Cancer Center
* Nanci Utida - Faculdade de Saúde Pública da Universidade de São Paulo
* Tatiana Natasha Toporcov - Faculdade de Saúde Pública da Universidade de São Paulo
