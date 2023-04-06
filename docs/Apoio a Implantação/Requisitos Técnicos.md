---
layout: default
title: Requisitos Técnicos
parent: Apoio a Implantação
nav_order: 11
has_children: false
has_toc: true
last_modified_date: "01/03/2023"
---

<h1>Como Implantar:</h1>

<p>Como qualquer sistema de informação que se prese, a implantação do Prontuário Eletrônico do Cidadão (PEC),
requer o cumprimento de algumas premissas fundamentais, antes de sua adoção. Abaixo, segue o rol de etapas necessárias para à sua adesão: </p>
<br>

<table class="table">
  <thead class="thead-dark">
    <tr>
      <th scope="col" colspan="3">Requisitos mínimos para a instalação do e-SUS APS do tipo Centralizador
Centralizadores Municipais:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Memória RAM - Aplicação:</td>
      <td>8GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>
      <th scope="row">4</th>
      <td>Memória RAM - Banco de Dados:</td>
      <td>16GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>
      <th scope="row">5</th>
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 13000 pontos no PassMark/CPUBenchmark</td>      
    </tr>
    <tr>
      <th scope="row">6</th>
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>
      <th scope="row">7</th>
      <td>Disco BD:</td>
      <td>1 TB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>    
    <tr>
      <th scope="row">9</th>
      <td>Parametrização do PostgreSQL:</td>
      <td>PGConfig 2.0 Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -
XX:MaxMetaspaceSize=1024M -XX:ReservedCodeCacheSize=500M"</td>      
    </tr>
     <tr>
      <th scope="row">10</th>
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>
      <th scope="row">11</th>
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>
     
     
  </tbody>

</table>

<br>
<br>

<table class="table">
  <thead class="thead-dark">
    <tr>
      <th scope="col" colspan="3">Requisitos mínimos para a instalação do e-SUS APS do tipo Centralizador
Centralizadores Estaduais:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Memória RAM - Aplicação:</td>
      <td>8GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>
      <th scope="row">4</th>
      <td>Memória RAM - Banco de Dados:</td>
      <td>32GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>
      <th scope="row">5</th>
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 13000 pontos no PassMark/CPUBenchmark</td>      
    </tr>
    <tr>
      <th scope="row">6</th>
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>
      <th scope="row">7</th>
      <td>Disco BD:</td>
      <td>3 TB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec
Parametrização PostgreSQL: PGConfig 2.0
Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -XX:MaxMetaspaceSize=1024M -XX:ReservedCodeCacheSize=500M"</td>      
    </tr>        
     <tr>
      <th scope="row">10</th>
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>
      <th scope="row">11</th>
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>
     
     
  </tbody>
</table>

<br>
<br>

<table class="table">
  <thead class="thead-dark">
    <tr>
      <th scope="col" colspan="3">Ambiente para até 40 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
  <tr>
      <th scope="row">1</th>
      <td>Usuários simultâneos</td>      
      <td>40</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Ambiente</td>      
      <td>Servidor único para aplicação e banco de dados</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>
      <th scope="row">4</th>
      <td>Memória RAM - Aplicação:</td>
      <td>8GB  Barramento DDR4  Mínimo 1600MHz</td>      
    </tr>    
    <tr>
      <th scope="row">4</th>
      <td>Processador: </td>
      <td>Quad Core 2.20 GHz  Pontuação mínima de 2500 pontos no PassMark/CPUBenchmark</td>      
    </tr>
    <tr>
      <th scope="row">5</th>
      <td>Disco:</td>
      <td>100 GB  Velocidade de escrita mínima 80 MB/seg  Velocidade de leitura mínima 350 MB/sec</td>      
    </tr>            
     <tr>
      <th scope="row">6</th>
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>
      <th scope="row">7</th>
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>

<br>
<br>

<table class="table">
  <thead class="thead-dark">
    <tr>
      <th scope="col" colspan="3">Ambiente para até 100 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Memória RAM - Aplicação:</td>
      <td>8GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>
      <th scope="row">4</th>
      <td>Memória RAM - Banco de Dados:</td>
      <td>8GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>
      <th scope="row">5</th>
      <td>Processador: </td>
      <td>Quad Core 2.20 GHz - Pontuação mínima de 5000 pontos no PassMark/CPUBenchmark  </td>      
    </tr>
    <tr>
      <th scope="row">6</th>
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>
      <th scope="row">7</th>
      <td>Disco BD:</td>
      <td>120 GB - Velocidade de escrita mínima 200 MB/seg - Velocidade de leitura mínima 350 MB/sec</td>      
    </tr>        
     <tr>
      <th scope="row">10</th>
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>
      <th scope="row">11</th>
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>

<br>
<br>


<table class="table">
  <thead class="thead-dark">
    <tr>
      <th scope="col" colspan="3">Ambiente para até 1000 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Memória RAM - Aplicação:</td>
      <td>8GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>
      <th scope="row">4</th>
      <td>Memória RAM - Banco de Dados:</td>
      <td>16GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>
      <th scope="row">5</th>
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 10000 pontos no PassMark/CPUBenchmark </td>      
    </tr>
    <tr>
      <th scope="row">6</th>
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>
      <th scope="row">7</th>
      <td>Disco BD:</td>
      <td>750 GB - Velocidade de escrita mínima 400 MB/seg - Velocidade de leitura mínima 700 MB/sec</td>      
    </tr>   
    <tr>
      <th scope="row">9</th>
      <td>Parametrização do PostgreSQL:</td>
      <td>PGConfig 2.0 Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -XX:MaxMetaspaceSize=1024M -XX:ReservedCodeCacheSize=300M"</td>      
    </tr>
     <tr>
      <th scope="row">10</th>
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>
      <th scope="row">11</th>
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>

<br>
<br>

<table class="table">
  <thead class="thead-dark">
    <tr>
      <th scope="col" colspan="3">Ambiente para até 2500 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Memória RAM - Aplicação:</td>
      <td>16GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>
      <th scope="row">4</th>
      <td>Memória RAM - Banco de Dados:</td>
      <td>16GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>
      <th scope="row">5</th>
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 13000 pontos no PassMark/CPUBenchmark  </td>      
    </tr>
    <tr>
      <th scope="row">6</th>
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>
      <th scope="row">7</th>
      <td>Disco BD:</td>
      <td>1 TB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>   
    <tr>
      <th scope="row">9</th>
      <td>Parametrização do PostgreSQL:</td>
      <td>PGConfig 2.0 Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -
XX:MaxMetaspaceSize=1024M -XX:ReservedCodeCacheSize=300M"</td>      
    </tr>
     <tr>
      <th scope="row">10</th>
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>
      <th scope="row">11</th>
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>

<br>
<br>

<table class="table">
  <thead class="thead-dark">
    <tr>
      <th scope="col" colspan="3">Ambiente para até 4000 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Memória RAM - Aplicação:</td>
      <td>16GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>
      <th scope="row">4</th>
      <td>Memória RAM - Banco de Dados:</td>
      <td>32GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>
      <th scope="row">5</th>
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 15000 pontos no PassMark/CPUBenchmark</td>      
    </tr>
    <tr>
      <th scope="row">6</th>
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>
      <th scope="row">7</th>
      <td>Disco BD:</td>
      <td>2 TB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>   
    <tr>
      <th scope="row">9</th>
      <td>Parametrização do PostgreSQL:</td>
      <td>PGConfig 2.0 Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -</td>      
    </tr>
     <tr>
      <th scope="row">10</th>
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>
      <th scope="row">11</th>
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>
















































</table>
