# **Análise de Dados SN Cursos**

## **Otimizando Iniciativas de Capacitação: Um Panorama Detalhado dos Treinamentos em São Paulo**

Bem-vindo(a) ao repositório do projeto "Análise de Dados SN Cursos"! Este relatório dinâmico oferece uma **visão aprofundada e estratégica** sobre o desempenho e o impacto dos treinamentos oferecidos pela SN Cursos em 21 cidades do estado de São Paulo. Nosso objetivo é transformar dados em *insights* acionáveis para otimizar futuras iniciativas de capacitação e planejar a expansão de forma mais inteligente.

---

### **O Desafio da Análise de Treinamentos e Nossos Objetivos**

Diante de um cenário de dados complexo e distribuído geograficamente, o principal desafio foi consolidar e dar sentido a um volume significativo de informações transacionais e cadastrais. Este projeto aborda essa complexidade através de um processo analítico robusto no Power BI, com os seguintes objetivos:

* **Garantir a integridade dos dados:** Assegurar que as informações utilizadas são precisas e confiáveis.
* **Melhorar a eficiência nas consultas:** Otimizar o acesso e o processamento dos dados para análises rápidas.
* **Facilitar a manutenção do banco de dados:** Simplificar a gestão e atualização das informações.

Minha análise começou com a **normalização e anonimização dos dados de clientes**, garantindo a privacidade e a integridade da informação.

---

### **:computer:Tecnologias e Ferramentas Utilizadas**

* **Power BI Desktop**: Desenvolvimento do dashboard, modelagem de dados, Power Query (ETL), e criação de medidas **DAX**.
* **.csv**: Fonte dos dados brutos.
* **Conceitos de Business Intelligence e Análise de Dados:** Aplicação de princípios para extrair e apresentar *insights* de forma eficaz.
* **Conceitos de Otimização de Banco de Dados:** Aplicação de técnicas para garantir a integridade dos dados e eficiência nas consultas.

---

### **A Base da Análise: Conjunto de Dados & Estrutura**

As informações foram cuidadosamente coletadas e estruturadas para permitir uma análise multifacetada:

* **Tipos de Treinamentos:** Quatro categorias distintas de treinamentos.
* **Cursos:** Oito cursos específicos oferecidos.
* **Localidades:** Dados coletados em 21 cidades estratégicas do estado de São Paulo.
* **Métricas Chave:**
    * **Quantidade de Matrículas:** Indicador direto da adesão aos cursos.
    * **Resultado da Arrecadação:** Avaliação financeira da performance dos treinamentos.
    * **Ano Correspondente:** Análise da evolução temporal.

---

### **Explorando os Indicadores: Dashboard de 5 Páginas no Power BI**

O dashboard é composto por 5 páginas intuitivas que permitem uma exploração detalhada do desempenho dos treinamentos, oferecendo *insights* valiosos sobre a demanda dos cursos e a distribuição da adesão:

#### **1ª Página: Introdução**

* Contextualiza o relatório com um texto explicativo.
* Inclui filtros de ano para **2017 e 2018**, permitindo análise temporal.
* Apresenta um **cartão de destaque com o total de arrecadação comparado à meta**, oferecendo uma visão financeira rápida e comparativa.

#### **2ª Página: Resultados x Metas**

* Utiliza um gráfico para **comparar metas e resultados de arrecadação por cidade**.
* Complementado por outros gráficos que mostram a **distribuição por curso**, facilitando a identificação de desempenho em diferentes localidades e ofertas.

#### **3ª Página: Cursos x Cidades**

* Combina gráficos que exibem o **resultado por curso e cidade selecionada**.
* Apresenta um **mapa interativo** com destaque geográfico da localidade selecionada, visualizando a concentração e o impacto dos treinamentos.

#### **4ª Página: Matrículas x Resultados**

* Relaciona o **número de matrículas com os valores arrecadados por curso** utilizando gráficos e filtros.
* Permite entender a eficiência da captação de alunos em relação ao retorno financeiro gerado por cada curso.

#### **5ª Página: Desempenho de Matrículas**

* Mostra um **gráfico com o total de matrículas por curso**.
* Inclui uma medida DAX chave: `Matrícula por Resultado = SUM('2-Base de Dados Resultados Cursos ver'[Resultado de Arrecadação R$])/SUM('2-Base de Dados Resultados Cursos ver'[Matriculas])`, indicando a **arrecadação média por matrícula**.
* Apresenta outro gráfico que indica a **proporção de cursos que atingiram ou não suas metas**, fornecendo um panorama claro do sucesso das iniciativas.

---

### **Impacto e Tomada de Decisão Estratégica**

As informações e *insights* gerados por este relatório são cruciais para a tomada de decisões estratégicas, permitindo à SN Cursos:

* **Otimizar a Oferta de Cursos:** Identificar quais cursos têm maior demanda e onde concentrar esforços.
* **Planejar a Expansão:** Direcionar investimentos para cidades com alto potencial de crescimento ou necessidade de capacitação.
* **Avaliar o ROI (Retorno sobre Investimento):** Compreender a efetividade financeira de cada iniciativa de treinamento.
* **Melhorar Campanhas de Marketing:** Focar em regiões ou tipos de curso com base em dados de adesão e arrecadação.

---

### **Como Acessar o Relatório**

* **Baixe o arquivo-fonte (.pbix):**
    Para uma análise detalhada da modelagem de dados, transformações (Power Query) e o código DAX, você pode baixar o arquivo-fonte do relatório.

---
