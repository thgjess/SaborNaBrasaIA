# SaborNaBrasaIA

# Uso de Inteligência Artificial para controle de estoque e redução de desperdício em lanchonete local

Este projeto foi desenvolvido como atividade de extensão universitária para a disciplina de **Inteligência Artificial para Devs** do curso de Análise e Desenvolvimento de Sistemas (Estácio).

## Objetivo do Projeto
O sistema utiliza algoritmos de Machine Learning para analisar o histórico de vendas de uma lanchonete local e prever a demanda futura de insumos (Marmitas Executivas e Caldos). A solução visa mitigar a imprevisibilidade de vendas diárias, otimizar as compras de ingredientes e reduzir o desperdício de alimentos perecíveis em uma microempresa instalada na comunidade.

## Tecnologias Utilizadas
- **Python 3** (Linguagem principal)
- **Pandas & NumPy** (Manipulação, mapeamento e tratamento de dados)
- **Scikit-Learn** (Treinamento do modelo preditivo através do algoritmo *RandomForestRegressor*)
- **Matplotlib** (Visualização e geração de gráficos de projeção)

## Estrutura do Repositório
- `historico_vendas_trimestre_1.xlsx`: Base de dados comercial bruta contendo o histórico de vendas coletado na fase de diagnóstico (Janeiro a Março de 2026).
- `codigo_ia_ouroquest.ipynb`: Notebook com o código-fonte completo contendo o pipeline de dados, treinamento da IA, geração de gráficos e o módulo de consulta interativa.

## Como Rodar o Projeto
1. Faça o download do arquivo `historico_vendas_trimestre_1.xlsx` e do script `.ipynb`.
2. Abra o script no ambiente do **Google Colab**.
3. No painel de arquivos lateral do Colab, realize o upload da planilha `.xlsx`.
4. Vá em *Ambiente de Execução > Executar tudo* para treinar o modelo e visualizar os gráficos de demanda.
