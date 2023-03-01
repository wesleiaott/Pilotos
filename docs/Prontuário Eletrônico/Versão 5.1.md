---
layout: default
title: Versão 5.0.1
parent:  Prontuário Eletrônico
nav_order: 4
has_children: false
has_toc: true
last_modified_date: "07/01/2022"
---

<h1>Versão 5.1</h1>

Módulos com novidades:
<ul>
    <li>Marcadores de consumo alimentar</li>
    <li>Busca ativa de vacinação</li>
    <li>Encaminhamento externo</li>
    <li>Adaptação do PEC para uso do estagiário</li>
    <li>Reterritorialização</li>
    <li>Observação do cidadão</li>
    <li>Registro tardio</li>
    <li>Acompanhamento de cidadãos vinculados</li>
    <li>RNDS - Envio de vacinas</li>
</ul>

<h3>Marcadores de consumo alimentar</h3>
<br>

* Agora é possível registrar o marcador de consumo alimentar do cidadão diretamente no atendimento. A opção foi incluída no Objetivo do SOAP em quase todos os tipos de atendimento e o formulário é apresentado de acordo com a idade do cidadão.

Gif mostrando o cadastro de uma lotação de estágioImagem de pause

* As informações de consumo alimentar registradas no atendimento também são apresentadas no histórico e impressão. É possível reconhecer um atendimento com esse registro através da etiqueta “Marcadores de consumo alimentar".
Gif mostrando o cadastro de uma lotação de estágioImagem de pause

Busca ativa de vacinação

* Agora é possível realizar a Busca ativa de vacinação, que retorna uma listagem exibindo os dados dos cidadãos que possuem doses de imunobiológicos atrasados ou no prazo para aplicação a partir das vacinas do calendário vacinal, e também as doses de imunobiológicos aplicados para as vacinas de Covid-19. É possível também realizar a exportação do relatório em formato CSV para manipulação dos dados.

* O resultado na listagem é filtrado a partir dos seguintes campos:

    * Grupo-alvo: irá filtrar os cidadãos por grupos-alvo do calendário vacinal e os cidadãos que estão na faixa etária selecionada para as vacinas de Covid-19;

    * Status da vacina: para as vacinas do calendário vacinal, será possível filtrar os imunobiológicos e suas respectivas doses pelos status Atrasada (vacinas não tomadas dentro do calendário vacinal) ou No prazo (vacinas não tomadas do calendário vacinal que estão dentro do prazo para aplicação), e para as vacinas de Covid-19, será possível filtrar os imunobiológicos e suas respectivas doses pelos status Aplicada.

* Estão disponíveis para seleção os grupos alvo de "Crianças (0 a 9 anos)" e "Adolescentes (10 a 19 anos)".

* Para gerar a listagem com os filtros selecionados, basta clicar no botão "Buscar cidadãos". Então, será exibida a listagem com as seguintes colunas: Cidadão, Idade, Endereço, e Status da vacina (Atrasada ou No prazo para o Calendário vacinal e Aplicada para as vacinas de Covid-19).

* A listagem pode ainda ser ordenada pelas colunas: Cidadão, Idade.

Encaminhamento externo

* Agora é possível registrar novos tipos de encaminhamento externo na seção de Plano dos atendimentos. Foram incluídas as opções:

* CAPS;
* Urgência;
* Internação hospitalar;
* Serviço de Atenção Domiciliar;
* Intersetorial.

Print de Encaminhamento externo

Adaptação do PEC para uso do estagiário

A nova funcionalidade permite que estagiários utilizem o PEC e tenham os atendimentos validados pelo supervisor antes da finalização. Foram inseridos os seguintes fluxos no sistema para adaptá-lo ao uso do estagiário:

* Login individual para o estagiário;
* Cadastro de uma lotação de estágio com um respectivo supervisor;

Gif mostrando o cadastro de uma lotação de estágioImagem de pause

* Retificação dos atendimentos realizados pelo estagiário antes do início da revisão pelo supervisor;
* Revisão dos atendimentos feitos pelo estagiário antes da finalização;

Gif mostrando a revisão de um atendimento feito pelo estagiárioImagem de pause

* Atualizações no Histórico para apresentar atendimentos realizados por estagiários;
* Novos status na Lista de Atendimento para suportar as funcionalidades.

