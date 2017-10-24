## O que este PR faz?
*Ex.:*

    - Disponibiliza o valor das transações em centavos para evitar problemas de arredondamento;
    - Aumenta cobertura de testes.

## Como verificar se este PR está correto?
*Ex.:*

	- Executar os testes de unidade e integração;
	- Fazer um request para o endpoint /v1/transactions;
	- Verificar se o valor está em centavos;
	- Verificar se o healthcheck retorna 200.

## Possui dependências ou blockers?
- [X] Sim

*Ex.:*

    - Depende do pull request #123 pois este adiciona a coluna valueInCents no barramento de serviço.

- [ ] Não

## Checklist
- [ ] Versão atualizada corretamente nos arquivos de configuração (package.json, change_request.yml e .nuspec);
- [ ] Documentação atualizada;
- [ ] Banco de dados de produção atualizado *(se aplicável)*.
