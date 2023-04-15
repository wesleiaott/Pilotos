---
layout: default
title: Monitoramento PEC
parent: Visão Geral - Pilotos
nav_order: 9
has_children: false
has_toc: true
last_modified_date: "06/04/2023"
---

<link rel="stylesheet" type="text/css" href="../estilos.css">

<h2>Monitoramento e-SUS APS</h2>

<br>

<p>
Para apoiar no monitoramento do Prontuário Eletrônico do Cidadão - PEC que está sendo Pilotado entre os Municípios Pilotos da Estratégia e-SUS APS, o <a href="https://esusaps.freshdesk.com/">Laboratório Bridge </a>  dispõe de uma ferramenta de monitoramento interno que apoia na aferição do desempenho da aplicação, bem como identificação de eventuais gargalos e questões performáticas que ajudam no suporte e otimização da aplicação durante o período de homologação das versões.
<br>

A ativação do monitoramento constitui fator imprescindível a atuação do Suporte Técnico e é item **obrigatório**, conforme termo de compromisso pactuado entre os Municípios Pilotos e o Ministério da Saúde.

<br>

Dúvidas relacionadas a tal recurso poderão ser tiradas no seguinte canal: **piloto.esusab@saude.gov.br**

</p>

1 - Acesse o diretório padrão do PEC -> webserver -> config

2 - Edite o arquivo "application.properties" e insira os seguintes parâmetros:

            spring.boot.admin.client.instance.name=NOME_DO_MUNICIPIO
            spring.boot.admin.client.url=http://pecadm.esusab.ufsc.br
            spring.boot.admin.client.username=bridge-admin-client
            spring.boot.admin.client.password=bridge-admin-client-pass
            spring.boot.admin.client.period=60000
            spring.boot.admin.client.instance.service-url=http://127.0.0.1:8080
            management.endpoints.web.exposure.include=*
            management.endpoint.health.show-details=always
            graflux.enabled=true
            graflux.server=https://graflux.ctn.bridge.ufsc.br

3 - Altere o link de acesso ao PEC no local de http://127.0.0.1:8080 para o link do seu servidor. Caso tenham trocado a porta, colocar também a porta em que estão, exemplo: http://150.168.16.25:80

4 - Liberar tanto o envio quanto o recebimento de requisição para a url de vocês com a porta informada, para o link: http://pecadm.esusab.ufsc.br

5 - Liberar o envio para: https://graflux.ctn.bridge.ufsc.br

6 - Reiniciar o serviço do PEC.

Ferramenta de monitoramento habilitada com **Sucesso!!**