Print do status aguardando revisão

Reterritorialização

* Agora é possível atualizar rapidamente o território dos imóveis e seus respectivos núcleos familiares. Com esta nova funcionalidade, a atualização das informações que determinam a responsabilidade de acompanhamento no território poderá ser feita de uma forma rápida e consolidada, sem a necessidade de se atualizar ficha por ficha.

* Acesse a seção "Gestão de Cadastros" e a aba de Reterritorialização. Nesta tela basta realizar uma busca pelos imóveis desejados.

Print reterritorializacao busca

* Aí então basta selecionar na lista quais deles devem ser reterritorializados, informar os novos dados e clicar em "Atualizar imóveis".

Print reterritorializacao seleção

* Este processo preserva automaticamente os núcleos familiares envolvidos, gerando novas fichas de atualização assim que um novo lote de fichas for gerado e enviado.

Observação do cidadão

* Agora é possível registrar no prontuário que um cidadão deve ficar em observação. Para tanto é necessário ativar o botão “Cidadão em observação” que irá liberar um novo fluxo no sistema:

Print botão “Cidadão em observação”

* Na lista de atendimentos os cidadãos em observação ficarão em uma seção separada;

* O profissional que iniciou a observação é considerado o profissional responsável, sendo este o único que poderá finalizar o atendimento de observação;
Print profissional responsável”

* Os outros profissionais que participarem da observação são considerados profissionais auxiliares, pois o foco desses profissionais é estabilizar o cidadão de acordo com o plano de cuidado prescrito pelo profissional responsável. Sendo que, os atendimentos dos profissionais auxiliares terão o mesmo formato que um atendimento de procedimentos com as seguintes mudanças:

    * A cada ponto de contato que o profissional tiver com o cidadão dentro de uma observação deve ser possível registrar uma medição;

    * O histórico de plano de cuidados deve ser exibido no Plano do SOAP, contendo todos os planos de cuidado realizados pelos profissionais da saúde para aquele atendimento de observação;

    * Nos atendimentos do profissional responsável todas as informações se mantêm, sendo possível realizar mais de uma medição, além de adicionar o histórico de plano de cuidados no Plano do SOAP;

Print plano de cuidado

Acompanhamento de cidadãos vinculados

* Com o novo acompanhamento é possível buscar, imprimir e exportar todos os cidadãos que são acompanhados pelas equipes da unidade de saúde, até mesmo aqueles que não pertencem a um núcleo familiar, ou seja, unidades que não utilizam o CDS, poderão visualizar os cidadãos no relatório, desde que em seu cadastro esteja informada a equipe responsável pelo cidadão.

* O Acompanhamento de cidadãos vinculados fica em um novo menu de Acompanhamentos, agrupado ao Acompanhamento de condições de saúde.

* Por padrão, os profissionais com os perfis Coordenador da UBS, ACS, TSB, Outros profissionais de nível superior NASF, Outros profissionais de nível superior, Outros profissionais de nível médio técnico, ASB, Auxiliar ou técnico de enfermagem, Cirurgião dentista, Enfermeiro, Farmacêutico e Médico terão acesso ao novo relatório. Com exceção do Coordenador da UBS, os demais profissionais só visualizam cidadãos relacionados às suas respectivas equipes.

Gif mostrando o funcionamento do acompanhamento de cidadãos vinculados

Redesign do módulo Registro tardio

* Nova interface! O módulo foi redesenhado a fim de facilitar a sua utilização, mantendo estrutura do atendimento individual;

Layout antigo do registro tardio

Permissão de agendamento do Registro tardio quando a justificativa for fora da UBS através do módulo da agenda;

Demonstração da funcionalidade de agendamento do registro tardio com a justificativa de "Fora da UBS" através do módulo da agenda.Imagem de pause

* Permissão de registros de atendimentos de até 7 dias anteriores a data atual que não puderam ser registrados no dia do atendimento;

* Possibilidade de cancelar registro na própria listagem caso ele tenha excedido o prazo ou possua outro mais recente que ele;

* Ao tentar realizar um registro com atendimento mais recente, são exibidas informações do atendimento posterior em uma modal;

