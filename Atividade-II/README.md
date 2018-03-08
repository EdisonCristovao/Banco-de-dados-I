# Banco-de-dados-II
Repositório para INE5613-04238B

1) Gere uma nova versão (versão 2) de diagrama ER para a definição da questão 1 apresentada na lista
de exercícios anterior, de acordo com os complementos a seguir.
Para cada venda de produtos, a loja de multidepartamentos deseja saber:
- cliente que efetuou a compra, com nome, endereço, telefone e e-mail;
- o produto vendido, com preço de venda, e quantidade vendida;
- dados da venda, contendo cliente que comprou, qual funcionário que o vendeu, além da data, horário
de venda e número da nota fiscal.
As entregas dos produtos na loja também devem ser controladas. Para isso, é necessário armazenar:
- número único de registro da entrega, data, hora e funcionário que a recebeu;
- dados sobre a transportadora, que incluem CNPJ, nome e nome do motorista responsável pela
entrega.
Os funcionários são bonificados pelos cursos que fazem, e para isso alguns dados devem ficar
armazenados no banco de dados. Os dados são:
- nome do curso, área, nota de aproveitamento, nome da instituição onde o curso foi realizado, e a data
de conclusão de cada curso;
- um vendedor é associado a um departamento (que possui código e nome); mas somente deve ser
associado aos departamentos cujo tema esteja associado a algum curso que ele tenha feito.


2) Gere uma nova versão (versão 2) de diagrama ER para as questões 2 e 3 da lista de exercícios
anterior, sem considerar alterações na definição das mesmas.

3) Gere um diagrama ER para a descrição a seguir, utilizando os conceitos vistos até o momento.
“O software que atenderá a cooperativa de laudos será acessado por um conjunto de usuários, não
necessariamente profissionais de saúde. Pelo fato de esses usuários poderem estar localizados em
qualquer parte do mundo, será necessário conhecer o país, a divisão política dentro do país (estado,
província) e a cidade na qual o usuário reside, bem como o seu nome, seu endereço e informações de
contato (cada usuário poderá ter n contatos diferentes, de diferentes tipos – tais como e-mail,
telefones, entre outros). Cada usuário poderá estar relacionado com n estabelecimentos de saúde; cada
estabelecimento de saúde possuirá um nome de registro, um nome fantasia, um número de registro e
um endereço (incluindo país, divisão política e cidade), além de informações de contato.
Todo profissional de saúde registrado no sistema é, obrigatoriamente, um usuário do mesmo. Como
forma de complemento de cadastro, um profissional de saúde possui um número de registro
profissional e uma ou mais especialidades médicas relacionadas (como por exemplo, cardiologia e
neurologia). Da mesma forma, um profissional de saúde está liberado para visualizar e manter dados de
um ou mais estabelecimentos de saúde, desde que seu cadastro especifique essa liberação.
Quando um exame ou procedimento é realizado por um dos estabelecimentos de saúde participantes,
dados como data, paciente, tipo de exame executado (eletrocardiograma, tomografia computadorizada,
entre outros) e observações são persistidas para avaliação posterior. Pelo fato de o mesmo paciente
poder executar diferentes exames durante a sua vida, é necessário manter seus dados cadastrais
atualizados (incluindo nome, sexo, endereço completo e dados de contato). A persistência dos exames
executados será, em um primeiro momento, centralizada: isso quer dizer que todos os exames de todos
os estabelecimentos de saúde serão gravados em um mesmo local.
Exames executados poderão ser laudados pelos profissionais de saúde registrados no sistema. Cada
exame poderá ter até dois laudos vinculados (chamados respectivamente de primeira e segunda
opinião). No caso de um exame ter segunda opinião, esta não poderá ser dada pelo mesmo profissional
de saúde que redigiu a primeira opinião. Um laudo é composto por uma data e uma observação, onde
são registrados os achados e as orientações de tratamento (se for o caso).
Diferentes tipos de exame possuem valores diferentes para execução e redação dos laudos. Esses
valores compõem uma tabela de preços que possui uma vigência (com datas inicial e final de validade).
Uma segunda opinião dada a respeito de um exame é cobrada da mesma forma que uma primeira
opinião.
Por manter dados sensíveis relacionados à saúde de pessoas, o software deverá providenciar um
registro de log para toda e qualquer ocorrência envolvendo dados do paciente, procedimentos e laudos.
Os logs devem incluir data/hora de ocorrência, o responsável pela ocorrência e uma especificação da
ocorrência (inserção, alteração e exclusão de dados). É importante registrar, em caso de alterações,
quais dados foram modificados; em caso de exclusões, quais dados foram removidos da base – uma
identificação única para os dados é suficiente.”
