# Literalura

<div align="center">



</div><br>

## Badge

Este é um badge conquistado por ter desenvolvido este projeto com a Alura no programa ONE - "Oracle Next Education" em parceria com a Oracle:

<div align="center">

![Badge](img/badge-literalura.png)

</div>

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/Changrettaa/challenge-literAlura.git
   cd literalura
   ```

2. Configure o banco de dados no arquivo `application.properties`:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/literalura
   spring.datasource.username=seu-usuario
   spring.datasource.password=sua-senha
   spring.jpa.hibernate.ddl-auto=update
   spring.jpa.show-sql=true
   ```

3. Execute o projeto:
   ```bash
   mvn spring-boot:run
   ```

## Estrutura do Projeto

- `br.com.alura.literalura`: Pacote principal do projeto.
  - `principal`: Contém a classe `Principal`, que gerencia a execução da aplicação.
  - `model`: Contém as classes de modelo (`Livro`, `Autor`, `LivroDTO`, `AutorDTO`).
  - `repository`: Contém as interfaces de repositório Spring Data JPA.
  - `service`: Contém as classes de serviço (`ConsumoAPI`, `ConverteDados`).



## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para enviar sugestões, correções de bugs ou melhorias através de issues e pull requests.