Demonstração das funcionalidades de registro de atendimentos realizados até 7 dias anteriores a data atual, cancelamento de registro por tempo excedido e exibição de informações de atendimentos mais recentes. Imagem de pause

* Possibilidade de agendar um atendimento Fora da UBS na finalização do atendimento.

Demonstração de funcionalidade de agendamento de atendimento Fora da UBS na finalização do atendimento.Imagem de pause

RNDS - Envio de vacinas

* Agora, para as instalações com a RNDS configurada, os registros de vacinação serão enviados à Rede Nacional de Dados em Saúde (RNDS) ao finalizar o atendimento de vacinação. Além disso, as transcrições de caderneta também serão enviadas.

* Nova página para visualização da quantidade de registros enviados, localizada no módulo de "Gestão municipal", aba "RNDS".

Gif mostrando o funcionamento do acompanhamento de cidadãos vinculados

Versões de estabilização 5.0

Versão 5.0.19

* Correção de cenário onde alguns elementos de marcação de texto eram exibidos incorretamente no histórico de exames.
* Melhorias de usabilidade na tela de resultados de exames.
* Padronização da apresentação de valores numéricos nos históricos de exames.
* Inclusão de novo botão de acesso ao histórico de resultados de exames ao lado da funcionalidade de registrar resultados de exames.
* Fechamento automático da modal de "Imprimir prescrição" após a impressão de uma prescrição de medicamentos.
* Adição da assinatura do cidadão no atestado para autorizar o registro de diagnóstico quando o CID é preenchido.
* Correção na impressão de atendimentos para considerar a quebras de linha em campos de texto.
* Correção de cenário onde poderia haver inconsistências na transmissão de dados entre versões.

Versão 5.0.18

* Inclusão do campo Conduta no histórico clínico do cidadão para os atendimentos odontológicos.

Versão 5.0.17

* Inclusão de novo imunobiológico contra a Covid-19: "Vacina Covid-19 - Pfizer (Comirnaty) - Bivalente".
* Inclusão de dose de reforço para o imunobiológico "Vacina Covid-19 - Pfizer (Comirnaty) - Pediátrica".
* Correção de cenário em que não era possível cadastrar lotes do imunobiológico "Covid-19 - Pfizer (Comirnaty) - * Pediátrica - p/ menores de 5 anos" através do módulo Lotes de imunobiológico.
* Correção de cenário em que não era possível finalizar um registro tardio caso existisse um agendamento para o cidadão no mesmo dia e horário do atendimento.

Versão 5.0.16

* Otimização no processamento de relatórios.
* Otimização no processo de envio de dados.
* Correção de cenário em que alguns procedimentos eram apresentados várias vezes no detalhe de alguns atendimentos no histórico do cidadão.
* Inclusão de novo imunobiológico contra a Covid-19: Pfizer pediátrica p/ menores de 5 anos.
* Retirada a possibilidade de realizar a transcrição de caderneta através do Registro Tardio.
* Inclusão do grupo de atendimento "Pessoas de 6 meses a 2 anos" nos registros de vacinação.
* Inclusão das doses Única e de 2º Reforço para o imunobiológico 'Meningocócica Conjugada', no calendário vacinal do grupo alvo de Adolescentes.

Versão 5.0.15

* Correção de cenário onde não estava sendo possível gerar Relatórios operacionais de crianças e gestantes.
* Correção de erro de tela branca ao acessar o histórico clínico que não contenha forma farmacêutica definida nas prescrições de medicamentos.
* Ajustes no Relatório de produção de visita domiciliar e territorial para não exibir profissionais duplicados em casos de mudança de CNS.

Versão 5.0.14

* Adição da funcionalidade de impressão da Escuta inicial.
* Limitação do número de procedimentos que podem ser inseridos nos atendimentos para 20.
* Correção de cenário onde uma mensagem de erro era apresentada incorretamente ao finalizar atendimento para cidadãs gestantes.
* Inclusão dos procedimentos SIGTAP "0301010366 - Consulta de Pré-natal de Gestante Alto Risco", "0202031292 - * * Dosagem de Anti-Beta-2-Glicoproteína I - IGM" e "0301010374 - Consulta de Acompanhamento de Recém-Nascidos e * * Criança, Prioritariamente, Egressa de Unidade Neonatal".
* Correção de cenário nos Relatórios operacionais para apresentar somente o cidadão conforme o último estado de território que ele se encontra; evitando registros duplicados nas impressões.

