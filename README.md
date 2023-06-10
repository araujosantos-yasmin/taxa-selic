**Taxa Selic** *- projeto de análise de dados*

**Objetivo**: Analisar dados fornecidos pelo Portal de Dados Abertos do Banco Central do Brasil sobre a Taxa Selic, de 1986-06-04 a 2023-06-09, em % a.d., visando a extração das seguintes informações:

* Evolução da Taxa Selic segundo períodos de vigências estabelecidos pelo BC, que possuam taxa anualizada (252 dias úteis) de 13.65% a.a. 
* Valores acumulados anuais da Taxa Selic Over de 2019 a 2022.
* Comparação dos valores da Taxa Selic Over dos meses de Maio de 2020 (início da pandemia) e 2023 (fim da pandemia).

**Fonte**: Portal de Dados Abertos do Banco Central do Brasil ( https://api.bcb.gov.br/dados/serie/bcdata.sgs.11/dados?formato=json.)

**Método**: 
- Leitura de arquivo .JSON e análise de dados utilizando linguagem de programação Python, suas bibliotecas e módulos como biblioteca Pandas e Datetime.
- Visualização de dados utilizando a biblioteca Matplotlib da linguagem Python.

**Tópicos do Projeto**:
- Introdução
- Objetivos
- Métodos
- Preparo dos dados
- Extração de informações:
  * Evolução da Taxa Selic segundo períodos de vigência estabelecidos pelo BC
  * Histórico de valores da Taxa Selic Over
   * Valores acumulados anuais da Taxa Selic de 2019 a 2022
   * Comparação do Histórico de valores da Taxa Selic Over (Maio de 2020 e 2023)
- Conclusão
- Referências
