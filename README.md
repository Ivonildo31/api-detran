# api-detran
Api para consulta aos serviços do detran,  

situação de CNH,  

infrações,  

dados do condutor,  

dodos do veículo

# ROTAS

**GET: /driver**: rotorna todos os dados da requisição  

**GET: /driver/tickets**: retorna todas as infrações da requisição  

**GET: /driver/data/:cpf**: retorna os dados do cpf requisitado  

**GET: /ping**: verifica uma conexão de serviços  

**GET: /vehicle/tickets**: retorna as infrações das placas requisitadas  

**GET: /vehicle**: retorna os dados da placa requisitada
