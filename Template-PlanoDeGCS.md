<Nome do Projeto>
=================
Plano de Gerenciamento de Configuração
======================================
Versão &lt;1.0&gt;
------------------

_[Observação: O template a seguir é fornecido para uso com o Rational Unified Process (RUP).  O texto exibido entre colchetes e em itálico foi incluído para orientar o autor e deve ser excluído antes da publicação do documento._

_Este documento utiliza a formatação da linguagem [Markdown] (http://daringfireball.net/projects/markdown/). Você pode encontrar um guia de referência rápido [aqui] (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).]_

Histórico de Versões
--------------------

|Data                |Versão       |Descrição               |Autor          |
|--------------------|-------------|------------------------|---------------|
|_&lt;09/12/2014&gt;_|_&lt;1.0&gt;_|_&lt;Versão inicial&gt;_|_&lt;Simone Magalhaes&gt;_|
|_&lt;12/12/2014&gt;_|_&lt;1.1&gt;_|_&lt;Inclusão de requisitos&gt;_  |_&lt;Aline Pereira&gt;_|
|_&lt;15/12/2014&gt;_|_&lt;1.1&gt;_|_&lt;Inclusão de requisitos&gt;_  |_&lt;Jaqueline Uchoa&gt;_|



1. Introdução
==============

Este documento apresenta o plano de gerência de configuração e mudança do Sistema Livraria que servirá de base de referência para o controle sistemático da configuração e das mudanças realizadas no projeto, durante todo o seu ciclo de vida até que os produtos gerados sejam liberados para o cliente, mantendo sua integridade.

1.1 Finalidade
---------------
Este Plano de Gerenciamento de Configuração visa definir como, quando e onde deverá ser feita a gestão de configuração e mudança do Projeto Livraria.

1.2 Escopo
----------
_[Controlar as versões do sistema, fazer os commits, branchs e merges para melhor entendimento por parte dos analista de sistemas, gerentes de projeto e analista de requisitos.Manter clareza nas informações sobre as alterações feitas. Objetividade nas alterações das vesões do sistema]_

1.3 Definições, Acrônimos e Abreviações
---------------------------------------
|TERMO               |                   SIGNIFICADO                        |
|--------------------|-------------|------------------------|---------------|
|_&lt;Baseline&gt;_| |Conjunto de itens de configuração que conseguiram um estado comprovado de estabilidade.|

1.4 Referências
---------------
_[Esta subseção apresenta uma lista completa de todos os documentos mencionados no Plano de Gerenciamento de Configuração. Identifique os documentos por título, número de relatório (se aplicável), data e organização responsável pela publicação. Especifique as fontes a partir das quais as referências podem ser obtidas. Essas informações podem ser fornecidas por um anexo ou outro documento.]_

1.5 Visão Geral
---------------
_[Este documento foi criado para melhor orientar os envolvidos nas mudanças e versões do Sistema Livraria, como Analista de Requisitos, Gerente de Projeto e Analistas de Sistemas.]_



2. Gerenciamento de Configuração de Software
============================================

2.1 Organização, Responsabilidades e Interfaces
------------------------------------------------
|PAPÉIS        |EQUIPE    |RESPOSABILIDADE       |
|:------------:|:-----------:|------------|
|Gerente de Configuração| Simone Magalhães |Estabelecer Políticas de GC</br>   Escrever Plano de GC</br>  Configurar Ambiente de GC</br>  Criar Espaços de Trabalho de Integração</br>  Criar Baselines</br>  Promover Baselines|
|CCM| Aline Pereira |Estabelecer Processo de Controle de Mudanças</br>  Revisar Solicitação de Mudança|
|Desenvolvedor|Jaqueline Uchoa </br >Simone Magalhães|Seguir os padrões e procedimentos definidos no Plano de Gerência de Configuração|

2.2 Ferramentas, Ambiente e Infra-estrutura
-------------------------------------------
|Tipo   |Ferramenta	    |Versão    |
|----------------|----------|:---------------:|
|Elaboração dos artefatos de Especificação|	LibreOffice	|-|
|Diagramas de análise e Projeto	|StarUML|5.03|
|Controle de versão|GIT|2.0|
|Gestão de mudanças|Mantis|2013
|Plataforma de Desenvolvimento|Ferramenta: Eclipse Indigo 3.7</br><br>Linguagem: JAVA SE |Junit	|
|Banco de Dados|PostgreSQL	|8.4|
|Maquina virtual|	VirtualBox |	4.3.2|
|Comunicação|Telefone	/ Skype / Hangout/ WhatZap|


3. O Programa de Gerenciamento de Configuração
==============================================

3.1 Identificação da Configuração
---------------------------------
### 3.1.1 Métodos de Identificação
----------------------------------
_[Todos os artefatos gerados, com exceção de código fonte, neste projeto terão a seguinte nomenclatura]_

Faz-se necessário que as letras que compoẽm o identificador esteja em caixa alta, onde estão listados na tabela 1, logo abaixo.

| Identificador        | Artefato                                          |
|----------------------|---------------------------------------------------|
| ARQU                 | Documento de arquitetura.                         |
| ATA                  | Ata de reuniões.                                  |
| MDC                  | Modelo, ou diagrama, de classes.                  |
| MER                  | Modelo de entidade-relacionamento.                |
| PTS                  | Plano de teste de software.                       |
| REQ                  | Documento de requisito.                           |
| RPT                  | Relatório de status, métricas, bugs, etc.         |
| TAP                  | Termo de abertura do projeto.                     |
| TST                  | Caso de teste.                                    |
| UC                   | Caso de uso.                                      |

### 3.1.2 Itens de Configuração
_[Relacionar os artefatos ou grupos de artefatos, separando por tipo, modulo ou subsistema, responsável ou momento em que deverão ser incluídos em baselines._
* _“Inclusão em Baseline” em branco significa que o grupo de artefatos não participará de baseline. Pode ser expresso como uma data ou identificador de uma baseline, fase ou ponto de controle_
* _“Responsável”: indicar nominalmente, sempre que possível]_

| Item (ou Tipo de Item)                           | Responsável na equipe	     | Inclusão em Baseline |
|--------------------------------------------------|----------------------------|----------------------|
|_&lt;Artefatos:Regras de Negócio, casos;_ 
_&lt;de uso, diagramas de análise e projeto,;_
_&lt;mensagens, regras de validação, requisitos,;_
_&lt;casos de teste, plano de projeto, cronograma&gt;_
_&lt;análise e negócio (contratos, atas de reunião...);_|_&lt;Simone&gt;_|_&lt;baselineartef1.0122014&gt;_|
                                         
|_&lt;Código-fonte&gt;_                            |_&lt;Jacqueline&gt;_        |_&lt;baselinecodigo1.0122014&gt;_|

### 3.1.3 Baselines do Projeto

As baselines serão criadas quando um dos seguintes fatos ocorrerem:
- Início do projeto;
- Cliente assinar termo de aceite;
- Fim de ciclo de desenvolvimento;
- Entrega de release para o cliente;
- Alteração de item de configuração;
- Entrega do produto final do projeto.    

Para que se dê a criação de uma baseline, é necessário que o gerente de configuração autorize, haja vista que o mesmo estará envolvido em todas as etapas do projeto, sendo este responsável por preparar o ambiente em que os artefatos serão versionados.

A baseline, quando criada, conterá:
- Codigo fonte
- Documento de requisitos
- TAP
- Casos de teste
- Casos de uso

### 3.1.4 Estrutura do Repositório de Versões
_[Descreva a organização de diretórios do seu repositório e que itens/arquivos devem ser armazenados em cada diretório.]_
Artefatos > Especificação > Requisitos; Regras de Negócio; Casos de uso; Mensagens; Regras de Validação;
Artefatos > Especificação > Teste > Casos de teste funcional; Casos de teste desempenho;
Artefatos > Análise e Projeto > Diagramas de Análise e Projeto (Classe, Sequencia, Atividade, Caso de uso, Estado, Implantação);
Artefatos > Projeto > Plano de projeto; Cronograma.
Códigoe > Fontes (Arquivos do sistema)

3.2 Controle de Configuração e Mudança
--------------------------------------

### 3.2.1 Processamento e Aprovação de Solicitações de Mudança
_[Descreva o processo pelo qual os problemas e as mudanças são submetidos, revisados e dispostos. Inclua como funciona a transição de estados de uma solicitação de mudança]_
Ciclo de vida de uma solicitação de mudança: Novo, Atribuído, Em desenvolvimento, resolvido, Testado, Fechado, re-aberto.
Estrutura do CCB do seu projeto: ??


### 3.2.2 Comitê de Controle de Mudança (CCB)
_[Descreva a participação e os procedimentos para processar solicitações e aprovações de mudança a serem seguidos pelo CCB. Informe quem são os membros do CCB e suas responsabilidades.]_
Integrantes: Aline, Simone, Jacqueline


4. Padrões e Procedimentos
==========================
_[Descreva os padrões e procedimentos que devem ser seguidos no projeto. Crie subseções se achar necessário, para organizá-los melhor.]_
Quando será obrigatório criar: Manutenção de uma versão em produção x trabalho na nova
versão, Atividade impactante e demorada, Customizações para diferentes.
clientes ou ambientes
Padrão para o nome do branch: nomefuncionalidade.0000
Quem é responsável por criar: GC - Aline
Quando e por quem o merge deve ser feito - a cada nova entrega ou versão - GC


5. Treinamento e Recursos
=========================
_[Descreva as ferramentas de software, o pessoal e o treinamento necessários para implementar as atividades de CM especificadas.]_
Ferramentas: GIT, Mantis


6. Auditorias de Configuração
=============================
_[Descreva o cronograma das auditorias de configuração e o que será verificado. Informe também como serão reportados os problemas encontrados e onde sera feito o acompanhamento dos itens corretivos.]_
