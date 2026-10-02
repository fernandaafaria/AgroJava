# AGROJAVA - Sistema Integrado de Agronegócio

Sistema desenvolvido em **Java** com base em um documento de requisitos e especificações técnicas para simular o controle de produção agrícola e o monitoramento de talhões de uma propriedade rural. O projeto tem como foco a manipulação de dados estruturados em memória (**arrays unidimensionais e matrizes bidimensionais**) via terminal
## Funcionalidades do Sistema

O sistema possui um menu interativo estruturado com laços de repetição e condicionais, oferecendo os seguintes módulos:

1. **Módulo de Registro de Chuvas (Array Unidimensional - `double[7]`):**
   - Cadastro do volume de chuva (em mm) para os 7 dias da semana (de Segunda a Domingo).
   - Cálculo automático da média semanal de pluviosidade.
   - Identificação e exibição do dia com o maior índice de precipitação.

2. **Mapeamento de Umidade do Solo (Matriz Bidimensional - `double[4][4]`):**
   - Representação da fazenda em uma grade de $4 \times 4$ talhões.
   - Entrada e exibição formatada do mapa de umidade (%) de cada setor.
   - Sistema inteligente de alertas que verifica talhões com umidade abaixo de $30\%$ indicando a necessidade de irrigação imediata.

3. **Relatórios e Menu Interativo (`do-while` & `switch-case`):**
   - Gerenciamento de fluxo validado (impede a exibição de relatórios antes que os dados sejam cadastrados).


## Tecnologias Utilizadas

- **Linguagem:** Java (versão 11 ou superior)
- **Entrada de Dados:** Classe `Scanner` (via terminal)
- **Estruturas de Dados:** Arrays lineares e Matrizes bidimensionais

---

## Como Executar o Projeto

1. Certifique-se de ter o **Java JDK** instalado na sua máquina.
2. Baixe ou clone este repositório.
3. Abra o terminal na pasta onde está o arquivo `Main.java` e compile o programa:
   ```bash
   javac Main.java
