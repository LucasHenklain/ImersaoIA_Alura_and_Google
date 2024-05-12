# ImersaoIA_Alura_and_Google
Projeto para imersão de inteligência artificial da Alura com a Google, usando IA para melhorar a compreensão das avaliações dos clientes em determinado produto.
# Projeto de Classificação de Texto com Integração à API Gemini

Este é um projeto de classificação de texto, onde um modelo de aprendizado de máquina é treinado para classificar textos em categorias específicas. Além disso, há integração com a API Gemini para obter informações adicionais sobre o texto e enviar feedback.

## Como Usar

1. **Instalação de Dependências**: Certifique-se de ter todas as dependências instaladas. Você pode instalá-las executando o seguinte comando:

    ```
    !pip install -q -U google-generativeai
    !pip install tensorflow scikit-learn nltk
    ```

2. **Configuração da Chave de API Gemini**: Você precisará obter uma chave de API da plataforma Gemini e substituir `"SUA_API_KEY_AQUI"` pelo valor real da sua chave de API no arquivo `main.py`.

3. **Execução do Projeto**: Após instalar as dependências e configurar a chave de API, você pode executar o projeto executando o seguinte comando no terminal:

    ```
    python main.py
    ```

4. **Resultado**: O projeto irá treinar um modelo de classificação de texto, avaliá-lo e demonstrar exemplos de uso da integração com a API Gemini.

## Estrutura do Projeto

- `main.py`: Contém a implementação principal do projeto, incluindo a definição do modelo, treinamento, avaliação e chamadas à API Gemini.
- `README.md`: Este arquivo README que fornece uma visão geral do projeto e instruções básicas de uso.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar uma pull request com melhorias ou correções.
