# CadastroDePaciente
Projeto prático para cadastro de pacientes


-- Nota de esclarecimento --
Vale ressaltar que como utilizei mas tempo para fazer o BackEnd do projeto. Não consegui assim me dedicar para terminar 
o restante. No entanto, se essa chance de emprego for entregue a mim, farei o meu melhor para aperfeiçoar essas novas modalidades 
(que até então só tinha a teoria, porém esse projeto me desafiou a por em pratica e fazer descobrir que é com isso que eu quero trabalhar)

-- Conhecimentos adquiridos:
Prática em Angular;
Novos fundamentos em Framewor;
Novas habilidades BackEnd e FrontEnd;
Aperfeiçoamento profissional;

* Porfavor, ignorar os termos 'Cadcliets' em algumas parte do projeto.
* Link do GOOGLE Drive para acesso do projeto ENVIADO POR E-MAIL

-- Itens atendidos:

Validações de campos;
Verificadores de campos;
Tecnologias permitidas utilizadas;
Coerência dos campos e seus tipos (Banco de Dados);
Code Clean;
Boas práticas de programação;

-- Itens não atendidos:

Interação do banco de dados com o front - 
(embora tenha criado todos os itens necessários para o funcionamento);


-- Na parte do banco de dados (SQL Server), todo o esquema de string de conexão, tabela e campos estão no esquema para uso.


-- O sistema possui duas telas. A primeira, exibe todos os pacietes cadastrados enquanto a segunda que através de um
botão é acionada e direciona para a tela que insere as informações do paciente.



-- Back End - API:
1 - Extrair o conteúdo em uma pasta.
2 - Abrir esta pasta no terminal (CMD).
3 - Executar o comando:
	dotnet ef database update
para realizar as migrações no banco de dados.
4 - Executar o comando:
	dotnet run
para executar a API.

-----------------------------------------------------------------------
-- Front End - Angular:
1 - Extrair o conteúdo em uma pasta.
2 - Abrir esta pasta no terminal (CMD).
3 - Executar o comando:
	npm start
para executar o projeto

-----------------------------------------------------------------------
Caso não tenha a CLI do .net Core + EF Core instalada, execute
	dotnet tool install --global dotnet-ef

Caso não tenha a CLI do Angular instalada, execute
	npm i -g @angular/cli
