
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

Link do Padlet: https://padlet.com/kawanribeiro/my-fearless-padlet-5sx2mkpku1hdj4st

## 1. Introdução

***1.1. Nome do grupo 3: D1c3 ***

João Marcos Ribeiro da Costa (https://github.com/JoaoMarcosRibeiroCosta)<br/>
Kawan Yukio Ribeiro (https://github.com/KawanRibeiro)<br/>
Ronaldo Azevedo<br/>
Rodolfo Depieri Gindri (https://github.com/RdGindri)<br/>
Lucas Nicoletti Theobaldo (https://github.com/LucasTheobaldo)<br/>

***1.2.  Nome do Sistema: D1c3 RPG companion***

D1c3

***1.3.  Propósito do Sistema***

  O sistema possui o propósito de permitir que a interação em sessões de RPG sejam mais dinâmicas e intuitivas, permitindo que os usuários aprendam a jogar de maneira mais simplificada, contendo dicas de como se realizar ações, desde as mais simples,
até as mais complexas, sem quebrar as regras do jogo.

***1.4.  Público Alvo***

  O público alvo se baseia em jogadores, tanto novatos, quanto os mais experientes, que tenham interesse em torna a jogatina de RPG, mais simplificada e prática, de modo que todos possam aprender a jogar, do básico, até melhorar as técnicas daqueles
que já jogam há mais tempo.

***1.5. Descrição dos usuários***



***Personas:***

Persona 1:
![Apresentação Gráfica de Persona Terapeuta Divertido Rosa](https://github.com/user-attachments/assets/7529d601-9aed-4d3e-ac20-6dcb92795c02)


![Apresentacao Grafica de Persona Terapeuta Divertido Rosa (1)_page-0001](https://github.com/user-attachments/assets/bcc7c7d6-a74b-427e-bdda-805cd753bec0)


***Análise da situação atual: antes da introdução de sua solução***

*`1. O que as pessoas fazem?`*
*`2. Quais os artefatos envolvidos?`*
*`3. O que elas precisam saber?`*

***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***

*`1. O que as pessoas fazem?`*
*`2. Quais os artefatos envolvidos?`*
*`3. O que elas precisam saber?`*

***Cenário: Antes***

*<Preencher com o cenário idealizado antes da aplicação do seu sistema.>*

***Cenário: Depois***

*<Preencher com o cenário idealizado depois da aplicação do seu sistema.>*

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***
|Identificador|<p style="text-align:center;">Descrição</p>|Prioridade|Dependencia|
|:------:|-----------------------------------------------|:------:|:---------------:|
| RF01 | O sistema deve permitir o cadastro de jogador                                                                  | Alta  | Dependente de: RNF01 |
| RF02 | O sistema deve permitir deve permitir o login de jogador e mestre, por áreas separadas                         | Alta  | Depende de RF01,RF08 |
| RF03 | O sistema deve conter avatares para manipulação do mestre                                                      | Média |                      |
| RF04 | O sistema deve permitir deve permitir a alteração da ficha dos jogadores                                       | Alta  |                      |
| RF05 | O sistema deve permitir o armazenamento das fichas                                                             | Alta  |                      | 
| RF06 | O sistema deve conter um apontamento feito pelo mestre para que o jogadores tenham noção de onde estão no mapa | Baixa |                      | 
| RF07 | O sistema deve permitir que os usuários solicitem a criação de vinculo (amizade) entre os jogadores            | Média |                      |
| RF08 | O sistema deve permitir o cadastro de mestre, com seus requisitos próprios                                     | Alta  |                      |
| RF09 | O sistema deve permitir que o mestre tenha acesso a um guia de como gerir o jogo                               | Média |                      |
| RF10 | O sistema deve permitir o cadastro de mapas e seus próprios monstros                                           | Alta  |                      |
| RF11 | O sistema deve permitir o cadastro de um sistema de recomenpsas gerados apartir da rolagem dos dados           | Alta  |                      |

<br>

***2.2. Requisitos Não Funcionais***
|Identificador|<p style="text-align:center;">Descrição</p>|Prioridade|Dependencia|
|:------:|-----------------------------------------------|:------:|:---------------:|
|RNF01 | O sistema deve ter suporte de banco de dados robusto | Alta | |
|RNF02 | O sistema deve possuir salvamento automatico para evitar perda de dados | Alta | |
|RNF03 | O sistema deve funcionar em sistemas operacionais Android e IOS | Baixa
|RNF04 | O sistema deve funcionar em qualquer sistema operacional Windows e/ou Linux | Baixa | |
|RNF05 | O sistema deve ter um acesso de usuário (login) em menos de 2 (dois) segundos | Média | |
|RNF06 | O sistema não pode permitir que um usuário (jogador) acesse a ficha de outro jogador | Alta | |
|RNF07 | O sistema não deve permitir a alteração do mapa, exceto o mestre | Baixa | |
|RNF08 | O sistema deve permitir o carregamento das telas e suas informações em menos de 5 (cinco) segundos | Alta | |
|RNF09 | O sistema deve permitir o acesso do aplicativo via Browser (navegador) | Baixa | |
|RNF10 | O sistema deve seguir as normas da LGPD (Lei geral de proteção de dados) | Alta | |

***2.3. Perguntas***

A - (Perguntas a ser feita para o mestre)<br>
1- Quanto o gerenciamento pela parte do mestre, acharia útil a implementação de um sistema para ajudar o percurso da história?<br>
2- O quanto você acha que o aplicativo pode ajudar a administrar historia ? <br>
3- O quanto seria utíl para você usar marcador no mapa do jogo? <br>
4- O quanto seria utíl para você o gerenciador de personagens como jogadores, monstros e npcs?<br>
5- O que você acharia interessante implementar na area do mestre.<br>
B- (Perguntas para o Jogador)<br>
6- O quanto seria util o aplicativo para ajuda na criação de ficha de personagem?<br>
7- O aplicativo ajuda a compreender mais facilmente as mecânicas referente a jogar RPG?<br>
8- O aplicativo desenvolve, em sua opinião, uma jogatina mais prática entre os jogadores?<br>
9- O sistema permite que os usuários fiquem mais imersivo nas sessões?<br>

***2.4. Entrevista***

*<Arquivo com as respostas do indivíduo entrevistado e [link do drive com upload da gravação](https://drive.google.com/file/d/1x0h2aRIVs4jhNHFQr3iGryzVKBzwGBzS/view?usp=sharing).>*

***2.5. Histórias do Usuário***

Cenário: Antes

Paulo é um contador renomado que passa a maior parte do seu dia trabalhando, por conta  disso paulo é muito estressado
e não tem paciencia para praticar seu hobby que é RPG de mesa.
Paulo gostaria muito de jogar RPG de mesa novamente assim como era em sua infancia, porém, demandaria muito tempo de Paulo,
pois, existem inumeras regras, historias e personagens.
Paulo se sente frustrado por não conseguir exercer seu hobby, por conta disso acaba ficando cada vez mais cansativo seus dias.

Cenário: Depois 

Paulo é um contador renomado que passa a maior parte do seu dia trabalhando. Ele poderia ser uma pessoa estressada porém,
Paulo Descobriu a pouco tempo o sistema DICE, que ajuda Paulo a exercer seu hobby que é o RPG de mesa.
Assim como em sua infancia Paulo separa um dia da semana para mestrar uma seção de RPG, o sistema o ajuda muito pois ele
não precisa passar horas estudando.
Paulo se sente feliz por conseguir exercer seu hobby, por conta disso sua semana acaba sendo mais leve.
  
***2.6. Diagramas de Caso de Uso e Especificações***

[Descrição_ Casos_De_Uso(D1CE).odt](https://github.com/user-attachments/files/18118807/Descricao_.Casos_De_Uso.D1CE.odt)
![asdasdasdasd](https://github.com/user-attachments/assets/3adf1b87-ad37-4a72-8c27-373b257c3715)

<!-- raw html -->
<table border="1 | 0" style="max-width:550px;"> 
    <tbody>
        <tr>
            <td>ID:</td>
            <td>001</td>
        </tr>
        <tr>
            <td>Nome do caso de uso:</td>
            <td>Solicitação de amizade</td>
        </tr>
        <tr>
            <td>Atores:</td>
            <td>Mestre, Jogador</td>
        </tr>
        <tr>
            <td>Visão Geral:</td>
            <td>Esse caso de uso descreve como o mestre ou jogador envia uma solicitação de amizade no sistema.</td>
        </tr>  
        <tr>
            <td colspan="2">Cenário de Sucesso Principal</td>
        </tr> 
        <tr>
            <td colspan="2">
                1. O caso de uso começa com o jogador ou o mestre abrindo a aba de amizades<br>
                2. O jogador ou o mestre escolhe a opção “Solicitar Amizade” no menu de amizades.<br>
                3. O sistema aciona o gerenciador de amigos e pede para o usuário digitar o nome do outro usuário.<br>
                4. O gerenciador de amigos envia uma solicitação de amizade para o usuário desejado.<br>
                5. O sistema espera a confirmação ou a negação da solicitação.<br>
                6. O sistema informa o usuário q foi solicitado e oque solicitou se foi aceito ou negado.<br>
                7. No caso de confirmação da solicitação o sistema adiciona o usuário solicitado na lista de amigos do usuário solicitante.<br>
                8. O caso de uso termina.<br>
            </td>
        </tr>
         <tr>
            <td colspan="2">Extensões</td>
        </tr> 
        <tr>
            <td colspan="2">
                ▪ E.1. No Passo 3, caso o sistema não consiga encontrar o nome do usuário digitado.<br>
                    • E.1.1. O sistema mostra uma mensagem de “USUARIO NÃO ENCONTRADO”.<br>
                    • E.1.2. O sistema abre novamente a caixa para digitar o nome do usuario.<br>
                    • E.1.3. O jogador ou mestre insere o nome do usuario.<br>
                    • E.1.4. O caso de uso retorna ao Passo 6.<br>
                    • O caso de uso termina.<br>
            </td>
        </tr>                 
    </tbody>
</table>

***2.7. Diagramas de Atividades***

*<Imagem, arquivo (PDF), link com Diagrama de Atividades.>*

***2.8.  Diagramas de Classe***
![d1c3 1_page-0001](https://github.com/user-attachments/assets/ec057211-a659-4316-874a-f71493cdd6ac)




***2.9. Protótipos***

[*<Imagem, arquivo (PDF), link com Protótipo.>*](https://ninjamock.com/s/JFB11Lx)

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
