# Matriz-de-Compet-ncias-em-Engenharia-de-Software-
Tradução da Matriz de Competências em Programação de Sijin Joseph. A original pode ser encontrada[aqui]: https://sijinjoseph.com/programmer-competency-matrix/ .

| Ciência da Computação   | 2n (Nível 0)                                                 | n2 (Nível 1)                                                 | n (Nível 2)                                                  | log(n) (Nível 3)                                             | Comentários |
| ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------- |
| Estruturas de Dados     | Não sabe a diferença entre o Array e o LinkedList            | Capaz de explicar e usar Arrays, LinkedLists, Dicionários, etc. em tarefas práticas de programação | Conhece os tradeoffs de espaço e tempo das estruturas de dados básicos, Arrays vs LinkedLists, Capaz de explicar como os hashtables podem ser implementados e sabe como lidar com colisões, filas prioritárias e formas de implementá-los, etc. | Conhecimento de estruturas de dados avançadas como árvores binárias, pilhas de binômio e fibonacci, árvores AVL/Red Black, Splay Trees, Skip Lists, tries, etc. |             |
| Algoritmos              | Incapaz de encontrar a média dos números em uma série (é difícil de acreditar, mas já entrevistei tais candidatos) | Algoritmos básicos de triagem, busca e estrutura de dados de travessia e recuperação de dados | Árvore, Gráfico, simples algoritmos míopes e de dividir e conquistar, é capaz de entender a relevância dos níveis desta matriz. | Capaz de reconhecer e codificar soluções de programação dinâmica, bom conhecimento de algoritmos gráficos, bom conhecimento de algoritmos de computação numérica, capaz de identificar problemas NP etc. |             |
| Programação de Sistemas | Não sabe o que é um compilador, linker ou interpreter        | Conhecimento básico de compiladores, linkers e interpreters. Compreende o que é código assembly e como as coisas funcionam no nível do hardware. Algum conhecimento sobre memória virtual e paginação. | Compreende modo kernel vs. modo usuário, multithreading, primitivas de sincronização e como elas são implementadas, capaz de ler código assembly. Entende como funcionam redes, compreensão dos protocolos de rede e programação em nível de socket. | Compreende toda o stack de programação, hardware (CPU + Memória + Cache + Interrupts + microcódigo), código binário, montagem, ligação estática e dinâmica, compilação, interpretação, compilação JIT, coleta de lixo, heap, stack, endereçamento de memória... |             |

| Engenharia de Software                    | 2n (Nível 0)                                       | n2 (Nível 1)                                                 | n (Nível 2)                                                  | log(n) (Nível 3)                                             | Comentários |
| ----------------------------------------- | -------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------- |
| Controle de Versionamento do Código Fonte | Cópias de segurança de pastas por data             | VSS e usuário iniciante de CVS/SVN                           | Proficiente no uso de recursos CVS e SVN. Sabe como ramificar e fundir, usar as propriedades do repositório de configuração de patches, etc. | Conhecimento de sistemas VCS distribuídos. Experimentou Bzr/Mercurial/Darcs/Git |             |
| Automação de Build                        | Só sabe fazer build a partir da IDE                | Sabe como fazer build a partir da linha de comando           | Pode configurar um roteiro para fazer build do sistema básico | Pode configurar um script para fazer build do sistema e também documentação, instaladores, gerar notas de lançamento e etiquetar o código no source control |             |
| Automação de Testes                       | Pensa que todos os testes são trabalho do testador | Tem testes unitários automatizados por escrito e apresenta bons casos de teste unitário para o código que está sendo escrito | Tem código escrito de maneira TDD                            | Compreende e é capaz de configurar testes funcionais automatizados, de carga/desempenho e de Interface de Usuário |             |

