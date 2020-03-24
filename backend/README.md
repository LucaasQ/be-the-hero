*Rota / Recursos*
  *Métodos HTTP*:
  
  *GET*: Buscar uma informação do back-end
  *POST*: Criar uma informação do back-end
  *PUT*: Alterar uma informação do back-end
  *DELETE*: Deletar uma informação do back-end

  *Tipos de parâmetros*
  
  *Query Params*: Parâmetros nomeados enviados na rota após "?" (Filtros, paginação)
  Ex: ?name=Lucas; ?page=2&name=Lucas&Idade=20
  
  *Rote Params*: Parâmetros utilizados para identificar recursos
  Ex: :id;
  
  *Request Body*: Corpo da requisição utilizado para criar ou alterar recursos
_________________________________________________________________________________
_________________________________________________________________________________
*BANDO DE DADOS*

*Driver*: SELECT * FROM users
*Query Builder*: table('users').select('*').where()

*ENTIDADES*:
- ONG
- Caso (indicent)

*FUNCIONALIDADES*:
- Login ONG
- Logout ONG
- Cadastro ONG
- Cadastrar novos casos
- Deletar casos
- Listar casos específicos da ONG
- Listar todos os casos
- Entrar em contato com a ONG