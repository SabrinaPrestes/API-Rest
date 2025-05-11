<!DOCTYPE html>
  <h1>Spring Boot 3 - API Rest em Java</h1>

  <p>Esta é uma API desenvolvida durante o curso <strong><a href="https://cursos.alura.com.br/course/spring-boot-3-desenvolva-api-rest-java" target="_blank">Spring Boot 3: Desenvolva uma API Rest em Java</a></strong> da Alura.</p>

  <h2>📚 Sobre o projeto</h2>
  <p>O objetivo desta aplicação é realizar o cadastro, atualização, listagem e exclusão de médicos e pacientes, seguindo as boas práticas de desenvolvimento de APIs REST utilizando Spring Boot 3, Jakarta Persistence API (JPA) e Banco de Dados.</p>

  <h2>🚀 Tecnologias utilizadas</h2>
  <ul>
    <li>Java 17</li>
    <li>Spring Boot 3</li>
    <li>Spring Data JPA</li>
    <li>Banco de Dados MySQL</li>
    <li>Maven</li>
    <li>Hibernate Validator</li>
    <li>Lombok</li>
    <li>Postman</li>
  </ul>

  <h2>🔧 Funcionalidades</h2>
  <ul>
    <li>Cadastro de médicos</li>
    <li>Cadastro de pacientes</li>
    <li>Listagem de médicos e pacientes</li>
    <li>Atualização de dados</li>
    <li>Exclusão lógica (inativação de cadastro)</li>
  </ul>

  <h2>📂 Estrutura básica do projeto</h2>
  <ul>
    <li><strong>Controller:</strong> Camada responsável por receber as requisições.</li>
    <li><strong>Service:</strong> Camada de regras de negócio.</li>
    <li><strong>Repository:</strong> Camada de acesso ao banco de dados.</li>
    <li><strong>Domain/Model:</strong> Representação das entidades.</li>
  </ul>

  <h2>🧪 Testes via Postman</h2>
  <p>O CRUD (Create, Read, Update, Delete) da aplicação é testado utilizando o <strong>Postman</strong>:</p>
  <ul>
    <li><strong>POST</strong> - Criar médicos e pacientes</li>
    <li><strong>GET</strong> - Listar médicos e pacientes</li>
    <li><strong>PUT</strong> - Atualizar informações de médicos e pacientes</li>
    <li><strong>DELETE</strong> - Inativar médicos e pacientes</li>
  </ul>

  <p>As requisições são enviadas em formato <strong>JSON</strong> e a comunicação ocorre diretamente com os endpoints da API.</p>

  <h2>📄 Endpoints principais</h2>
  <ul>
    <li><strong>POST</strong> /medicos - Cadastrar médico</li>
    <li><strong>GET</strong> /medicos - Listar médicos</li>
    <li><strong>PUT</strong> /medicos - Atualizar dados do médico</li>
    <li><strong>DELETE</strong> /medicos/{id} - Inativar médico</li>
    <li><strong>POST</strong> /pacientes - Cadastrar paciente</li>
    <li><strong>GET</strong> /pacientes - Listar pacientes</li>
    <li><strong>PUT</strong> /pacientes - Atualizar dados do paciente</li>
    <li><strong>DELETE</strong> /pacientes/{id} - Inativar paciente</li>
  </ul>

  <h2>✅ Pré-requisitos</h2>
  <ul>
    <li>Java 17 instalado</li>
    <li>MySQL instalado e configurado</li>
    <li>Postman instalado</li>
    <li>Maven instalado (ou suporte na IDE)</li>
  </ul>

  <h2>👨‍💻 Autor</h2>
  <p>Projeto desenvolvido como exercício prático do curso da <strong>Alura</strong>.</p>

</body>
</html>
