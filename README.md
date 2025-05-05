# Integração Gemini com NodeJS

Este projeto consiste em uma implementação da API do modelo Gemini utilizando NodeJS.
As funcionalidades implementadas incluem:

• Chat: Interface para interação conversacional com o modelo.
• Leitura de Imagem: Capacidade de processar e extrair informações de conteúdo visual.
• Análise de Sentimentos: Módulo para identificar e classificar o sentimento expresso em textos.


## Pré-requisitos

* **NodeJS:** Certifique-se de ter o NodeJS instalado em sua máquina. Você pode baixá-lo em [https://nodejs.org/](https://nodejs.org/).
* **Conta Google Cloud:** Você precisará de uma conta no Google Cloud Platform (GCP) e um projeto configurado.
* **API Key do Gemini:** Você precisará gerar uma chave de API para acessar o modelo Gemini. Siga a documentação oficial do Google Cloud para criar uma chave de API.


## Configuração

1.  Crie uma variável de ambiente no seu computador com a chave da API do Gemini (Sugestão para o nome da chave: GEMINI_API_KEY).
2.  Execute o projeto com o node: ``node index.js``


## Comentários

Para realizar a integração com a API do Gemini do 0, você vai precisar realizar as seguintes tarefas:

• Criar um projeto com Node.js;
• Instalar no projeto a dependência do generative-ai usando o comando `npm install @google/generative-ai`;
• Criar uma chave de API no Google AI Studio e armazene em uma variável de ambiente.
• Criar no projeto o arquivo pergunta.js com a função para leitura do teclado;
• Criar no projeto o arquivo index.js com a lógica de integração com a API;


### Referências
[Documentação Gemini] (https://ai.google.dev/gemini-api/docs/get-started/tutorial?lang=node&hl=pt-br)