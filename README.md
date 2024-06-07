# API de Monitoramento Oceânico

A API de Monitoramento Oceânico é um sistema desenvolvido para monitorar e relatar eventos e dados relacionados aos oceanos. Ele fornece endpoints para gerenciar alertas, relatórios, biodiversidade e dados oceanográficos.

## Funcionalidades Principais

### Alertas
- Criação, leitura, atualização e exclusão de alertas.
- Consulta de alertas com filtros por tipo, mensagem, data/hora ou localização.

### Relatórios
- Criação, leitura, atualização e exclusão de relatórios.
- Associação de alertas aos relatórios.

### Biodiversidade
- Criação, leitura, atualização e exclusão de registros de biodiversidade.
- Associação de alertas aos registros de biodiversidade.

### Dados Oceanográficos
- Criação, leitura, atualização e exclusão de registros de dados oceanográficos.

## Endpoints

### Alertas
- `GET /alertas`: Retorna todos os alertas ou filtra por tipo, mensagem, data/hora ou localização.
- `GET /alertas/{id}`: Retorna o alerta com o ID especificado.
- `POST /alertas`: Cria um novo alerta com os dados fornecidos no corpo da solicitação.
- `PUT /alertas/{id}`: Atualiza o alerta com o ID especificado com os dados fornecidos no corpo da solicitação.
- `DELETE /alertas/{id}`: Exclui o alerta com o ID especificado.

### Relatórios
- `GET /relatorios`: Retorna todos os relatórios.
- `GET /relatorios/{id}`: Retorna o relatório com o ID especificado.
- `POST /relatorios`: Cria um novo relatório com os dados fornecidos no corpo da solicitação.
- `PUT /relatorios/{id}`: Atualiza o relatório com o ID especificado com os dados fornecidos no corpo da solicitação.
- `DELETE /relatorios/{id}`: Exclui o relatório com o ID especificado.

### Biodiversidade
- `GET /biodiversidade`: Retorna todos os registros de biodiversidade.
- `GET /biodiversidade/{id}`: Retorna o registro de biodiversidade com o ID especificado.
- `POST /biodiversidade`: Cria um novo registro de biodiversidade com os dados fornecidos no corpo da solicitação.
- `PUT /biodiversidade/{id}`: Atualiza o registro de biodiversidade com o ID especificado com os dados fornecidos no corpo da solicitação.
- `DELETE /biodiversidade/{id}`: Exclui o registro de biodiversidade com o ID especificado.

### Dados Oceanográficos
- `GET /dados-oceanicos`: Retorna todos os registros de dados oceanográficos.
- `GET /dados-oceanicos/{id}`: Retorna o registro de dados oceanográficos com o ID especificado.
- `POST /dados-oceanicos`: Cria um novo registro de dados oceanográficos com os dados fornecidos no corpo da solicitação.
- `PUT /dados-oceanicos/{id}`: Atualiza o registro de dados oceanográficos com o ID especificado com os dados fornecidos no corpo da solicitação.
- `DELETE /dados-oceanicos/{id}`: Exclui o registro de dados oceanográficos com o ID especificado.

## Tecnologias Utilizadas
- Java
- Spring Boot
- Spring Data JPA
- Oracle Database
- Maven
## Diagrama
![Diagrama de Classes](https://github.com/caiquealm/GlobalSolution_3Semestre/blob/main/documentacao/GS_OCEANHEALTHMONITORING.png)

## Grupo
- Caique Almeida Dias : RM99778
- Vinicius Rebollo Minei: RM98486
- Sofia Sprocatti : RM99208
- Ana Carolina Tavares	RM: 552283
- Gabriel Lopes Pereira RM: 98023
