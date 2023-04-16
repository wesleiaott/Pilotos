---
layout: default
title: Como implantar
nav_order: 10
has_children: true
description: "Manual e-SUS APS"
permalink: /Como implantar
last_modified_date: "27/02/2023"
---

<h1>Como Implantar:</h1>
  <br>
  <p>Para qualquer sistema de informação que se prese, a etapa de planejamento é fase cruscial na determinação do êxito ou fracasso na adoção de qualquer sistema de informação. Com as soluções de software que compõem a Estratégia e-SUS APS, também não é diferente. Sua adoção, requer o cumprimento de algumas premissas fundamentais, conforme poderá ser visto na ilustração abaixo:</p>
  <br>

  <img src="https://raw.githubusercontent.com/CGIAP-SAPS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/como_implantar.PNG">

  <h5>Etapas para implantação do PEC:</h5>

  <ol>
    <li>Definição do Cenário:</li>
        <p>À definição do cenário, existem basicamente dois tipos de cenários: <b>Descentralizado e o Centralizado</b>. O cenário descentralizado, basicamente corresponde ao modelo clássico de estrutura no qual uma instalação única do PEC (instalação local), existente em um estabelecimento de saúde, serve de base para que computadores clientes dentro da mesma rede corporativa, possam ter acesso de forma compartilhada aos recursos desta instalação, permitindo assim, o compartilhamento do prontuário clínico do cidadão entre os setores e profissionais que atuam na prestação do serviço em saúde.
    <li>Preparação do Ambiente:</li>
        <p>Esta etapa diz respeito ao provimento do aparato tecnológico que sustentará o ambiente que receberá o Prontuário Eletrônico do Cidadão (PEC). Tal ambiente poderá ser sob infraestrutura própria ou utilizando soluções de computação em nuvem. Definem-se informações relevantes, como: hardware, sistema operacional, banco de dados, parametrização da JVM, etc.</p>
    <li>Download e-SUS PEC:</li>
        <p>Download do PEC disponível no Portal da APS. A aplicação encontra-se disponível apenas à arquitetura x64 bits e às plataformas Windows e Linux.</p>
    <li>Instalação e Configuração:</li>
        <p>Após download da aplicação, a próxima etapa diz respeito a instalação propriamente dita do PEC e parametrização do sistema, para que esteja apto à utilização.</p>
    <li>Contra-chave:</li>
        <p>A contra-chave é uma sequência alfanumérica, gerada via e-GESTOR AB, que permite a ativação daquela instalação e uso para transmissão dos dados de produção à Base Federal (SISAB). </p>
    <li>Importação do XML:</li>
        <p>O XML é um arquivo gerado via e-GESTOR AB e que deverá ser importado dentro do PEC para carregamento dos profissionais de saúde que atuarão naquela UBS, suas respectivas lotações, equipes, além das informações do próprio estabelecimento de saúde responsável pela transmissão dos dados. </p>
  </ol>
  

