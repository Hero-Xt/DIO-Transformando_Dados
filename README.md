# Desafio de Projeto - Processamento de Dados Simplificado com Power BI

Este desafio tem como objetivo realizar o processamento de dados utilizando o Power BI em conjunto com uma instância MySQL na Azure. A seguir, estão detalhadas as etapas a serem seguidas para alcançar esse objetivo.

# Passo 1: Configuração do Ambiente
- Crie uma instância na Azure para o MySQL.
- Utilize a base de dados disponível no GitHub para criar o banco de dados.

# Passo 2: Integração do Power BI com MySQL no Azure
- Configure a integração do Power BI com o MySQL na Azure.

# Passo 3: Verificação e Transformação dos Dados
- Verifique os cabeçalhos e tipos de dados.
- Modifique os valores monetários para o tipo double preciso.
- Analise e remova valores nulos.
- Identifique e trate employees com nulos em Super_ssn, considerando que podem ser gerentes.
- Verifique se há departamentos sem gerente.
- Preencha as lacunas caso haja departamento sem gerente.
- Avalie o número de horas dos projetos.
- Separe colunas complexas.
- Mescle consultas employee e department para criar uma tabela employee com nomes de departamentos associados aos colaboradores.
- Elimine colunas desnecessárias.

# Passo 4: Junção de Colaboradores e Gerentes
- Utilize consulta SQL ou Power BI para realizar a junção dos colaboradores e seus respectivos gerentes.
- No README, especifique a query SQL utilizada, se aplicável.

# Passo 5: Ajustes Finais
- Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna de nomes de colaboradores.
- Mescle os nomes de departamentos e localizações para criar combinações únicas.
- Explique por que, neste caso, é apropriado utilizar a mescla e não a atribuição.

# Passo 6: Análise Adicional
- Agrupe os dados para saber quantos colaboradores existem por gerente.
- Elimine as colunas desnecessárias em cada tabela, que não serão usadas no relatório final.

