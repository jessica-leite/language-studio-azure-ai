# Explorar a fala no portal do Azure AI Foundry - Passo a passo

O serviço de IA do Azure transcreve fala em texto e texto em fala. Você pode usar a IA para criar um aplicativo para transcrever notas de reunião ou gerar um texto
a partir de uma gravação.

Para criar um projeto no portal do Azure AI Foundry:
Abrir o portal do Azure [AI Foundry](https://ai.azure.com) e entre com suas credenciais do Azure. 
Feche todas as dicas ou painéis de início rápido que forem abertos na primeira vez que você entrar.

No navegador, navegue até [Azure - All Resources](https://ai.azure.com/managementCenter/allResources) e selecione Criar. 
Em seguida, escolha a opção para criar um novo recurso do Azure AI Foundry.

No assistente \*Criar um projeto*\, insira um nome para o seu projeto.

Expanda Opções avançadas para especificar as seguintes configurações para o seu projeto:
Assinatura: Sua assinatura do Azure
Grupo de recursos: Crie ou selecione um grupo de recursos
Região: Selecione um dos locais disponíveis.

Após a criação do projeto, você será direcionado para uma página de Visão Geral com os detalhes do projeto.

No menu à esquerda da tela, selecione Playgrounds.

Na página Playgrounds, selecione o bloco Playground de Fala para testar alguns recursos do Azure AI Speech.
Explore a conversão de fala em texto no Speech Playground do Azure AI Foundry
Vamos testar a conversão de fala em texto no Speech Playground do Azure AI Foundry.

Na página \*Fala*\, role para baixo e selecione \*Transcrição*\ em tempo real em \*Experimentar recursos de fala*\. Você será direcionado para o \*Speech Playground*\.

Selecione (https://aka.ms/mslearn-speech-files) para baixar o arquivo speech.zip. Abra a pasta.

Em \*Carregar arquivos*\, selecione Procurar arquivos e navegue até a pasta onde você salvou o arquivo. Selecione WhatAICanDo.m4a e, em seguida, Abrir.

O serviço Speech transcreve e exibe o texto em tempo real. Se você tiver áudio no seu computador, poderá ouvir a gravação enquanto o texto é transcrito.

Revise a saída, que deve ter reconhecido e transcrito o áudio para texto com sucesso.

Limpeza
Excluir os recursos que não precisa mais. Isso evita custos desnecessários.
Abrir o portal do Azure e selecionar o grupo de recursos que contém o recurso que você criou.
Selecione o recurso, selecione Excluir e, em seguida, Sim para confirmar. O recurso será excluído.


# Analisar texto no portal do Azure AI Foundry - Passo a passo

O Processamento de Linguagem Natural (PLN) é um ramo da IA ​​que lida com a linguagem escrita e falada. 
Você pode usar o PNL para criar soluções que extraem significado semântico de texto ou fala, ou que formulam respostas significativas em linguagem natural.

O serviço de Linguagem do Azure AI inclui Análise de Texto, com recursos como reconhecimento de entidades, extração de frases-chave, sumarização e análise de sentimentos. 

No navegador, navegue até https://ai.azure.com/managementCenter/allResources e selecione Criar. Em seguida, escolha a opção para criar um novo recurso do Azure AI Foundry.

No assistente Criar um projeto, insira um nome válido para o seu projeto.

Expanda Opções avançadas para especificar as seguintes configurações para o seu projeto:
Assinatura: Sua assinatura do Azure
Grupo de recursos: Crie ou selecione um grupo de recursos
Região: Selecione um dos seguintes locais disponíveis

Após a criação do projeto, você será direcionado para a página Visão Geral dos detalhes do projeto.

No menu à esquerda da tela, selecione Playgrounds.

Na página Playgrounds, selecione o bloco Playground de Linguagens para testar alguns recursos do Azure AI Language.
Extraia entidades nomeadas com o Azure AI Language no portal do Azure AI Foundry.
Entidades nomeadas são palavras que descrevem pessoas, lugares e objetos com nomes próprios. 
Vamos usar o recurso de extração de entidades nomeadas do Azure AI Language para identificar tipos de informações em uma análise.

No Playground de Linguagens, selecione Extrair informações. Em seguida, selecione o bloco Extrair entidades nomeadas.

Em Amostra, copie e cole a seguinte análise:
Selecione Executar. Analise a saída. Observe na seção Detalhes como as entidades extraídas vêm com informações adicionais, como tipo e pontuações de confiança. 
A pontuação de confiança representa a probabilidade de o tipo identificado realmente pertencer a essa categoria.
Extraia frases-chave com a Linguagem de IA do Azure no portal do Azure AI Foundry
Frases-chave são as informações mais importantes em um texto. Vamos usar o recurso de extração de frases-chave da Linguagem de IA do Azure 
para extrair informações importantes de uma avaliação.

No playground de idiomas, selecione "Extrair informações". Em seguida, selecione o bloco "Extrair frases-chave".

Em "Exemplo", copie e cole a seguinte avaliação:

Selecione "Executar". Revise a saída. Observe as diferentes frases extraídas na seção "Detalhes". Essas frases devem contribuir mais para o significado do texto.

Resuma o texto com a Linguagem de IA do Azure no portal do Azure AI Foundry
Vamos analisar os recursos de sumarização da Linguagem de IA do Azure. No playground de idiomas, selecione "Resumir informações" e, em seguida, selecione o bloco "Resuma texto".

Em "Exemplo", copie e cole a seguinte avaliação:
Selecione Executar. Revise a saída. Observe que o Resumo extrativo em Detalhes fornece pontuações de classificação para as frases mais relevantes.

Limpeza
Exclua os recursos que não precisa mais. Isso evita custos desnecessários.

Abra o portal do Azure em (https://portal.azure.com) e selecione o grupo de recursos que contém os recursos que você criou.

Selecione os recursos, selecione Excluir e, em seguida, Sim para confirmar. Os recursos serão excluídos.

