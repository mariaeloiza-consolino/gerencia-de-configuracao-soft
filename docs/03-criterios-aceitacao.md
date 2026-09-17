## RF-001 - Cadastrar chamado
### Cenário 1 - Cadastro válido
- Dado que título e descrição foram informados;
- quando confirmar o cadastro;
- então o sistema cria o chamado;
- e atribui ID e data de criação.
### Cenário 2 - Dados obrigatórios ausentes
- Dado que título ou descrição estão em branco;
- quando tentar cadastrar;
- então o servidor rejeita com HTTP 400.
## RF-002 - Listar chamados
- com registros: ordenar do mais recente ao mais antigo;
- sem registros: informar que a lista está vazia.