Versão 5.0.13

* Correção de erro onde a tela ficava branca ao atender crianças de 5 anos.
* Agrupamento de todos os imunobiológicos relacionados a Covid-19 em um único componente no Atendimento de vacinação.
* Correção de cenário onde ocorria a quebra de página na impressão de encaminhamentos para Unidades de Saúde com nome muito extenso.

Versão 5.0.12

* Ao finalizar um atendimento, agora é exibido um alerta com todos os campos preenchidos de forma incorreta e que precisam ser corrigidos antes de salvar.
* Correção de erro onde em alguns casos não estava sendo possível visualizar o histórico clínico do cidadão.
* Correção de cenário onde não estava sendo possível atualizar o sistema para versões superiores a 5.0 em instalações com grandes quantidades de registros.
* Ajustes na Ficha de atividade coletiva que mostrava uma inconsistência incorreta no preenchimento dos registros.
* Inclusão do nome do profissional do agendamento juntamente do horário na Lista de atendimentos.
* Correção de erro onde ao realizar a redefinição de senha do instalador, o mesmo ainda continuava bloqueado.
* Ajuste de cenário onde, em algumas instalações, não estava sendo possível importar arquivos de CNES do CEO.
* Inclusão do procedimento SIGTAP "030100313 - Ações de Redução de Danos".
* Ajuste de cenário onde o filtro de Equipe da Lista de atendimentos não estava funcionando corretamente.
* Inativação do procedimento SIGTAP "0301040079 - Escuta inicial / orientação (acolhimento a demanda espontânea)".
* Correção de erro inesperado ao adicionar um CID10 ou CIAP2 de alto risco sem pré-natal cadastrado.
* Ajustes no tamanho da fonte e formatações de data nas impressões de atestado e declaração de comparecimento.
* Correção de cenário onde não estava sendo mostrado o alerta de "Comunicante de Hanseníase" ao aplicar uma vacina de BCG no atendimento de vacinação.
* Alteração nominal do procedimento SIGTAP "0307020061" para "Tratamento endodôntico de dente permanente unirradicular".
* Atualização da lista de procedimentos disponíveis para todos os dentes no odontograma.

Versão 5.0.11

* Correção de cenário onde várias mensagens de erro eram apresentadas quando o profissional abria a própria agenda.
* Inclusão dos imunobiológicos Varíola Bavarian Nordic e Herpes-Zoster (recombinante).
* Correção de erro onde não era possível visualizar o prontuário do cidadão caso ele possuísse um exame específico requisitado.
* Correção de cenário onde não era possível realizar o atendimento de um cidadão caso ele possuísse alergia a uma substância específica cadastrada.
* Alteradas as descrições dos textos do campo "É membro de Povo ou Comunidade Tradicional ou Campo, Floresta e Águas?" na Ficha de cadastro individual.
* Inclusão do procedimento SIGTAP "0301010382 - Estratificação do risco cardiovascular".

Versão 5.0.10

* Correção de cenário onde ao acessar alguns atendimentos a tela ficava branca.

Versão 5.0.9

* Inclusão da terceira dose de reforço para os imunobiológicos COV19 Oxford - AstraZeneca Covishield, COV19 Janssen - Cilag e COV19 Biontech - Pfizer.
* Correção de cenário onde o cartão de Acompanhamento de pré-natal não estava exibindo as informações corretamente e em alguns casos impossibilitava a impressão.
* Ajustes na Avaliação do SOAP, onde ao evoluir um problema/condição sem data de início, a data atual era incluída erroneamente.
* Correção de erro onde não era possível visualizar o histórico clínico do cidadão caso ele possuísse uma avaliação de exame registrada no prontuário.

Versão 5.0.8

* Correção de cenário onde não era possível atender cidadãos que não possuiam data de nascimento registrada.
* Correção de erro onde os alertas do imunobiológico Meningocócica Conjugada C não estavam sendo exibidos corretamente.
* Ajustes na impressão do Acompanhamento da criança para exibir a data do campo "Data de início" de um problema ou condição ativo.
* Ajustes gerais visando performance no módulo de atendimentos.

