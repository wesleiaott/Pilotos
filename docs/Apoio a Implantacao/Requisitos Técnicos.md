---
layout: default
title: Requisitos Técnicos
parent: Como implantar
nav_order: 11
has_children: false
has_toc: true
last_modified_date: "01/03/2023"
---

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<link rel="stylesheet" type="text/css" href="../estilos.css">

<h1>Requisitos Técnicos:</h1>

<p>Como qualquer sistema de informação que se prese, a implantação do Prontuário Eletrônico do Cidadão (PEC),
requer o cumprimento de algumas premissas fundamentais, antes de sua adoção. Abaixo, segue o rol de etapas necessárias para à sua adesão: </p>
<br>

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