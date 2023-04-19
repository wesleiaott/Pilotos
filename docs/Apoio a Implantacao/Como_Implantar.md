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
    <a class="nav-item nav-link" id="nav-ambiente-tab" data-toggle="tab" href="#nav-ambiente" role="tab" aria-controls="nav-ambiente" aria-selected="false">Preparar Ambiente</a>
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

  <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#carouselExampleIndicators" data-slide-to="1" class="active"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>    
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img class="d-block w-100" src="https://raw.githubusercontent.com/CGIAP-SAPS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/pec_descentralizado.PNG" alt="Primeiro Slide">      
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="https://raw.githubusercontent.com/CGIAP-SAPS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/pec_descentralizado_02.PNG" alt="Segundo Slide">
      </div>    
  </div>

    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Anterior</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Próximo</span>
    </a>
    
  </div>
      <li>Arquitetura Centralizada:</li>
      <br>
      <p>Ao contrário da topologia descentralizada, na arquitetura centralizada, uma instalação do e-SUS APS é <b>externa e compartilhada</b>, podendo vários estabelecimentos de saúde (UBSs), terem acesso simultâneo e em tempo real a aplicação, para o atendimento clínico do paciente; nesta modalidade, tem-se de forma evidente, acesso ao Prontuário Único do Cidadão, no nível municipal. Abaixo, segue ilustração do cenário proposto:</p>
      <br>
      <br>
      <img src="https://raw.githubusercontent.com/CGIAP-SAPS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/pec_centralizado.PNG">
      <br>
      <h4>Considerações:</h4>
      <br>
      <p>A adoção de uma arquitetura ou outra, irá depender basicamente da necessidade do município. Lembrando-se que quanto mais estabelecimentos de saúde conectados a uma instalação PEC, mais robusto deverá ser o hardware que sustentará aquele ambiente, sob risco da aplicação declinar em termos de performance e apresentar lentidão na sua operacionalização.</p>
  </ul>
</div>

  <div class="tab-pane fade" id="nav-ambiente" role="tabpanel" aria-labelledby="nav-ambiente-tab">
  
  <h1>Prepação do Ambiente:</h1>
  <br>
  <p>Esta etapa diz respeito ao provimento do aparato tecnológico que sustentará o ambiente que receberá o Prontuário Eletrônico do Cidadão (PEC). Tal ambiente poderá ser sob infraestrutura própria ou utilizando soluções de computação em nuvem. Definem-se informações relevantes, como: hardware, sistema operacional, banco de dados, parametrização da JVM, etc.</p>
  <br>

  <h4>Sistema Operacional:</h4>

  <table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Sistemas Operacinais Compatíveis:</th>            
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>Microsoft Windows</td>
      <td>
          Windows 7<br>
          Windows 8<br>
          Windows 10<br>
          Windows Server<br>
	    </td>      
    </tr>   
     <tr>      
      <td>GNU/LINUX</td>
      <td>
          Debian<br>
          Ubuntu<br>
          Red Hat<br>
          CentOS<br>
	    </td>      
    </tr>     
  </tbody>
</table>

  <h4>Instalação do JAVA:</h4>

  <h4>Especificações de Banco de Dados:</h4>
  
  <h4>Especificações técnicas de hardware, por acessos simultâneos:</h4>

<table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Requisitos mínimos para a instalação do e-SUS APS em Centralizadores Municipais:</th>            
    </tr>
  </thead>

  <tbody>
    <tr>      
      <td>Ambiente</td>    
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Aplicação:</td>
      <td>8GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Banco de Dados:</td>
      <td>16GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>      
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 13000 pontos no PassMark/CPUBenchmark</td>      
    </tr>
    <tr>      
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>      
      <td>Disco BD:</td>
      <td>1 TB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>    
    <tr>      
      <td>Parametrização do PostgreSQL:</td>
      <td>PGConfig 2.0 Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -
XX:MaxMetaspaceSize=1024M -XX:ReservedCodeCacheSize=500M"</td>      
    </tr>
     <tr>      
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>      
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>
     
     
  </tbody>

</table>

<br>
<br>

<table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Requisitos mínimos para a instalação do e-SUS APS em Centralizadores Estaduais:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>      
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>      
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Aplicação:</td>
      <td>8GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Banco de Dados:</td>
      <td>32GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>      
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 13000 pontos no PassMark/CPUBenchmark</td>      
    </tr>
    <tr>      
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>      
      <td>Disco BD:</td>
      <td>3 TB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec
Parametrização PostgreSQL: PGConfig 2.0
Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -XX:MaxMetaspaceSize=1024M -XX:ReservedCodeCacheSize=500M"</td>      
    </tr>        
     <tr>      
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>      
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>
     
     
  </tbody>
</table>

<br>
<br>

<table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Ambiente para até 40 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
  <tr>      
      <td>Usuários simultâneos</td>      
      <td>40</td>
    </tr>
    <tr>      
      <td>Ambiente</td>      
      <td>Servidor único para aplicação e banco de dados</td>
    </tr>
    <tr>      
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Aplicação:</td>
      <td>8GB  Barramento DDR4  Mínimo 1600MHz</td>      
    </tr>    
    <tr>      
      <td>Processador: </td>
      <td>Quad Core 2.20 GHz  Pontuação mínima de 2500 pontos no PassMark/CPUBenchmark</td>      
    </tr>
    <tr>      
      <td>Disco:</td>
      <td>100 GB  Velocidade de escrita mínima 80 MB/seg  Velocidade de leitura mínima 350 MB/sec</td>      
    </tr>            
     <tr>      
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>      
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>

<br>
<br>

<table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Ambiente para até 100 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>      
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>      
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Aplicação:</td>
      <td>8GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Banco de Dados:</td>
      <td>8GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>      
      <td>Processador: </td>
      <td>Quad Core 2.20 GHz - Pontuação mínima de 5000 pontos no PassMark/CPUBenchmark  </td>      
    </tr>
    <tr>      
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>      
      <td>Disco BD:</td>
      <td>120 GB - Velocidade de escrita mínima 200 MB/seg - Velocidade de leitura mínima 350 MB/sec</td>      
    </tr>        
     <tr>      
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>      
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>

<br>
<br>


<table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Ambiente para até 1000 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>      
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>      
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Aplicação:</td>
      <td>8GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Banco de Dados:</td>
      <td>16GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>      
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 10000 pontos no PassMark/CPUBenchmark </td>      
    </tr>
    <tr>      
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>      
      <td>Disco BD:</td>
      <td>750 GB - Velocidade de escrita mínima 400 MB/seg - Velocidade de leitura mínima 700 MB/sec</td>      
    </tr>   
    <tr>      
      <td>Parametrização do PostgreSQL:</td>
      <td>PGConfig 2.0 Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -XX:MaxMetaspaceSize=1024M -XX:ReservedCodeCacheSize=300M"</td>      
    </tr>
     <tr>      
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>      
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>

<br>
<br>

<table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Ambiente para até 2500 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>      
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>      
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Aplicação:</td>
      <td>16GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Banco de Dados:</td>
      <td>16GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>      
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 13000 pontos no PassMark/CPUBenchmark  </td>      
    </tr>
    <tr>      
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>      
      <td>Disco BD:</td>
      <td>1 TB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>   
    <tr>      
      <td>Parametrização do PostgreSQL:</td>
      <td>PGConfig 2.0 Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -
XX:MaxMetaspaceSize=1024M -XX:ReservedCodeCacheSize=300M"</td>      
    </tr>
     <tr>      
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>      
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>

<br>
<br>

<table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Ambiente para até 4000 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>      
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>      
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Aplicação:</td>
      <td>16GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Banco de Dados:</td>
      <td>32GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>      
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 15000 pontos no PassMark/CPUBenchmark</td>      
    </tr>
    <tr>      
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>      
      <td>Disco BD:</td>
      <td>2 TB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>   
    <tr>      
      <td>Parametrização do PostgreSQL:</td>
      <td>PGConfig 2.0 Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -</td>      
    </tr>
     <tr>      
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>      
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>
  
  
  
  
  
  </div>






































  
  <div class="tab-pane fade" id="nav-download" role="tabpanel" aria-labelledby="nav-download-tab">Realizar Download</div>
  <div class="tab-pane fade" id="nav-install" role="tabpanel" aria-labelledby="nav-install-tab">Instalar o PEC</div>
  <div class="tab-pane fade" id="nav-chave" role="tabpanel" aria-labelledby="nav-chave-tab">Gerar Contra-Chave</div>
  <div class="tab-pane fade" id="nav-xml" role="tabpanel" aria-labelledby="nav-xml-tab">Gerar XML</div>

</div>

