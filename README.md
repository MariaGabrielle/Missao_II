Missao_II
=========

Missão complementar


Terminologia

A terminologia do CVS considera um projeto (conjunto de arquivos relacionados) gerenciados pelo CVS como um módulo, que consiste em uma hierarquia de diretórios contendo os arquivos do projeto. Um servidor CVS pode gerenciar diversos módulos; ele armazena todos os módulos administrados por ele em seu repositório. A cópia do módulo que foi baixada para um cliente é chamada cópia de trabalho (ou checkout).
Abaixo, estão listados alguns termos em inglês, que fazem parte da terminologia CVS, e seu significado:
Checkout: normalmente é usado para denominar o primeiro download de um módulo inteiro a partir do repositório CVS.
Commit: envio das modificações feitas pelo usuário ao repositório CVS.
Export: é o download de um módulo inteiro a partir de um repositório CVS, sem os arquivos administrativos CVS. Módulos exportados não ficam sob controle do CVS.
Import: geralmente é usado para designar a criação de um módulo inteiro dentro de um repositório CVS através do upload de uma estrutura de diretórios.
Module: é uma hierarquia de diretórios. Geralmente um projeto de software existe como um simples módulo dentro do repositório.
Release: é a versão de um produto inteiro.
Revision: é a numeração atribuída pelo CVS a cada modificação de um arquivo.
Tag: é um nome simbólico dado para um conjunto de arquivos em um instante específico durante o desenvolvimento.
Branch: é uma ramificação no desenvolvimento, usada para descrever o processo de divisão dos arquivos de um projeto em linhas de desenvolvimento independentes. Podendo servir para teste de uma nova funcionalidade ou para projetos destinados a um cliente específico.
Update: atualização da cópia local do trabalho através do download das modificações feitas por outros usuários no repositório.
Merge: é a fusão de modificações feitas por diferentes usuários na cópia local de um mesmo arquivo. Sempre que alguém altera o código, é necessário realizar um update antes do commit, de modo que seja feito o merge — ou a fusão — das mudanças.