• Versão 5.0

Módulos com novidades:

* Acompanhamentos
* Alergias
* Antecedentes
* Atendimentos
* Atendimento odontológico
* Atestados
* Encaminhamentos e orientações
* Escuta inicial / pré-atendimento
* Exames
* Histórico clínico do cidadão
* Medicamentos
* Pré-natal / puerpério
* Prontuário / folha de rosto
* Vacinação

Acompanhamentos:

* Nova interface! Agora a lateral do atendimento irá mostrar as informações dos acompanhamentos específicos do cidadão.

Acompanhamento da criança:

* Marcos de desenvolvimento integrados ao SOAP, possibilitando que os profissionais consultem outras informações durante a avaliação.

Gif mostrando o acompanhamento da criançaImagem de pause

Acompanhamento de pré-natal:

* Apresentação de todas as informações que antes estavam na tela de acompanhamento. Risco da gravidez, DPPs, IGs, DUM, consultas de pré-natal realizadas e a última consulta odontológica feita durante a gestação serão informações acessadas rapidamente pelos profissionais através da lateral.

* Medições antropológicas com as curvas de referência durante a fase de gestação.
* Medições específicas do atendimento de pré-natal apresentadas na modal de medições em uma aba separada juntamente com o gráfico de referência de altura uterina.

Acompanhamento de pré-natal no SOAP

Acompanhamento do idoso:

* Apresentação da data da última avaliação multidimensional feita para os cidadãos com 60 anos ou mais.
* Apresentação de um alerta quando 5 ou mais medicamentos de uso contínuo estiverem ativos no cadastro do cidadão.

Acompanhamento do idoso no SOAP

Alergias

* Nova interface! O módulo foi redesenhado e agora está ainda mais fácil de usar. Confira nas imagens abaixo as principais alterações:

Módulo de alergias antigo

* O bloco para registrar a evolução de alergias estará sempre disponível na Avaliação do SOAP.

Gif da avaliação de alergiasImagem de pause

Antecedentes

* Nova interface! O módulo foi redesenhado e agora está ainda mais fácil de usar. Confira nas imagens abaixo as principais alterações:

antecedentes nas versões antigas

* Nova forma de cadastrar os antecedentes pessoais. Agora, o registro dos antecedentes é direto na Lista de Problemas e Condições através do botão "Adicionar antecedente resolvido".

gif mostrando os antecedentes pessoaisImagem de pause

* Antecedentes familiares em uma área exclusiva, com novo campo de observações para cada registro.

gif mostrando os antecedentes familiaresImagem de pause

* Novo grupo de antecedentes hospitalares para cadastro de cirurgias e internações, com novos campos para data e idade.

gif mostrando os antecedentes hospitalaresImagem de pause

* Novo botão para acompanhamento da criança, exibido após o cidadão completar 19 anos. Antes, ao atingir essa idade, a informação não era mais acessível. Agora, é possível através dos antecedentes.

gif mostrando o acompanhamento da criançaImagem de pause

Atendimentos

* Nova interface com estrutura de informações na lateral do atendimento! Facilita o acesso à informações do prontuário que podem ser relevantes durante um atendimento.
São agrupadas em: Alergias/Reações adversas, Problemas/condições, Medições e gráficos, Medicamentos em uso, Lembretes, Resultados de exames, Condições autorreferidas e Acompanhamentos de pré-natal, do idoso e da criança.

Gif mostrando a nova estrutura da tela de AtendimentoImagem de pause

* Pesquisa na Avaliação de problemas e condições que estão ativos ou latentes na Lista de Problema/Condições do cidadão, facilitando o registro da evolução.

Gif mostrando as novas opções de pesquisa durante um atendimentoImagem de pause

* Visualização das listas de Problemas e Condições e de Alergias/Reações adversas do cidadão no Atendimento de Procedimentos.

Gif mostrando o novo Atendimento de ProcedimentosImagem de pause

Atendimento odontológico

* Nova interface! O módulo está em um novo formato, que une a Evolução Odontológica do sistema antigo com a inserção de Problemas e Condições nos dentes. Confira nas imagens abaixo as principais alterações:

Arcada antiga

