---
layout: default
title: Apoio à Implantação
parent: Como implantar
nav_order: 0
has_children: false
has_toc: true
last_modified_date: "01/03/2023"
---

<style>
    p{
        text-align:justify;
        font-family:Verdana;
        font-size:12px;
    }    
</style>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>



<nav>
  <div class="nav nav-tabs" id="nav-tab" role="tablist">
    <a class="nav-item nav-link active" id="nav-cenario-tab" data-toggle="tab" href="#nav-cenario" role="tab" aria-controls="nav-cenario" aria-selected="true">Cenário</a>
    <a class="nav-item nav-link" id="nav-ambiente-tab" data-toggle="tab" href="#nav-ambiente" role="tab" aria-controls="nav-ambiente" aria-selected="false">Ambiente</a>
    <a class="nav-item nav-link" id="nav-download-tab" data-toggle="tab" href="#nav-download" role="tab" aria-controls="nav-download" aria-selected="false">Download</a>
    <a class="nav-item nav-link" id="nav-install-tab" data-toggle="tab" href="#nav-install" role="tab" aria-controls="nav-install" aria-selected="false">Instalar e Configurar</a>
    <a class="nav-item nav-link" id="nav-chave-tab" data-toggle="tab" href="#nav-chave" role="tab" aria-controls="nav-chave" aria-selected="false">Contra-chave</a>
    <a class="nav-item nav-link" id="nav-xml-tab" data-toggle="tab" href="#nav-xml" role="tab" aria-controls="nav-xml" aria-selected="false">XML</a>
  </div>
</nav>

<div class="tab-content" id="nav-tabContent">
  <div class="tab-pane fade show active" id="nav-cenario" role="tabpanel" aria-labelledby="nav-cenario-tab">    

  <h4>Definição de Cenário:</h4><br>
  <p>Antes de efetivamente se realizar a implantação do Prontuário Eletrônico do Cidadão (PEC) no ambiente de produção, deve-se preliminarmente, realizar o mapeamento do ambiente, identificar necessidades e de acordo com o cenário proposto, implementar ajustes técnicos de acordo com as especificidades de cada cenário. Abaixo, segue detalhamento técnico de dois tipos principais de arquiteturas: Centralizada e Descentralizada.</p>

  <ul>    
      <li>Arquitetura Descentralizada:</li>
      <br>
      <p>Nesta topologia, uma instalação do e-SUS APS é <b>interna e exclusiva</b> de um determinado estabelecimento de saúde (UBS). Isto significa, que temos um PEC instalado localmente neste ambiente e partir de uma rede compartilhada, é possível que computadores internos a esta rede, posssam acessar simultaneamente aquela instalação e usufruir dos recursos compartilhados daquela instalação. Abaixo, segue ilustração do cenário proposto:</p>
      <br>
      <br>
      <img src="https://raw.githubusercontent.com/CGIAP-SAPS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/pec_descentralizado.PNG">
      <li>Arquitetura Centralizada:</li>
      <br>
      <p>Ao contrário da topologia descentralizada, na arquitetura centralizada, uma instalação do e-SUS APS é <b>externa e compartilhada</b>, podendo vários estabelecimentos de saúde (UBSs), terem acesso simultâneo e em tempo real a aplicação, para o atendimento clínico do paciente; nesta modalidade, tem-se de forma evidente, acesso ao Prontuário Único do Cidadão, no nível municipal. Abaixo, segue ilustração do cenário proposto:</p>
      <br>
      <br>
      <img src="https://raw.githubusercontent.com/CGIAP-SAPS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/pec_centralizado.PNG">
  </ul>
</div>

  <div class="tab-pane fade" id="nav-ambiente" role="tabpanel" aria-labelledby="nav-ambiente-tab">Definir Ambiente</div>
  <div class="tab-pane fade" id="nav-download" role="tabpanel" aria-labelledby="nav-download-tab">Realizar Download</div>
  <div class="tab-pane fade" id="nav-install" role="tabpanel" aria-labelledby="nav-install-tab">Instalar o PEC</div>
  <div class="tab-pane fade" id="nav-chave" role="tabpanel" aria-labelledby="nav-chave-tab">Gerar Contra-Chave</div>
  <div class="tab-pane fade" id="nav-xml" role="tabpanel" aria-labelledby="nav-xml-tab">Gerar XML</div>

</div>

