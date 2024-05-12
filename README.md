![Auxil IA de Contratações](https://github.com/fgcortes/Projeto-da-Imersao-Alura/assets/169413553/a4a267a5-999b-460f-8c95-6740362e0a80)


Autor

Meu nome é Felipe Côrtes, sou Pregoeiro há 8 anos e não tinha conhecimentos sobre programação até o início da Imersão IA Alura + Google.

Objetivo

O Auxil.IA de Contratações é um bot para Telegram especializado em responder perguntas sobre licitações e contratos, com foco na Lei nº 14.133/2021 e nas orientações do Tribunal de Contas da União (TCU). Considerando que a atual lei geral de licitações e contratos é recente e sua aplicação ainda está em amadurecimento nos diversos órgãos públicos, o intuito é ofertar uma ferramenta simples e de fácil acesso para que agentes públicos que atuam na área e fornecedores que pretendem contratar com o governo possam tirar dúvidas rapidamente e sem precisar acessar uma enorme quantidade de leis e acórdãos, favorecendo a efetividade das contratações públicas brasileiras.

Sobre o projeto

O produto nasceu da participação na Imersão IA Alura + Google de 2024, cujos ensinamentos foram fundamentais para o seu desenvolvimento.
A partir das interações com o Gemini via Google AI Studio, realizei o upload dos arquivos PDF da Lei nº 14.133/2021 e da 5ª edição do livro "Licitações e contratos: orientações e jurisprudência do TCU", publicado em dezembro de 2023 pelo Tribunal, com posterior troca de mensagens exemplificativas.
Inseri instruções para que o Gemini agisse como um especialista em licitações e contratos e baseasse suas respostas somente nos materiais que subi para a plataforma.
O modelo generativo escolhido foi o Gemini 1.5 Pro, em razão de sua alta capacidade de geração de respostas consistentes e do tamanho do contexto, relativamente ao tamanho de tokens necessários para processar os arquivos PDF mencionados.
Utilizando o "Get Code" do AI Studio, copiei e colei o código para o Google Colab, onde posteriormente configurei a integração do modelo com o bot do Telegram, criado por meio da interação com o BotFather do Telegram, que já forneceu a chave API utilizada no código.
