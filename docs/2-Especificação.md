# Especificações Do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Contexto.md"> Documentação de Contexto</a></span>

Neste projeto estamos propondo um calendário que será alimentado pela ONG e disponibilizado aos pacientes, permitindo que os próprios possam visualizar a disponibilidade de dias e horários, facilitando assim o processo de agendamento das consultas. Através do calendário, os pacientes podem efetuar o cancelamento do atendimento sem muita burocracia e gerando um alerta para que os gestores da clínica possam identificar o pedido e abrir uma nova vaga.

Baseado nas personas identificadas trabalho será realizado no ambiente Web, sendo responsivo a necessidade e uso no aparelho móvel. Também serão mantidos registrados informações importantes da ficha do pacientes, apenas no acesso da clínica para que quando seja visualizado uma consulta do mesmo, essas informações sejam obtidas em tela preparando o profissional da ONG a um atendimento mais assertivo. Também será acrescentado a opção da numeração da consulta dos pacientes, permitindo a clínica acompanhar quantas seções um determinado paciente já teve e como está o andamento dele.

> 
## Público-Alvo
A aplicação proposta terá como público alvo os pacientes de um equipe de psicólogos voluntários que atendem na ONG, assim como os psicólogos e gestores que irão coordenar as datas de atendimento e disponibilidade de horários.

Desta forma estabelece que o público-alvo sejam homens e mulheres, entre jovens e adultos que buscam tratamento psicológico mas que não tenham oportunidades para custear o mesmo e que fazem o uso de dispositivos móveis para algumas das suas atividades diárias e lazer. Assim como psicólogos e gestores da ONG, que tenham vinvência no horários de atendimento e que conhecem a rotina da ONG para alimentar o sistema de gestão de consultas e que fazem uso frequente de computadores e dispositivos móveis.

## Personas

Maria tem 30 anos, trabalha com controle de qualidade, e utiliza dispositivos móveis para manter contato com a família, e para lazer, como Facebook, WhatsApp e Pinterest.

João tem 28 anos, aluno no curso de Ciência da Computação. Está em busca de uma ONG com custo acessível para apoio psicológico. E utiliza dispositivos móveis para realizar cursos online.

Gabriela tem 23 anos, cursa Sistemas de Informação. Trabalha na área de atendimento e possui uma grande vivência com aplicativos móveis e plataformas web.

Larissa tem 20 anos, recém-formada em Odontologia e autônoma. Frequenta a ONG e necessita de um melhor atendimento em relação as consultas, já que o quadro de pacientes aumentou devido a pandemia do COVID-19. Larissa utiliza plataformas web com frequência pois ela possui um blog para divulgação de seus trabalhos profissionais.

Wesley tem 25 anos, cursa Sistemas de Informação. Trabalha na área de Assistente de TI, e utiliza de aplicativos móveis e plataformas web para realizar tarefas na empresa em que trabalha, durante o seu dia-a-dia.

> Enumere e detalhe as personas da sua solução. Para
> tanto, baseie-se tanto nos documentos disponibilizados na disciplina
> e/ou nos seguintes links:
>
> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
> Lembre-se que você deve ser enumerar e descrever precisamente e
> personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

> Apresente aqui as histórias de usuário que são relevantes para o
> projeto de sua solução. As Histórias de Usuário consistem em uma
> ferramenta poderosa para a compreensão e elicitação dos requisitos
> funcionais e não funcionais da sua aplicação. Se possível, agrupe as
> histórias de usuário por contexto, para facilitar consultas
> recorrentes à essa parte do documento.
>
> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

> Com base nas Histórias de Usuário, enumere os requisitos da sua
> solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais
>   (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais
>   (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


> Enumere as restrições à sua solução. Lembre-se de que as restrições
> geralmente limitam a solução candidata.
> 
> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
