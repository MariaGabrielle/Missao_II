Missao_II
=========

Missão complementar




Limitações

Os arquivos em um repositório CVS não podem ser renomeados a partir do cliente, eles devem ser explicitamente removidos e readicionados. Entretanto, com acesso ao servidor os arquivos podem ser renomeados. No servidor, cada arquivo na estrutura de diretório do cliente possui um equivalente seguido de ,v. Exemplo: o arquivo index.html no cliente é gravado no servidor como index.html,v. A ação de renomear no servidor gera no cliente um processo de exclusão do arquivo antigo e criação de um novo e o histórico de atualizações é mantido.
O protocolo do CVS não permite que os diretórios sejam movidos ou renomeados. Cada arquivo do subdiretório em questão deve ser individualmente removido e readicionado.
Não permite "checkout" reservados (permite que dois usuários alterem o mesmo arquivo ao mesmo tempo) e em alguns casos pode ser mais custoso resolver o conflito do que evitar que ele ocorra.
Alguns dos principais desenvolvedores que trabalharam no CVS são atualmente responsáveis pelo Subversion (SVN)[carece de fontes], lançado no começo de 2004 e cujo objetivo é substituir o CVS ao lidar com algumas de suas limitações.
