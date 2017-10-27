# CPqD Texto Fala &mdash; SDK para Java  [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

O **CPqD Texto Fala** é um *framework* que permite converter texto genérico, como notícias ou diálogos, em fala. É possível integrar o CPqD Texto Fala nas mais variadas aplicações, desde aplicativos móveis até sistemas de diálogo para telefonia. 

Este repositório contém um projeto Maven contendo dois módulos. O módulo ``synthesizer`` contém o código fonte do pacote necessário para integrar a biblioteca dinâmica (Windows ou GNU/Linux) do **CPqD Texto Fala** em aplicações Java. Já o módulo ``synthesizer-examples`` contém programas de exemplo que demonstram algumas formas de utilizar o **CPqD Texto Fala**.

## Instalação

Baixe o conteúdo do repositório em seu computador usando o comando abaixo:

	# git clone https://github.com/CPqD/tts-sdk-java.git

A instalação do SDK pode ser feita utilizando sua IDE preferida ou via linha de comando usando o programa ``mvn``. A instalação é feita usando o *goal* ``install``.

Para realizar a instalação via linha de comando, acesse o diretório onde o repositório foi clonado e use o comando abaixo:

	# mvn clean install

Será instalado em seu repositório local do Maven o arquivo JAR ``synthesizer-4.1.0-SNAPSHOT.jar``.

## Documentação

A documentação de como utilizar o **CPqD Texto Fala** em uma aplicação Java está disponível em: https://speechweb.cpqd.com.br/tts/docs/4.1/

