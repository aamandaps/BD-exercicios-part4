# DER - Normalização

### 1. Aplicar as Formas Normais cabíveis, nas questões abaixo. Você deve transformar os esquemas abaixo em conjuntos de esquemas que estejam nas Formas Normais.

1) Empregado {Número Empregado. Nome do Empregado, Número do Departamento, Nome do
Departamento, Número do Gerente, Nome do Gerente, Número do Projeto, Nome do Projeto,
Dia de Início do Projeto. Número de horas trabalhadas no projeto).

2) Ordem_Compra (cod_ordem_compra, dt_emissão, cod_fornecedor, nome_fornecedor,
endereço_fomecedor (logradouro, número, complemento, cidade), cod_material (n vezes),
descrição_material (n vezes), qtd_comprada (n vezes), vl_unitario (n vezes), vl_total_item (n
vezes), vl_total_ordem).

3) Tabela de Notas Fiscais (Num_NF, Série, Data emissão, Cod. Cliente, Nome cliente, Endereço
cliente (Logradouro, número de porta), CPF cliente, Código Mercadoria, Descrição Mercadoria.
Quantidade vendida, Preço de venda. Total da venda da Mercadoria e Total Geral da Nota).
Obs.: Cada nota pode ter mais do que uma mercadoria.

4) Inscrição (Código do Aluno, Nome do Aluno, Telefone para contato, Ano de Admissão, Código
da Disciplina, Nome da Disciplina, Nome do Curso, Data da Matrícula).

5) Paciente (num_paciente, nome_paciente, num_quarto, descrição_quarto, num_cômodos_
quarto, {cód_médico, nome_ médico, fone_ médico}).

   * Considere os termos entre chaves ({}) ou descritos com (n vezes) como multivalorados

***

### 2) Considere as situações abaixo e aplique até a 5FN, podendo representar a normalização no Modelo de Dados Relacional ou Modelo Entidade Relacionamento.
