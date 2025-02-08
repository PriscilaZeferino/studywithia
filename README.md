# Documentação resumida

## Como surgiu a ideia?
No final de 2023, participei do NLW IA, um evento da Rocketseat para criar projetos com IA em 3 dias. Durante o evento, aprendi a usar IA para transcrever vídeos e gerar títulos. 
Isso me fez refletir sobre como aplicar o conhecimento adquirido. Enquanto estudava para uma prova usando o ChatGPT, percebi a dificuldade de manter um fluxo 
contínuo na geração de perguntas e respostas. Para resolver isso, surgiu a ideia do study.ia, uma plataforma para auxiliar nesse processo.

## A ideia inicial
A ideia inicial era criar uma aplicação completa usando IA para gerar perguntas e avaliar respostas, incluindo a documentação do projeto. 
Para isso, utilizei as tecnologias do NLW IA, focando na implementação com IA. O front-end foi desenvolvido com React, TypeScript, Vite, Tailwind e Shadcn UI, 
enquanto o back-end usou Node, TypeScript e Prisma. Inicialmente, não planejava divulgar o projeto publicamente, mas acabei compartilhando com algumas pessoas 
ao longo do desenvolvimento.

## Sobre o design
Para acelerar o desenvolvimento, escolhi o shadcn.ui, mas ainda precisava de uma estrutura visual clara para mapear os elementos do projeto. 
Desenvolvi algumas telas e iniciei o projeto, seguindo um fluxo de design e implementação por páginas. No entanto, esse método não funcionou tão bem. 
As telas ficaram funcionais, mas não me agradaram muito. Decidi refazer o layout no futuro, pois precisei focar em outros problemas. 
Curiosamente, agora vejo que ele não está tão ruim, só precisa de alguns ajustes. 

Veja só: [Design inicial aqui](https://www.figma.com/design/D3jLpTAqOVsJDI4TCOrCiJ/Untitled?node-id=0-1&node-type=canvas&t=EfxoIFCJhOCnNrAM-0)

## Inicio do desenvolvimento e problemas encontrados

Durante o desenvolvimento, além dos desafios com o design, enfrentei dificuldades para separar as perguntas como queria, o que me travou por um tempo. 
Depois, meus créditos da OpenAI API expiraram. Como a reposição era em dólar e eu tinha outras prioridades, precisei pausar o projeto.

## Novas descobertas
Algum tempo depois, descobri que a API do Gemini oferece um plano gratuito e, aparentemente, conexão com a internet, o que achei interessante. 
Isso permitiria continuar o projeto sem grandes custos, mas exigiria a reestruturação de parte do código.

## Documentação e sua organização

Além dos problemas encontrados, eu tinha uma documentação básica com o objetivo do projeto, objetivos específicos, requisitos funcionais e não funcionais, e também coisas que o projeto não abordaria. 
Havia uma separação de tarefas, mas não estava bem organizada de forma visual, o que não me agradava muito. Então, comecei a reescrever a documentação, melhorando a organização,
para disponibilizá-la junto ao projeto study.ia no GitHub. Vou dividir a documentação por páginas, criando um sumário principal para facilitar o acesso. Essa divisão ficará mais clara
na documentação detalhadas.

## Funcionalidades basicas iniciais
- Definir tópicos específicos para estudo
- Gerar perguntas aleatórias utilizando ia com base no tópico definido
- Permitir que os usuários respondem essas perguntas
- Obter Feedback personalizados sobre as respostas das perguntas
- Leitura de um arquivo do usuário para focar nas perguntas específicas:

## Requisitos funcionais e não funcionais

**Requisitos funcionais**

1. **Definir tópicos específicos de estudo**
    Os usuários devem poder criar tópicos de estudo.
    Os tópicos devem ter um nome descritivo
    
2. **Gerar perguntas aleatórias utilizando IA com base no tópico definido:**
    Os usuários devem poder selecionar um tópico específico para gerar perguntas.
    O sistema deve fazer solicitações à API do ChatGPT para gerar perguntas relacionadas ao tópico escolhido.
    
3. **Permitir que os usuários respondam a essas perguntas:**
    Os usuários devem poder selecionar e responder às perguntas geradas.
    Os usuários devem receber feedback após responderem a pergunta.
    
4. **Obter Feedback personalizados sobre as respostas das perguntas:**
    O sistema deve fornecer feedback personalizado com base nas respostas dos usuários.
    O feedback deve incluir informações sobre a precisão da resposta e explicações relevantes, se necessário.
    
5. **Opção de Upload de Arquivo com Tópicos ou Textos Específicos:**
    O sistema deve ser capaz de extrair os tópicos ou questões relevantes do arquivo carregado.
    As perguntas geradas devem ser baseadas nos tópicos ou questões extraídas do arquivo do usuário.
    
6. **Geração de Perguntas com Base nos Tópicos ou Questões Extraídas do Arquivo do Usuário:**
    As perguntas geradas devem ser baseadas nas respostas da API do ChatGPT, que por sua vez são baseadas nos tópicos ou questões extraídas do arquivo do usuário.
    
**Requisitos não funcionais**

- **Acessibilidade:** o sistema deve ser acessível para pessoas com deficiências, atendendo a padrões de acessibilidade, como WCAG.
- **Suporte a Idiomas:** o sistema deve ser acessível em inglês e português.

## Por que estou colocando isso aqui e não no outro repositório study.ia?
Estou recomeçando o projeto study.ia do zero neste novo repositório, pois o projeto original ficou obsoleto e com dificuldades técnicas que não consegui resolver de forma eficiente.
Embora tenha sido um bom ponto de partida, quero aplicar mudanças drásticas na organização e nas tecnologias.
O repositório antigo será mantido como um arquivo de estudo, pois contém ideias úteis que podem ser aproveitadas futuramente. 
Além disso, quero documentar o processo de forma mais organizada para acompanhar a evolução do projeto e compartilhar os aprendizados de maneira mais clara.

Obs: o outro repositório está publico, se quiser, visitá-lo.

# Documentação detalhada
[Clique aqui](https://clear-myth-de2.notion.site/STUDY-IA-em-desenvolvimento-19438f37744a8108a6d3d9d4e1c456a6) para visualizar uma documentação detalhada sobre todo o processo