* Novos campos "Possui aparelho" e "Possui contenção";
* Botão "Mostrar dentes decíduos" para ativar ou desativar a visualização dos dentes;
* Registro de procedimentos em dentes supranumerários através de um botão abaixo do odontograma;

Gif do registro de dentes supranumerarios no odontogramaImagem de pause

* Nova aba "Tecidos duros e moles", onde é possível fazer a análise de outras parte da boca que não sejam os dentes;

Gif da nova aba de tecidos moles e durosImagem de pause

* Nova aba "Periodontia", onde é possível fazer o Registro de procedimentos para sextantes, Registro Periodontal Simplificado e Periograma Completo.
Gif da nova aba de periodontiaImagem de pause

Atestados

* Nova interface! O módulo foi redesenhado e agora está ainda mais fácil de usar. Confira nas imagens abaixo as principais alterações:

Atestado padrão antigo

* Cadastro de modelos de atestado para otimizar o tempo dos profissionais que usam atestados diferentes do modelo padrão.

Cadastro de modelo de atestado

Encaminhamentos e orientações

* Nova interface! Os módulos foram redesenhados e agora está ainda mais fácil de usar. Confira nas imagens abaixo as principais alterações:

Orientacoes antigo

Escuta inicial / pré-atendimento

Nova interface! O módulo foi redesenhado e agora está ainda mais fácil de usar. Confira nas imagens abaixo as principais alterações:

Escuta inicial antiga

Exames

* Nova interface! O módulo foi redesenhado e agora está ainda mais fácil de usar. Confira nas imagens abaixo as principais alterações:

Resultado de exames antigo

* No histórico de solicitações de exames, é possível imprimir uma solicitação em até 30 dias e replicar todos os exames de uma solicitação antiga.

* Os resultados de exames com e sem solicitação são registrados no mesmo local. A interface foi otimizada para inserir todos os resultados de exames no mesmo momento.

Gif da mostrando os resultados de examesImagem de pause

* O histórico de resultados de exames está localizado no menu lateral e permite a comparação de vários resultados do mesmo exame;

Gif mostrando o historico de resultados de exameImagem de pause

Histórico clínico do cidadão

* Nova interface! O módulo foi redesenhado para facilitar a visualização dos diversos tipos de históricos e das principais informações indicadas pelos profissionais através de etiquetas (tags), sem ser necessário abrir os detalhamentos de cada histórico.

Histórico antigo

* Implementação de novos filtros para a localização mais refinada dos históricos dos atendimentos.
Gif dos filtros do históricoImagem de pause

* Otimização na performance do sistema ao trazer os resultados na listagem do histórico clínico.
* Impressão individual e em lote do histórico, facilitando sua ação.

Gif da impressão de históricoImagem de pause

* Visualização do detalhamento de cada histórico com design que facilita a leitura das informações, disponibilizadas na própria listagem ao expandir o item.

Gif da visualização do historicoImagem de pause

* Exclusão de um atendimento do tipo Vacinação.

Gif da exclusão de historicoImagem de pause

Medicamentos

* Nova interface! O módulo foi redesenhado e agora está ainda mais fácil de usar. Confira nas imagens abaixo as principais alterações:

Medicamentos antigo

* Impressão pode ser realizada na mesma tela que está sendo prescrito o medicamento, sendo possível imprimir todos medicamentos daquela receita com um único clique.

Gif da impressão de medicamentosImagem de pause

* Histórico das prescrições exibido na listagem em um único lugar com um design mais prático e moderno.
* Pesquisa de um medicamento já prescrito, com opção de incluir os medicamentos de uso contínuo.

Gif da pesquisa de medicamentosImagem de pause

* Interrupção de um tratamento, bem como cancelar a interrupção.

Gif da interrupção de um tratamentoImagem de pause

* Replicação do receituário completo ou apenas de um medicamento prescrito em uma receita.

Gif da replicação de uma receitaImagem de pause

Pré-natal / puerpério

* Nova interface! O módulo foi redesenhado e agora está ainda mais fácil de usar. Confira nas imagens abaixo as principais alterações:

Pre-natal nas versões antigas

