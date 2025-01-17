Manual do Bixo - Centro Acadêmico da Computação (CACo)
======================================================

Este é o Manual do Bixo, criado pelo Centro Acadêmico da Computação, CACo,
distribuído aos ingressantes nos cursos de Engenharia e Ciência da Computação
da Unicamp.

Compilando
----------

O build system utilizado é o scons.

 - Para compilar o manual: `scons`
 - Para limpar os arquivos temporários de compilação: `scons --clean`

Dependências:

 - Distribuição de LaTeX (utilize preferencialmente o tex-live)
 - Fonte atual: TeX Gyre Pagella

Como contribuir
---------------

Você pode mandar sugestões na [lista](http://groups.google.com/group/cacounicamp)
de emails do [CACo](www.caco.ic.unicamp.br). Se estiver disposto a contribuir
mais seriamente, você pode abrir issues/forkar esse repositório no github e
mandar pull requests com alterações. Observe as seguintes convenções:

 - **Sempre** teste suas mudanças antes de comitar na branch master
 - Tente manter as linhas com no máximo 80 colunas
 - Comente quaisquer truques de LaTeX ou outras ferramentas que você usar em sua
   contribuição (lembre-se que outras pessoas poderão ter de mexer nisso)
 - Utilize, preferencialmente, um arquivo para cada seção (ou agrupe algumas
   seções no mesmo arquivo), e os inclua no arquivo principal com `\input`
 - Escreva mensagens de commit em português e que resumam o que cada alteração
   representa
 - Evite nomes de arquivos cuja diferença seja apenas a capitalização. Ex:
   `Padaria.png` e `padaria.png` são o mesmo arquivo em um sistema Windows, mas
   não em um \*nix, e a idéia do manual é ser portável
 - Da mesma forma, evite caracteres especiais em nomes de arquivos

Como qualquer lista de regras, elas podem ser quebradas dado um bom argumento =)

Manutenção de versões
---------------------

A cada nova versão completada, criar uma tag no último commit estável seguindo
o padrão "vANO" ANO onde é o ano em que o manual vai ser entregue, com
4 dígitos. E adicionar um pdf pronto na seção de downloads do github.

Tarefas
-------

2016:
+ Arte
  - [ ] Capa
  - [ ] Contra capa

+ Conteúdo:
  - [ ] Atualizar valor médio de aluguel (fazer pesquisa entre alunos)
  - [ ] Atualizar cantinas da Unicamp que abriram e fecharam
  - [ ] Revisar preços (moradia, comida, transporte)
  - [ ] Atualizar seções das entidades
  - [ ] Adicionar mais entidades
  - [ ] Revisar telefones
  - [ ] Revisar links
  - [ ] Spell-checking
  - [ ] Melhorar a documentação interna
  - [ ] Adicionar texto sobre história da computação
  - [ ] Cursos da Casa do Lago
  - [ ] Cursos de Líguas (CEL)
  - [ ] Cursos da FEF
  - [ ] Bolsa trabalho e PAD
  - [ ] Breve descrição AA/AB
  - [ ] Mudança de Catálogo
  - [x] CACo Empresta
  - [ ] Representatividade do CACo
  - [x] Alteração de Matrícula
  - [ ] Asteriscos
  - [x] Salinha
  
