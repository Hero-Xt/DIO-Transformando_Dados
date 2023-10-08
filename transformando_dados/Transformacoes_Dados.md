# Documentação das Transformações de Dados
Este documento descreve as transformações de dados realizadas no âmbito do desafio de projeto do Módulo 3, que envolve o Processamento de Dados Simplificado utilizando o Power BI em conjunto com uma instância MySQL na Azure.

# Verificação e Transformação dos Dados
1. Verificação de Cabeçalhos e Tipos de Dados
Ação: Revisão inicial da estrutura do banco de dados.
Justificativa: Garantir consistência nos cabeçalhos e tipos de dados.
2. Conversão de Valores Monetários para Double Preciso
Ação: Alteração do tipo de dados para double preciso nas colunas que representam valores monetários.
Justificativa: Melhor precisão para cálculos e análises financeiras.
3. Remoção de Valores Nulos
Ação: Identificação e eliminação de registros com valores nulos.
Justificativa: Evitar impactos negativos nas análises e garantir a integridade dos dados.
4. Identificação e Tratamento de Employees sem Gerente
Ação: Verificação de nulos em Super_ssn e atribuição do status de gerente para esses casos.
Justificativa: Possíveis gerentes podem não ter Super_ssn atribuído.
5. Verificação de Departamentos sem Gerente
Ação: Identificação de departamentos sem gerente.
Justificativa: Departamentos sem gerente podem impactar análises de estrutura organizacional.
6. Preenchimento de Lacunas em Departamentos sem Gerente
Ação: Atribuição de gerentes fictícios para departamentos sem gerente.
Justificativa: Facilitar análises futuras que dependem da estrutura organizacional.
7. Avaliação do Número de Horas dos Projetos
Ação: Análise do número de horas dedicadas a cada projeto.
Justificativa: Identificação de projetos com possíveis desvios ou excessos de horas.
8. Separação de Colunas Complexas
Ação: Quebra de colunas complexas para simplificar a estrutura.
Justificativa: Melhora na legibilidade e manutenção do modelo.
9. Mescla de Consultas Employee e Department
Ação: Fusão de dados de employee e department para criar tabela employee com nomes de departamentos.
Justificativa: Facilita análises relacionadas à associação entre colaboradores e departamentos.
10. Eliminação de Colunas Desnecessárias
Ação: Remoção de colunas que não contribuem para a análise proposta.
Justificativa: Reduz a complexidade e o volume de dados, melhorando o desempenho.
Passo 4: Junção de Colaboradores e Gerentes
11. Junção de Colaboradores e Gerentes
Ação: Utilização de consulta SQL ou Power BI para unir colaboradores e gerentes.
Justificativa: Necessário para análises que envolvem estrutura hierárquica.
12. Mescle de Nomes e Sobrenomes
Ação: Fusão das colunas de nome e sobrenome em uma única coluna.
Justificativa: Simplificação da estrutura, facilitando análises futuras.
13. Mescle de Nomes de Departamentos e Localizações
Ação: Criação de combinações únicas de departamentos e localizações.
Justificativa: Facilita a criação de um modelo estrela em módulos futuros.
14. Explicação da Mescla em Vez da Atribuição
Explicação: A utilização da mescla é preferível à atribuição porque...
Justificativa: Explique por que a mescla é mais adequada neste contexto específico.
Passo 5: Ajustes Finais
15. Agrupamento de Dados por Gerente
Ação: Agrupamento de dados para saber quantos colaboradores existem por gerente.
Justificativa: Análise da distribuição da força de trabalho por gerente.
16. Eliminação de Colunas Desnecessárias nas Tabelas Finais
Ação: Remoção de colunas irrelevantes para o relatório final.
Justificativa: Melhora na performance e legibilidade do relatório.
Este documento serve como registro das transformações realizadas durante o processamento de dados, garantindo transparência e rastreabilidade nas etapas do projeto.