* Pré-natal só pode ser iniciado a partir da avaliação do SOAP. Condições de pré-natal lançadas diretamente na Lista de Problemas/Condições não são consideradas como Atendimento Individual com pré-natal.

Gif do novo pre-natalImagem de pause

Prontuário / folha de rosto

* Nova interface! O módulo foi redesenhado e agora está ainda mais fácil de usar. Confira nas imagens abaixo as principais alterações:

Folha de rosto antiga

* Através de cards, visualização de informações de Escuta Inicial/Pré-atendimento, Últimos contatos, Antecedentes, Medições, Vacinação, Problemas/Condições autorreferidas, Lembretes, Alergias/Reações adversas, Lista de problemas/condições, Resultados de exames, Medicamentos. Os cards são clicáveis e exibem mais informações ao serem abertos.

Gif da folha de rosto durante o atendimentoImagem de pause

* Acesso à Folha de Rosto, Histórico e Vacinação a partir da visualização do prontuário. Na Folha de Rosto da visualização do prontuário há também informações do Plano, incluindo as evoluções odontológicas.

Gif da folha de rosto durante a visualização do prontuarioImagem de pause

Vacinação

* Nova funcionalidade de aprazamento automático de doses.

Gif do aprazamento automatico de dosesImagem de pause

* Visualização de informações da vacina na folha de rosto.

Imagem da visualização de informações de vacina na folha de rosto

Versões de estabilização 4.5

Versão 4.5.15

* Correção de cenário onde não estava sendo possível redefinir ou criar senha de alguns profissionais.

Versão 4.5.13

* Alteração do nome da funcionalidade "Registro anterior" no registro de vacinação para "Transcrição de caderneta", essa alteração foi feita para destacar que essa funcionalidade serve apenas para atualização da caderneta e não gera produção como ocorre no registro tardio.

* Correção de cenário que causava erro na contagem no Relatório de produção de vacinação ao utilizar o filtro personalizado "Vacinação".

* Inclusão dos procedimentos SIGTAP "0202031349 - Teste de biologia molecular para a detecção de marcadores de Mycobacterium leprae, em amostras de biópsia de pele ou de nervos", "0202031357 - Teste qualitativo in vitro, para detecção de Mycobacterium leprae resistente à rifampicina e/ou dapsona e/ou ofloxacino, em pacientes acometidos por hanseníase e com suspeita de resistência a antimicrobianos" e "0214010171- Teste rápido para detecção de anticorpos IgM anti-Mycobacterium leprae".

* Alteração na Ficha e no Atendimento de vacinação, onde agora se torna obrigatório o preenchimento do campo "CPF/CNS do cidadão".

* Adição de alerta de vacinas não recomendadas para gestantes para as doses dos imunobiológicos contra a Covid-19.

* Alteração no formato de primeiro acesso ao sistema para não ser concedido automaticamente na importação do CNES. Para liberar acesso ao sistema, um coordenador ou outro profissional autorizado deverá utilizar a opção "Redefinir senha" no módulo de Profissionais.

Versão 4.5.12

* Inclusão dos procedimentos SIGTAP "0301070210 - Reabilitação de Pacientes Pós Covid-19" e "0301070229 - Reabilitação Cardiorrespiratória de Pacientes Pós Covid-19".

* Ajustes na vacina de Covid-19 Sinovac - Coronavac inativada. Agora é possível realizar aplicações e aprazamentos com este imunobiológico.

* Inclusão do grupo de atendimento "Pessoas de 3 a 4 anos" para registros de vacinação.

Versão 4.5.11

* Correção de erro onde não estava sendo possível aplicar o filtro "Ver agendamentos anteriores" na tela de agendamentos do cidadão.

* Correção de cenário em que os registros no histórico não apresentavam o nome de alguns profissionais cadastrados na instalação.

* Ajustes de desempenho nas impressões dos Relatórios de atendimento individual.

* Inclusão do campo "Observações" nas reservas na agenda.

* Correção no módulo da Agenda do profissional, onde não estava sendo possível navegar no calendário caso a agenda do profissional fosse inativada.

* Ajustes na apresentação dos agendamentos e das reservas na agenda dos profissionais que possuem lotações inativas.

* Correção de cenário onde não estava sendo possível imprimir alguns Atendimentos de pré-natal de cidadãos unificados.

