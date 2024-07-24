# Projeto: Indians Diabetes

## Descrição do Projeto

### Objetivo
O objetivo deste projeto é analisar um conjunto de dados de pacientes para identificar aqueles que desenvolveram ou não diabetes e realizar transformações específicas nos dados.

### Etapas do Projeto

1. **Leitura e Exploração dos Dados:**
   - Carregar o arquivo de dados de pacientes.
   - Explorar e entender a estrutura dos dados, verificando a presença de colunas relevantes como idade e BMI (Índice de Massa Corporal).

2. **Filtragem de Pacientes:**
   - Selecionar pacientes com mais de 50 anos.
   - Criar uma nova coluna indicando o status de peso do paciente:
     - **Normal:** BMI menor que 30.
     - **Obeso:** BMI maior ou igual a 30.

3. **Gerar Nova Amostra de Dados:**
   - Construir um DataFrame contendo apenas os pacientes com mais de 50 anos e suas respectivas categorias de BMI.
   - Salvar a nova amostra de dados em um arquivo CSV.

4. **Entrega dos Dados:**
   - Encaminhar o arquivo CSV gerado para o Cientista de Dados responsável pela próxima etapa da análise.

### Ferramentas Utilizadas
- **Python:** Para manipulação e transformação dos dados utilizando bibliotecas como pandas.
- **SQL:** Para consultas e manipulação de dados, se necessário.
- **pandas:** Biblioteca Python essencial para análise e manipulação de dados.
- **CSV:** Formato de arquivo utilizado para armazenar e transferir a amostra de dados gerada.

### Resultados
- Obtenção de um arquivo CSV contendo dados filtrados e categorizados dos pacientes com mais de 50 anos.
- Facilitação do trabalho do Cientista de Dados, fornecendo uma amostra de dados limpa e organizada para análises mais aprofundadas.

### Conclusão
Este projeto demonstra habilidades em manipulação de dados utilizando Python e SQL, além de práticas de preparação de dados para análises avançadas. Ele ilustra a capacidade de transformar dados brutos em informações úteis para a tomada de decisões baseadas em dados.
