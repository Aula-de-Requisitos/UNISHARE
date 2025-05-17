
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

Link do Padlet:  https://padlet.com/mateusdejesusg11/unishare-335t022zpks4cmlk

## 1. Introdução

***1.1.  Nome do Grupo***

[Sabrina Cavalcante de Queiroz](https://github.com/Sabrinascq)  
[Mateus de Jesus](https://github.com/IG-jeebas)  
[Janderson Silva](https://github.com/JandersonLSilva)  
[Nelson Meirelles](https://github.com/Nelsonjr-74)  
[Thiago Henrique](https://github.com/thiagohenrique06)  

***1.2.  Nome do Sistema***

UNISHARE

***1.3.  Propósito do Sistema***

O principal propósito do sistema é criar um aplicativo colaborativo voltado para estudantes da UTFPR, que funcione como um repositório de materiais de apoio acadêmico. A ideia é permitir o compartilhamento de conteúdos, além das informações do curso entre os alunos, organizando esses *materiais por professores e por assunto, promovendo assim a troca de recomendações sobre docentes e suas matérias.

***1.2.  Público Alvo***

Este documento se destina aos Alunos da UTFPR.

***1.3. Descrição dos usuários***

Estudantes da UTFPR, cuja dificuldade está na organização e manipulação de arquivos diretamente relacionados às aulas, no armazenamento prático e intuitivo de documentos voltados para fins didáticos e na troca concreta e segura de recomendações sobre docentes e suas disciplinas

***Personas:***

📄 [Persona 1)](Persona.pdf)

***Análise da situação atual: antes da introdução de sua solução***

1. O que as pessoas fazem?
   - Estudantes buscam materiais acadêmicos em diversos canais, como grupos de redes sociais, sites e e-mails compartilhados.  
   - Dependem de recomendações informais para obter informações sobre professores e disciplinas.  
   - Armazenam documentos de maneira desorganizada, muitas vezes dispersos entre dispositivos ou plataformas.  

2. Quais os artefatos envolvidos?
   - Arquivos digitais (PDFs, apresentações, apostilas, anotações).  
   - Plataformas de compartilhamento não estruturadas (WhatsApp, Telegram, Google Drive).  
   - Métodos informais de avaliação de docentes (conversas entre alunos, enquetes).  

3. O que elas precisam saber? 
   - Onde encontrar materiais confiáveis e organizados.  
   - Como trocar informações sobre professores e disciplinas.  
   - Métodos eficazes para armazenar e acessar documentos sem risco de perda ou desorganização.  

***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***
1. O que as pessoas fazem?
   - Utilizam o aplicativo para armazenar, organizar e compartilhar arquivos de maneira intuitiva.  
   - Têm acesso direto a avaliações e recomendações sobre professores e disciplinas.  
   - Encontram materiais categorizados por assunto e docente sem depender de redes informais.  

2.Quais os artefatos envolvidos?
   - Interface do aplicativo UNISHARE.  
   - Banco de dados estruturado com categorias de arquivos e docentes.  
   - Sistema de avaliações e troca de recomendações.  

3.O que elas precisam saber?
   - Como utilizar o aplicativo para upload e download de materiais.  
   - Métodos de classificação e recomendação de docentes.  
   - Como garantir a segurança e privacidade dos arquivos compartilhados.

***Cenário: Antes***

Antes da introdução da solução, os alunos estavam com dificuldades para se situar tanto dentro quanto fora das salas de aula. Devido ao difícil acesso a informações rápidas, simples e objetivas, os alunos ficavam confusos e perdidos em relação à fonte de informações e aos meios de obtê-las. Na maioria das vezes, recorriam a informações desatualizadas ou incoerentes repassadas por outros alunos.

***Cenário: Depois***

Em seguida, em consequência da implantação do nosso sistema, o público-alvo (os alunos) ainda não tinha conhecimento de tal ferramenta. Porém, após um período de divulgações e indicações por professores e pela instituição, os estudantes se familiarizaram com êxito, utilizando e usufruindo do sistema. Isso fez com que suas dúvidas fossem sanadas, a dificuldade para encontrar suas salas fosse praticamente eliminada e, por fim, as respectivas informações fossem recebidas de maneira correta e objetiva.

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

| Identificador | Descrição | Dependente |
| :-: | :- | :-: |
| RF1 | O sistema deve permitir os usuários a busca pelo nome de professor para poder acessar os feedbacks | RF13, RF15 |
| RF2 | O sistema deve permitir os usuários inserir materiais de apoio | RF3 |
| RF3 | O sistema deve permitir que os usuários efetuem o login com RA | RF8 |
| RF4 | O sistema deve permitir aos usuários realizar uma pesquisa de material por matéria | RF14 |
| RF5 | O sistema deve permitir os usuários avaliar os professores | RF3 |
| RF6 | O sistema deve enviar para os usuários notificações personalizadas |  |
| RF7 | O sistema deve permitir os usuários organizar por disciplinas e professores | RF14 |
| RF8 | O sistema deve exigir a criação de um perfil para que os usuários possam enviar os materiais |  |
| RF9 | O sistema deve permitir que os usuários acessem um mapa interativo da UTFPR |  |
| RF10 | O sistema deve permitir a acessibilidade para usuários cegos ou analfabetos |  |
| RF11 | O sistema deve permitir a interação e troca de comentários entre os usuários | RF3 |
| RF12 | O sistema deve permitir aos usuários acessar a área de notícias |  |
| RF13 | O sistema deve permitir o cadastro de professores na base de dados |  |
| RF14 | O sistema deve permitir filtrar professores, disciplinas e materiais |  |
| RF15 | O sistema deve permitir criar feedbacks de professores | RF13 |

***2.2. Requisitos Não Funcionais***

| Identificador | Descrição |
| :-: | :- |
| RNF1 | O sistema deve ser compatível com os sistemas operacionais Android 10 ou superior e com os navegadores Chrome, Firefox e Edge, nas últimas três versões |
| RNF2 | Em caso de falha crítica, o sistema deve ser capaz de restaurar seu funcionamento completo em até 1 hora |
| RNF3 | A navegação entre páginas do sistema deve ter latência inferior a 100ms em redes locais (LAN) e inferior a 300ms em redes móveis (4G ou superior) |
| RNF4 | O sistema deve manter uma identidade visual padronizada (tipografia, cores, espaçamento) com base nas diretrizes da UTFPR, para reforçar a familiaridade institucional |
| RNF5 | O aplicativo móvel deve otimizar o carregamento de imagens e arquivos, priorizando versões compactadas sempre que possível, visando reduzir o consumo de dados móveis |
| RNF6 | O sistema deve suportar no mínimo 1 TB de arquivos acadêmicos no ambiente de produção, com possibilidade de expansão conforme a demanda |
| RNF7 | O sistema deve garantir que informações pessoais de alunos (como nome completo, e-mail e curso) só sejam visíveis a outros usuários com consentimento explícito |
| RNF8 | A plataforma deve suportar pelo menos 5.000 usuários ativos simultaneamente sem impacto crítico no desempenho |
| RNF9 | Uma falha em um módulo (por exemplo, upload de arquivos) não deve comprometer o funcionamento de outros módulos (como busca ou autenticação) |
| RNF10 | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD), garantindo consentimento explícito para uso de dados pessoais e possibilidade de exclusão mediante solicitação |
| RNF11 | O sistema deve ser estruturado de forma que alterações em funcionalidades específicas (ex: sistema de recomendações) possam ser feitas sem impacto nos demais módulos |
| RNF12 | Dados em cache ou arquivos temporários devem ser removidos automaticamente após 7 dias ou após logout do usuário, garantindo economia de armazenamento |

***2.3. Perguntas***
- Como você costuma acessar materiais acadêmicos? Existe alguma dificuldade em encontrá-los rapidamente?
- Você acha fácil encontrar informações sobre professores e disciplinas? Gostaria que houvesse melhorias nesse aspecto?
- Como você avalia sua experiência ao interagir com outros alunos e professores na plataforma da instituição?(Tem retorno no quesito de resposta)
- Você já teve problemas ao utilizar a plataforma da instituição no seu celular ou computador? O que poderia ser melhorado?
- Quando precisa acessar conteúdos  ou realizar buscas, você sente que o sistema responde rapidamente?
- Você costuma utilizar a plataforma em redes móveis (4G, 5G)? O desempenho é satisfatório?
- Você se sente confortável em compartilhar suas informações pessoais dentro da plataforma da instituição?
- Existe alguma funcionalidade relacionada à segurança e privacidade que você acha que poderia ser melhorada?
- Você conhece alguém que tenha dificuldades para usar a plataforma devido a questões de acessibilidade? Como acha que isso poderia ser resolvido?
- O design da plataforma facilita sua navegação ou há pontos confusos que atrapalham sua experiência?
- Se pudesse melhorar a interface da plataforma, o que mudaria para torná-la mais intuitiva?
- Você já passou por alguma instabilidade ou falha no sistema enquanto utilizava a plataforma? Como isso afetou sua rotina acadêmica?
- Em momentos de maior demanda, como períodos de provas, você sente que o sistema continua funcionando bem?
- Se uma funcionalidade falhar (como upload de arquivos), você consegue continuar utilizando outras partes do sistema sem dificuldades, tem outro lugar possível onde possa enviar, manter contato?

***2.4. Entrevista***

*<Arquivo com as respostas do indivíduo entrevistado e link do drive com upload da gravação.>*

***2.5. Histórias do Usuário***

*<Imagem, arquivo (PDF), link com as Histórias de Usuário.>*

***2.6. Diagramas de Caso de Uso e Especificações***

*<Imagem, arquivo (PDF), link com Diagrama de Caso de Uso.>*

***2.7. Diagramas de Atividades***

*<Imagem, arquivo (PDF), link com Diagrama de Atividades.>*

***2.8. Matrizes de Rastreabilidade***

*<Imagem, arquivo (PDF), link com Matriz de Rastreabilidade.>*

***2.9. Protótipos***

*<Imagem, arquivo (PDF), link com Protótipo.>*

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
