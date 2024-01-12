# 1.introdução
Vamos agora desbravar as nuances do diagrama de controle de chaves, desvendando os segredos por trás da gestão inteligente de acessos e compartilhando conhecimentos essenciais para a construção de ambientes mais seguros e organizados.
Ao longo deste documento, exploraremos não apenas os aspectos técnicos do diagrama, mas também seu impacto prático em situações do dia a dia. Seja você um desenvolvedor que busca insights para implementar um sistema eficiente, um gestor preocupado com a segurança do local ou um usuário final envolvido na operação diária, esta jornada visa fornecer uma compreensão aprofundada do controle de chaves e sua importância crescente.

#  1.1 Finalidade
Este documento possui como finalidade trazer questões relacionadas à implementação arquitetural do projeto controle de chaves, idealizado na disciplina Análise e Projeto de Sistemas, que possui como cliente principal a direção da escola IFPI - Campus Angical.Portanto, a importância desse documento reside na sua capacidade de fornecer uma visão clara e concisa do sistema de controle de chaves, promovendo uma implementação eficiente, segura e satisfatória para todas as partes envolvidas.

# 1.2 Escopo
O diagrama a seguir de controle de chaves é uma representação visual que prorciona uma visão abrangente e organizada de como um sistema gerencia o acesso e a posse das chaves em um determinado ambiente.

![92ea6c16-7df6-4b53-905a-9bc7ff10ebd2](https://github.com/kemellyamorim/monitoria/assets/144693858/cb970457-73d2-4759-90ba-c18dffc3916a)


# 2.1 Atores de Casos de Uso

|Ator|Descrição|
|---|---|
|Adm(Diretor)|O adm irá manter os dados do corpo docente, dos alunos e poderá consultar os dados dos alunos|
|Aluno|O aluno irá registrar sua entrada e saída e poderá consultar seus dados| 
|Responsável|O responsável pode consultar os dados do aluno e será notificado da sua entrada e saída|
|Professor|O professor pode consultar dados dos alunos e gerar notificação|
|Secretário|O secretário pode registrar nota e consultar dados dos aluno|

# 2.2 Descrições de Casos de Uso

|Caso de Uso|Descrição|
|---|---|
|UC01 - Manter alunos|Criar, alterar ou deletar um aluno.|
|UC02 - Registrar advertência|Registrar uma nova advertência para um aluno.|
|UC03 - Registrar suspensões|Registrar uma nova suspensão para um aluno.|
|UC04 - Registrar notificação|Registrar notificação para aluno.|
|UC05 - Manter Responsáveis|Criar, alterar ou deletar um responsável de um aluno|
|UC06 - Consultar aluno|Fazer a busca pelo o histórico de um aluno.|
|UC07 - Visualizar número de faltas|Acessar o número de faltas de um determinado aluno.|
|UC08 - Visualizar Boletim|Acessar o boletim de um determinado aluno.|
|UC09 - Visualizar advertências/suspensões|Acessar o número de advertências/suspensões de um determinado aluno.|
|UC10 - Dar nota|Adicionar notas dos alunos.|
|UC11 - Registrar entrada/saída|Registrar a hora de entrada ou saída do aluno.|
|UC12 - Notificar os Responsáveis|Mandar SMS para os responsáveis após entrada/saída do aluno.|
|UC13 - Manter corpo docente|Criar, alterar ou deletar um membro do corpo docente.|
|UC14 - Fazer login|Acessar funcionalidades do sistema.|

# 3.visão

# 3.1 Classe
![Cópia do Diagrama sem nome drawio](https://github.com/kemellyamorim/monitoria/assets/144693858/23c04ddd-b0ce-475a-b005-e04d3de93951)
# 3.2 Colaboração entre Classes

O objetivo deste tópico é apresentar as principais colaborações entre as classes para executar suas funções dentro do sistema.
# 3.1.2 Cartão CRC
![286593002-7b22b4ca-7a65-4f97-a48c-3f350cdaa593](https://github.com/kemellyamorim/monitoria/assets/144693858/2d4d9617-0195-4c72-a28e-b07528792c0f)
# 3.2.2 Lógica das Responsabilidades
Classe: Posse
Responsabilidade: cadastrar() - Cadastrar a posse de uma chave para um usuário.

* Criar um objeto usuário com os dados repassados.
* Criar um objeto chave com os dados repassados.
* Verificar se o usuário existe
* Verificar se a chave existe
* Verificar se a chave está disponível
* Verificar autorização do usuário para posse da chave
* Footer

* Responsabilidade**:emAberto()- Listar





