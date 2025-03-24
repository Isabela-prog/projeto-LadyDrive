## API sistema de corridas para mulheres


Nessa aplicação teremos um sistema completo de cadastro,ataulização,\
deleção e busca de todos as usuárias,por meio do id e pelo nome (método específico escolhido).
Bem como, para veiculo (método específico será buscar por modelo) e viagens (método específico será buscar por destino).\
Nesse projeto, na classe service, temos a regra de negócio de apenas aceitar que usuários do sexo feminino se cadastrem,\
caso um usuário masculino tente realizar cadastro o sistema irá gerar um erro.\
Não foi implementado o recurso de aceitar apenas motoristas mulheres, pois o projeto pedia apenas uma classe Service para usuários.

## Etapas: 
- [x] Package model (contém as classes que representam as entidades do banco de dados)
- [ ] Fazer modificações no arquivo application.properties - criar bd
- [x] Criar classe Usuário
- [x] Criar classe Veiculo
- [x] Criar classe Viagem
- [x] Atributos Usuário (id, nome, usuario, senha, foto, sexo)
- [x] Atributos Veiculo (id, modelo, placa, cor, motorista)
- [x] Atributos Viagem (id, origem, destino)
- [x] Package repository (classses responsáveis pela persistência de dados usando Spring Data JPA)
- [x] Criar classe UsuarioRepository - buscar por nome
- [x] Criar classe VeiculoRepository - buscar por modelo
- [x] Criar classe ViagemRepository - buscar por destino
- [x] Package controller (classes responsáveis por expor as funcionalidades como endpoints REST)
- [x] Criar classe UsuarioController
- [x] Criar métodos (cadastrar, atualizar, excluir, consultar todos, consultar por id e consultar por nome)
- [x] Criar classe MotoristaController
- [x] Criar métodos (cadastrar, atualizar, excluir, consultar todos, consultar por id e consultar por modelo)
- [x] Criar classe ViagemController
- [x] Criar métodos (cadastrar, atualizar, excluir, consultar todos, consultar por id e consultar por destino)
- [x] Criar relacionamento entre classes - Usuário se relaciona tanto com motorista, como com viagem
- [x] Package Service
- [x] Criar método específico da regra de negócio - aceitar apenas usuários Femininos 
- [x] Testar todos métodos através do Insomnia
</br>

> A parte mais desafiadora do projeto foi criar o método específico da Service.  

</br></br> Esse projeto foi realizado por **Isabela Santos, Abiqueila, Evelyn Santos, Thainara Cruz, Hellen Gleice e Mayte**, no Cruso Java Fullstack Brasil\ 
com intuito de aplicar conhecimentos adquiridos ao longo das aulas.