| Programação                                      | 2n (Nível 0)                                                 | n2 (Nível 1)                                                 | n (Nível 2)                                                  | log(n) (Nível 3)                                             | Comentários                                                  |
| ------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Decomposição de Problemas                        | Somente código de linha reta com pasta de cópia para reutilização | Capaz de dividir o problema em múltiplas funções             | Capaz de criar funções/objetos reutilizáveis que resolvam o problema geral | Uso de estruturas de dados e algoritmos apropriados e vem com um código genérico/objetivo que encapsula aspectos do problema que estão sujeitos a mudanças. |                                                              |
| Decomposição de Sistemas                         | Não consegue pensar acima do nível de um único arquivo/classe | Capaz de romper o espaço do problema e de projetar a solução, desde que dentro da mesma plataforma/tecnologia | Capaz de projetar sistemas que abrangem múltiplas tecnologias/plataformas. | Capaz de visualizar e projetar sistemas complexos com múltiplas linhas de produtos e integrações com sistemas externos. Também deve ser capaz de projetar sistemas de apoio às operações, como monitoramento, relatórios, falhas, etc. |                                                              |
| Comunicação                                      | Não é possível expressar pensamentos/ideias aos colegas. Má ortografia e gramática. | Os colegas podem entender o que está sendo dito. Boa ortografia e gramática. | É capaz de se comunicar efetivamente com os colegas          | Capaz de compreender e comunicar pensamentos/design/ideas/especções de forma inequívoca e ajusta a comunicação de acordo com o contexto | Este é um critério frequentemente subestimado, mas muito crítico para julgar um programador. Com o aumento da terceirização das tarefas de programação para lugares onde o inglês não é a língua nativa, esta questão se tornou mais proeminente. Sei de vários projetos que falharam porque os programadores não conseguiam entender qual era a intenção da comunicação. |
| Organização de Código em Arquivo Único           | nenhuma evidência de organização dentro de um arquivo        | Métodos agrupados logicamente, ou por acessibilidade         | O código é agrupado em regiões e bem comentado com referências a outros arquivos fonte | O arquivo tem cabeçalho de licença, resumo, bem comentado, uso consistente do espaço em branco. O arquivo deve ficar bonito. |                                                              |
| Organização de Código Através de Vários Arquivos | Não pensa em organizar o código através de arquivos          | Os arquivos relacionados são agrupados em uma pasta          | Cada arquivo físico tem uma finalidade única, por exemplo, uma definição de classe, uma implementação de recurso, etc. | A organização do código em um nível físico corresponde estreitamente ao projeto e a análise dos nomes dos arquivos e da distribuição de pastas fornece informações sobre o projeto |                                                              |
| Organização de Sourcetree                        | Tudo em uma pasta                                            | Separação básica do código em pastas lógicas.                | Sem dependências circulares, binários, bibliotecas, documentos, builds, código de terceiros, tudo organizado em pastas apropriadas | A disposição física da árvore de origem corresponde à hierarquia lógica e organização. Os nomes dos diretórios e a organização fornecem informações sobre o design do sistema. | A diferença entre este e o item anterior está na escala de organização, a organização da árvore de origem está relacionada com todo o conjunto de artefatos que definem o sistema. |
| Legibilidade do Código                           | Nomes monossílabos                                           | Bons nomes para arquivos, classes de variáveis, métodos, etc. | Sem funções longas, comentários explicando código incomum, correção de erros, suposições de código | As suposições de código são verificadas através de afirmações, o código flui naturalmente - não há nesting profundo de condicionais ou métodos |                                                              |
| Programação Defensiva                            | Não entende o conceito                                       | Verifica todos os argumentos e afirma suposições críticas em código | Certifica-se de verificar os valores de retorno e verificar as exceções em torno do código que podem falhar. | Tem sua própria biblioteca para ajudar na codificação defensiva, escreve testes unitários que simulam falhas |                                                              |
| Tratamento de Exceções                           | Só sabe escrever código orientado ao 'happy case'            | Tratamento básico de erros ao redor do código que pode lançar exceções/gerar erros | Assegura que erros/exceções deixam o programa em bom estado, os recursos, as conexões e a memória estejam todos limpos adequadamente | Códigos para detectar possíveis exceções antes, manter uma estratégia consistente de tratamento de exceções em todas as camadas de código, apresentar diretrizes sobre o tratamento de exceções para todo o sistema. |                                                              |
| IDE                                              | Utiliza principalmente IDE para edição de texto              | Conhece a interface, capaz de usar efetivamente a IDE usando menus. | Conhece atalhos de teclado para a maioria das operações utilizadas. | Já escreveu macros personalizadas                            |                                                              |
| API                                              | Precisa consultar a documentação com frequência              | Tem as APIs mais frequentemente utilizadas na memória        | Vasto e profundo conhecimento do API                         | Tem bibliotecas escritas que ficam em cima do API para simplificar as tarefas freqüentemente utilizadas e para preencher as lacunas do API | Por exemplo, a API pode ser a biblioteca Java, a estrutura .net ou a API personalizada para a aplicação |
| Frameworks                                       | Não utilizou nenhuma framework fora da plataforma central    | Já ouviu falar mas não utilizou as frameworks populares disponíveis para a plataforma. | Utilizou mais de uma framework em uma capacidade profissional e é bem versado com os idiomas das frameworks. | Autor da framework.                                          |                                                              |
| Requisitos/Especificações de Projeto             | Escreve código que atende os requisitos e especificações     | Fazer perguntas sobre casos perdidos nas especificações      | Compreende a visão geral e encontra áreas inteiras que precisam ser especuladas | Capaz de sugerir melhores alternativas e fluxos para determinadas exigências com base na experiência |                                                              |
| Scripting                                        | Nenhum conhecimento de ferramentas de scripting              | Batch files/shell scripts                                    | Perl/Python/Ruby/VBScript/Powershell                         | Escreveu e publicou código reutilizável                      |                                                              |
| Bancos de Dados                                  | Pensa que o Excel é um banco de dados                        | Conhece conceitos básicos de banco de dados, normalização, ACID, transações e pode escrever seleções simples | Capaz de projetar esquemas de banco de dados bons e normalizados, tendo em mente as consultas que terão de ser executadas, proficiente no uso de vistas, procedimentos armazenados, gatilhos e tipos definidos pelo usuário. Conhece a diferença entre índices agrupados e não agrupados. Proficiente no uso de ferramentas ORM. | Pode fazer administração básica de bancos de dados, otimização de desempenho, otimização de índices, escrever consultas avançadas de seleção, capaz de substituir o uso do cursor por sql relacional, entende como os dados são armazenados internamente, entende como os índices são armazenados internamente, entende como os bancos de dados podem ser espelhados, replicados, etc. Entende como funcionam as duas fases do commit. |                                                              |

