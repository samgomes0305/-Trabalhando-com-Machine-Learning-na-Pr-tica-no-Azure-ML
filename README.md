# Azure Machine Learning Automated ML - README

Este repositório fornece um guia passo a passo para explorar o Machine Learning Automatizado no Azure Machine Learning. Neste exercício, você aprenderá a criar um espaço de trabalho do Azure Machine Learning, treinar e avaliar um modelo de aprendizado de máquina usando Automated ML, e, finalmente, implantar e testar o modelo treinado.

## Requisitos

Antes de começar, certifique-se de ter os seguintes requisitos:

- Uma assinatura ativa do Azure.
- Credenciais da Microsoft para acessar o portal do Azure.
- Acesso ao [Azure Machine Learning Studio](https://ml.azure.com/).

## Passo a Passo

### 1. Crie um espaço de trabalho do Azure Machine Learning

- Acesse o [portal do Azure](https://portal.azure.com/) utilizando suas credenciais da Microsoft.
- Selecione "+ Criar um recurso", pesquise por "Machine Learning" e crie um novo recurso do Azure Machine Learning, fornecendo as configurações necessárias.

### 2. Abra o Azure Machine Learning Studio

- Após a criação do espaço de trabalho, selecione "Launch Studio" no portal do Azure ou acesse [https://ml.azure.com](https://ml.azure.com) utilizando suas credenciais da Microsoft.

### 3. Use Automated ML para treinar um modelo

- Dentro do Azure Machine Learning Studio, navegue até a página "Automated ML" em Authoring.
- Crie um novo trabalho de ML automatizado, seguindo as configurações especificadas no guia. Este passo envolve a seleção de um conjunto de dados, configuração de tarefa de aprendizado de máquina, e outras opções essenciais.

### 4. Avalie o melhor modelo

- Após a conclusão do trabalho automatizado de aprendizado de máquina, reveja o resumo do melhor modelo treinado na guia "Visão geral do trabalho automatizado de aprendizado de máquina".
- Explore as métricas e gráficos residuais para avaliar o desempenho do modelo.

### 5. Implante e teste o modelo

- Na guia "Modelo" do melhor modelo treinado, selecione "Implantar" e use a opção de serviço Web para implantar o modelo com configurações específicas.
- Aguarde a conclusão da implantação e teste o serviço implantado utilizando a guia "Teste".

### Limpeza

- Para evitar cobranças desnecessárias no Azure, exclua o ponto de extremidade do serviço web após a conclusão dos testes.
- Se não pretender continuar explorando o Azure Machine Learning, exclua o espaço de trabalho e os recursos associados no portal Azure.

**Observação:** Certifique-se de revisar e entender todas as configurações e opções fornecidas durante o exercício, adaptando-as conforme necessário com base nas suas necessidades específicas.
