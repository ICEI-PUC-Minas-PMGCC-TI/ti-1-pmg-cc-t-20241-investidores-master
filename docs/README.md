# Documentação do Projeto (TIDocs)

Esta pasta armazena a documentação do projeto para a disciplina de **Trabalho Interdisciplinar 1** dos cursos de Tecnologia da Informação da **[PUC Minas](https://pucminas.br)**. Essa documentação é estruturada na forma de um site que fica disponível por meio do GitHub Pages e pode ser incluído, também, no site da solução hospedada. Um [exemplo publicado do TIDocs](https://webtech-puc-minas.github.io/ti1-template/) está disponível por meio do repositório do **[WebTech PUC Minas](https://github.com/webtech-pucminas)**.

A documentação do projeto inclui as seguintes seções:

1. Introdução
2. Contexto
3. Concepção
4. Metodologia
5. Solução
6. FAQ (Questões frequentes)
7. Referências Bibliográficas

O template para o site é estruturado e permite que a equipe evolua a documentação do projeto à medida que avance no desenvolvimento.

# Orientações gerais

Esta seção traz explicações breves sobre o conjunto de artefatos que precisam ser incluídos na documentação do projeto com uma conjunto de links importantes para que se entenda como criar cada coisa. 

## Problema

Um dos principais problemas decorrentes dessa prática é a oferta de produtos financeiros que não necessariamente se alinham com o perfil de risco e os objetivos de investimento dos clientes. Essas recomendações tendenciosas frequentemente incluem a promoção de fundos de investimento com gestão duvidosa ou taxas excessivamente altas, bem como outros instrumentos financeiros que não oferecem o melhor retorno ajustado ao risco para os investidores. Isso resulta em uma alocação de recursos ineficiente e, em muitos casos, em prejuízos financeiros significativos para os clientes. 

## Objetivos

Diante desse cenário, o objetivo do projeto é desenvolver uma solução que ofereça aos investidores acesso a recomendações imparciais e personalizadas, levando em consideração seus objetivos financeiros, tolerância ao risco e situação financeira atual.  

## Justificativa

A falta de transparência e de orientação imparcial por parte das corretoras pode levar os investidores a tomarem decisões baseadas em informações incompletas ou tendenciosas, aumentando ainda mais o risco de escolhas financeiras inadequadas. Assim, uma plataforma de investimentos automatizada pode desempenhar um papel fundamental na resolução desse problema, fornecendo uma alocação de portfólio teoricamente otimizada e transparente, livre de conflitos de interesse e alinhada com os interesses dos investidores. 

## Público-Alvo

O público-alvo desta solução são os investidores em busca de orientação financeira imparcial e personalizada, que buscam maximizar seus retornos financeiros de acordo com seus objetivos e tolerância ao risco e investidores novatos que estão começando a aprender sobre o mundo dos investimentos. 

## Personas

Eu como persona...    Quero/preciso...               Para... 

Arthur                Informações confiáveis         Conseguir investir por mim mesmo no futuro 

Arthur                 Local de gestão                Para ter de maneira clara se estou atingindo minhas metas 

Walter                 Facil acesso                   Para conseguir utilizar a plataforma em ajuda 

Cristina               Sistema de autenticação       Confiar meu dinheiro na plataforma 

Cristina               Boas recomendações            Para aumentar meu patrimônio 

## Histórias de Usuários

Arthur
“Me chamo Arthur, tenho 23 anos, sou estudante e trabalho como estagiário e recebo um salário
mínimo por mês. Me juntei a InvestGO após um amigo próximo me recomendar o site alegando ser
um ótimo lugar para adquirir informações e conhecimento de qualidade. Meu objetivo como usuário
da InvestGO é conquistar minha liberdade financeira construindo uma vida financeira sólida e
saudável a longo prazo que me permita ter uma certa flexibilidade na vida.”

Walter
“Me chamo Walter, tenho 65 anos e sou aposentado. Meu hobby favorito é cuidar das minhas
plantas e, agora que tenho muito tempo livre, estou fazendo isso a maior parte do dia. Conheci a
InvestGO por meio de uma notícia que li no jornal, que dizia ser uma das melhores plataformas para
adquirir informações e conhecimento sobre investimentos. Meu objetivo como usuário da InvestGO
é deixar uma quantia significativa para meus filhos e netos quando eu partir, não renunciando a uma
renda passiva para pagar meus remédios e futuros médicos.”

Cristina
“Me chamo Cristina, tenho 29 anos, sou confeiteira e possuo uma dívida com o banco. Tive contanto
com o InvestGO, através da internet quando estava pesquisando sobre como ter uma renda maior.
Meu objetivo como usuário da InvestGO é pagar completamente minha dívida e crescer meu negócio
e comprar uma loja física para os meus produtos.”

## Requisitos

Requisitos Funcionais  

 RF-001 Perfil do usuário: (Alta) 

O sistema deve permitir que os usuários criem e personalizem seus perfis, incluindo informações como idade, ocupação, objetivos financeiros e tolerância ao risco.  

RF-002 Avaliação do perfil de investimento: (Alta) 

O sistema deve realizar uma avaliação abrangente do perfil de investimento de cada usuário, levando em consideração fatores como idade, renda, objetivos financeiros e aversão ao risco.  

RF-003 Recomendações personalizadas: (Alta) 

Com base na avaliação do perfil do usuário, o sistema deve gerar recomendações de investimento personalizadas, alinhadas com os objetivos financeiros e a tolerância ao risco de cada usuário.  

RF-004 Acesso a informações e conhecimento: (Baixa) 

A plataforma deve fornecer acesso a informações e conhecimentos relevantes sobre investimentos, adequados ao nível de compreensão e experiência de cada usuário.  

RF-005 Monitoramento e atualização de investimentos: (Média) 

Os usuários devem poder monitorar o desempenho de seus investimentos e receber atualizações regulares sobre suas carteiras, permitindo ajustes conforme necessário.  

RF-006 Transparência e imparcialidade: (Alta) 

O sistema deve garantir transparência e imparcialidade em suas recomendações, evitando conflitos de interesse e priorizando os interesses financeiros dos usuários.  

RF-007 Suporte ao cliente: (Alta) 

Deve haver um canal de suporte ao cliente disponível para esclarecer dúvidas, fornecer assistência técnica e orientação sobre o uso da plataforma.  

Requisitos Não Funcionais  

RNF-001 Segurança de dados: (Alta) 

Todos os dados dos usuários devem ser armazenados de forma segura e protegidos contra acesso não autorizado, seguindo as melhores práticas de segurança da informação.  

RNF-002 Desempenho escalável: (Média) 

A plataforma deve ser capaz de lidar com um aumento significativo no número de usuários sem comprometer o desempenho, garantindo uma experiência fluida mesmo em momentos de alta demanda.  

RNF-003 Disponibilidade e confiabilidade: (Alta) 

A plataforma deve ter uma alta disponibilidade, com tempos de inatividade mínimos planejados para manutenção. Além disso, deve ser confiável, minimizando falhas e erros inesperados.  

RNF-004 Compatibilidade multiplataforma: (Média) 

A solução deve ser compatível com uma variedade de dispositivos e navegadores web, garantindo uma experiência consistente e adequada em diferentes ambientes de uso.  

RNF-005 Usabilidade e acessibilidade: (Média) 

A interface do usuário deve ser intuitiva e de fácil utilização, com ênfase na acessibilidade para usuários com necessidades especiais, seguindo as diretrizes de acessibilidade da web.  

RNF-006 Manutenibilidade e extensibilidade: (Média) 

O código-fonte e a arquitetura da plataforma devem ser bem documentados e modularizados, facilitando a manutenção e permitindo futuras extensões e atualizações.  

RNF-007 Performance do sistema: (Média) 

A resposta do sistema às solicitações dos usuários deve ser rápida e eficiente, minimizando o tempo de carregamento de páginas e atrasos nas operações.  

RNF-008 Compliance regulatório: (Alta) 

A solução deve estar em conformidade com todas as regulamentações e leis pertinentes relacionadas à proteção de dados, segurança financeira e práticas comerciais justas.  

RNF-009 Integração com sistemas externos: (Alta) 

O sistema deve ser capaz de integrar-se facilmente com sistemas externos, como APIs de instituições financeiras e ferramentas de análise de mercado, para enriquecer suas funcionalidades e dados disponíveis.  
## User Flow

https://lucid.app/lucidchart/153a95ce-d81b-4bba-b12b-5feb6066aeff/edit?page=0_0&invitationId=inv_9403e55b-cd4a-42cc-af68-914551320137

## Wireframes

https://lucid.app/lucidchart/82d82a48-2a80-4e9b-853e-e5b4abaaf50b/edit?viewport_loc=502%2C-10%2C681%2C743%2CI5_Pk22Ve1Oe&invitationId=inv_b5ed8806-5647-4d9f-bbe9-7f22e7ec6090 

## Gestão de Projetos

 Scrum Master: Pedro Gabriel Amorim Soares 

Product owner: André Henriques Parreiras 

Desenvolvedores: André Henriques, Mateus Martins, Pedro Gabriel Amorin, Vitor Leite 

Documentações: Mateus Martins Parreiras e Vitor Leite Setragni 
