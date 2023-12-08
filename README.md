# Fetal Health Classifier 👶🏻

Repositório para o projeto de `detecção de sofrimento fetal` utilizando técnicas de **Inteligência Artificial e Machine Learning**. O foco principal está na análise de dados provenientes de cardiotocografias para prever possíveis situações de risco durante o trabalho de parto.

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

Ao lidar com os dados, o especialista médico desempenha um papel crucial, identificando as características relevantes no exame. A tarefa, neste exercício, é utilizar um conjunto de dados já processado para criar um `modelo preditivo`. Esse modelo deverá vincular as características extraídas do exame com as categorias de classificação, permitindo a previsão do estado do bebê com base nas variáveis monitoradas.