Versão 4.5.10

* Correção de cenário onde a conexão com o serviço do CADSUS estava inoperante.
* Inclusão da dose de reforço (REF) para o imunobiológico COV19 Coronavac - Sinovac/Butantan.
* Correção de erro onde não era possível finalizar alguns atendimentos de vacinação com registros anteriores de vacinação.
* Atualização da tabela INEP conforme o Censo 2021.
* Adicionadas as funcionalidades de visualização e paginação nos agendamentos do cidadão, além da exibição da justificativa e do responsável pelo cancelamento dos agendamentos.
* Ajustes na tela da agenda onde, em monitores com resoluções pequenas, o nome do cidadão não era apresentado corretamente.
* Inclusão dos procedimentos SIGTAP "0101040105 - Dispensação de Suplemento de Ácido Fólico" e "0101040113 - Dispensação de Suplemento de Ferro".
* Inativação do procedimento SIGTAP "0101040067 - Aplicação de Suplementos de Micronutrientes".
* Alteração na ficha de Marcadores de consumo alimentar, onde agora se torna obrigatório o preenchimento do campo "CPF/CNS do cidadão" e retirado o campo "Nome do cidadão".
* Ajustes gerais nos filtros personalizados do Relatório de produção de atividade coletiva.
* Atualização da tabela de referências de países do PEC.
* Nova opção de filtro "Incluir fichas do histórico" na Ficha de Cadastro Domiciliar para incluir o histórico de fichas do domicílio na busca por CPF/CNS.

Versão 4.5.9

Ajustes gerais visando performance.
Alteração nos relatórios de produção e no histórico do cidadão para que o CNS temporário dos profissionais também seja considerado.

Versão 4.5.5

* Correção de cenário onde não era possível realizar um Registro anterior e uma Aplicação do mesmo imunobiológico em um mesmo atendimento de vacinação.
* Ajustes no módulo de Encaminhamentos onde alguns dados dos campos Motivo e Observação eram exibidos parcialmente na impressão.
* Correção de erro onde alguns dados não eram transmitidos corretamente ao Centralizador Nacional em instalações com o Administrador Municipal inativo.
* Melhorias no calendário e otimizações no módulo da Agenda.
* Correção das quantidades divergentes entre o Resumo do cadastro e a Situação sociodemográfica geral no Relatório consolidado da situação do território.

Versão 4.5.4

* Correção de cenário onde alguns dados eram sincronizados de forma incorreta entre o PEC e o aplicativo Atenção Domiciliar.
* Correção de erro onde a data da última consulta RCV aparecia incorreta no Relatório operacional de risco cardiovascular.
* Correção de cenário onde, em alguns casos, não era possível atualizar o PEC para a versão 4.5.3.

• Versão 4.5

Módulos com novidades:

* Agenda
* Agendamentos do cidadão
* Atendimento de vacinação
* Agenda

O módulo de Agenda está de cara nova. A partir desta versão:

* Agendamentos de reservas são apresentados como um único evento.
* Mais agendamentos são apresentado ao mesmo tempo na tela.
* Remoção dos períodos: agora todos os horários do dia são apresentados na mesma tela.

Gif Novidades AgendaImagem de pause

Agendamentos do cidadão

A listagem de agendamentos do cidadão pode ser visualizada em uma nova aba na tela de Visualização de Cadastro de Cidadão.

* A partir desta versão são apresentados todos os agendamentos realizados na mesma instalação, incluindo os agendamentos da Atenção Domiciliar.

Imagem com novidades do módulo Agenda

Atendimento de vacinação

O atendimento de vacinação teve seu visual redesenhando, deixando mais moderno e fácil de usar. Além disso, as seguintes alterações foram realizadas:

* Agora é possível visualizar, através dos cards das doses dos imunobiológicos, quantas vezes esta dose foi aplicada no(a) cidadã(o).

* As legendas de status das doses foram atualizadas para adequar à realidade do profissional no dia a dia.
* Ainda, visando melhorar a organização das funcionalidades, o Registro Anterior, Aprazamento e Aplicação podem ser acessadas por botões exclusivos, que redirecionarão o usuário para a funcionalidade acessada.

Gif Novidades Atendimento de VacinaçãoImagem de pause