| Experiência                              | 2n (Nível 0)                      | n2 (Nível 1)                                                 | n (Nível 2)                                                  | log(n) (Nível 3)                                             | Comentários |
| ---------------------------------------- | --------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------- |
| Linguagens com Experiência Profissional  | Imperativa ou orientado a objetos | Imperativa, Orientado a Objetos e Declarativo (SQL), bônus adicional se entender tipagem estática vs dinâmica, tipagem fraca vs forte e dos tipos inferidos estáticos | Funcional, bônus adicional se entenderem lazy evaluation, currying, continuações | Concorrentes (Erlang, Oz) e Lógicas (Prolog)                 |             |
| Plataformas com Experiência Profissional | 0-1                               | 2-3                                                          | 4-5                                                          | 6+                                                           |             |
| Anos de Experiência Profissional         | 0-1                               | 2-5                                                          | 6-9                                                          | 10+                                                          |             |
| Conhecimento de Domínio                  | Nenhum conhecimento do domínio    | Trabalhou em pelo menos um produto no domínio.               | Tem trabalhado em vários produtos no mesmo domínio.          | Especialista em domínios. Projetou e implementou vários produtos/soluções no domínio. Bem versado com termos padrão, protocolos utilizados no domínio. |             |

| Conhecimentos                                     | 2n (Nível 0)                                                 | n2 (Nível 1)                                                 | n (Nível 2)                                                  | log(n) (Nível 3)                                             | Comentários |
| ------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------- |
| Conhecimento de Ferramenta                        | Limitado à IDE primária (VS.Net, Eclipse etc.)               | Conhece algumas alternativas às ferramentas populares e padrão. | Bons conhecimentos de editores, depuradores, IDEs, alternativas de código aberto, etc., etc. Por exemplo, alguém que conhece a maioria das ferramentas da lista de power tools do Scott Hanselman. Utilizou ferramentas ORM. | Escreveu ferramentas e roteiros, bonus adicional se foram publicados. |             |
| Exposição a Linguagens                            | Imperativa ou orientado a objetos                            | Imperativa, Orientado a Objetos e Declarativo (SQL), bônus adicional se entender tipagem estática vs dinâmica, tipagem fraca vs forte e dos tipos inferidos estáticos | Funcional, bônus adicional se entenderem lazy evaluation, currying, continuações | Concorrentes (Erlang, Oz) e Lógicas (Prolog)                 |             |
| Conhecimento de Codebase                          | Nunca olhou para a codebase                                  | Conhecimento básico do layout do código e de como fazer a build | Bom conhecimento prático da base de códigos, implementou várias correções de bugs e talvez algumas pequenas características. | Implementou várias grandes características na base de código e pode facilmente visualizar as mudanças necessárias para a maioria das características ou correções de bugs. |             |
| Conhecimento de Tecnologias Pioneiras             | Ainda não ouviu falar das próximas tecnologias               | Já ouviu falar das próximas tecnologias no campo             | Fez o download da visualização alfa/CTP/beta e leu alguns artigos/manuais | Brincou com as previews e realmente construiu algo com elas e como um bônus compartilhou com a comunidade |             |
| Internalidade de Plataformas / Platform Internals | Conhecimento zero dos internos da plataforma                 | Tem conhecimento básico de como a plataforma funciona internamente | Profundo conhecimento dos internos da plataforma e pode visualizar como a plataforma pega o programa e o converte em código executável. | Possui ferramentas escritas para melhorar ou fornecer informações sobre os internos da plataforma. Para, por exemplo, desmontadores, descompiladores, depuradores, etc. |             |
| Livros                                            | Unleashed series, 21 days series, 24 hour series, dummies series… | Code Complete, Don’t Make me Think, Mastering Regular Expressions | Design Patterns, Peopleware, Programming Pearls, Algorithm Design Manual, Pragmatic Programmer, Mythical Man month | Structure and Interpretation of Computer Programs, Concepts Techniques, Models of Computer Programming, Art of Computer Programming, Database systems , by C. J Date, Thinking Forth, Little Schemer |             |
| Blogs                                             | Já ouviu falar deles, mas nunca teve tempo para isso.        | Lê blogs de engenharia de tecnologia/programação/software e ouve podcasts regularmente. | Mantém um blog de links com alguma coleção de artigos e ferramentas úteis que ele/ela coletou | Mantém um blog no qual são compartilhados insights e pensamentos pessoais sobre programação |             |
