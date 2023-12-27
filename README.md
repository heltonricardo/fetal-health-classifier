# Fetal Health Classifier 👶🏻

Repositório para o projeto de `detecção de sofrimento fetal` utilizando técnicas de **Inteligência Artificial e Machine Learning** com o auxílio de **Keras e TensorFlow**. O foco principal está na análise de dados provenientes de cardiotocografias para prever possíveis situações de risco durante o trabalho de parto.

## 🌐 Contextualização

O termo `sofrimento fetal` refere-se a situações críticas durante o trabalho de parto, nas quais o bebê está em risco de vida. A `cardiotocografia` é o exame central neste contexto, assemelhando-se a um eletrocardiograma, mas destinado a monitorar o batimento cardíaco do feto e diversas variáveis relacionadas às contrações uterinas da gestante.

A cardiotocografia desempenha um papel crucial em gestações de risco, detectando momentos de sofrimento fetal. **Quando identificado, este quadro demanda uma ação imediata**, frequentemente resultando em cesariana para preservar a vida do bebê e da gestante.

Além do aspecto clínico, a `cardiotocografia é amplamente utilizada em situações de gestação de risco`, inclusive na rede pública de saúde. Sua aplicação preventiva visa reduzir a mortalidade infantil e materna, tornando-se uma ferramenta valiosa para profissionais de saúde.

## 📊 Classes de classificação e dataset

No contexto do problema, cada leitura da cardiotocografia é classificada em uma das três categorias a seguir, sendo fundamental para a tomada de decisão clínica:

- `normal`: estado apropriado, dentro dos parâmetros esperados;
- `suspeito`: indicando possível sofrimento fetal iminente;
- `patológico`: indicando que o bebê está em sofrimento fetal.

## 🛠️ Abordagem na resolução do problema

Ao lidar com os dados, o especialista médico desempenha um papel crucial, identificando as características relevantes no exame. A tarefa, neste exercício, é utilizar um conjunto de dados já processado para criar um `modelo preditivo`. Esse modelo deverá vincular as características extraídas do exame com as categorias de classificação, permitindo a previsão do estado do bebê com base nas variáveis monitoradas. Para isso, utilizaremos a biblioteca Keras em conjunto com o TensorFlow.

## 🔐 Configuração de segredos

Para que a pipeline do projeto funcione corretamente, é necessário configurar os seguintes segredos no repositório do GitHub. Esses segredos são utilizados para diversas finalidades, como autenticação, controle de acesso e integração contínua. Aqui estão os segredos necessários, com pequenas descrições:

| Nome                     | Descrição                                         |
| ------------------------ | ------------------------------------------------- |
| DOCKER_IMAGE_NAME        | Nome da imagem Docker utilizada no projeto.       |
| DOCKER_PASSWORD          | Senha de acesso ao registro Docker.               |
| DOCKER_USER              | Nome de usuário do registro Docker.               |
| MLFLOW_TRACKING_MODEL    | URI de rastreamento do MLflow para o modelo.      |
| MLFLOW_TRACKING_PASSWORD | Senha de autenticação para o rastreamento MLflow. |
| MLFLOW_TRACKING_URI      | URI para o rastreamento do MLflow.                |
| MLFLOW_TRACKING_USERNAME | Nome de usuário para autenticação MLflow.         |

> Para obter os valores necessários para os segredos, é preciso criar contas em duas plataformas essenciais:
>
> [Docker Hub](https://hub.docker.com/) é uma plataforma para construção e compartilhamento de containers Docker. Registre-se para obter as credenciais necessárias.
>
> [Dagshub](https://dagshub.com/) é uma plataforma para gerenciamento de modelos de machine learning. Crie uma conta para obter as credenciais necessárias para rastreamento com o MLflow.

Créditos: [Professor Renan Santos](https://github.com/renansantosmendes)
