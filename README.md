# Portuguese-Public-Procurement-Database

Portuguese Public Procurement Database (PPPData) is a dataset, comprised of more than 5000 procurement contracts with 37 distinct properties. PPPData offers a rawdata file in json and a treated in xlsx.
The authors of the database provide additional documentation in order to facilitate de comprehension and manipulation of the publish data.

## Tabela explicativa propriedades dos contratos

|Nome |	Descrição	|Esquema de Codificação	|Unidade de medição|
| ------------- |:-------------:|:-------------:| -----:|
|ID|Número de Identificação|	Inteiro|	N/A|
|Descrição Breve|	Descrição breve do objeto do contrato|	Texto|	N/A|
|Cpvs|	Código Cpvs|	Texto|	N/A|
|Designação Cpvs|	Designação do código Cpvs|	Texto|	N/A|
|Critério Ambiental|	Se o critério ambiental foi considerado no concurso (VERDADEIRO-FALSO)|	Lógico|	N/A|
|Ano de publicação|	Ano de publicação do concurso em Diário da Républica|	Data|	N/A|
|Ano de fecho|	Ano de fecho do processo no Portal Base	Data	N/A|
|País|	País de execução da obra	|Texto|	N/A|
|Município|	Município de execução da obra|Texto|	N/A|
|Distrito|	Distrito da execução da obra	|Texto|	N/A|
|Código de Distrito|	Código identificador de distrito, organizado por ordem alfabética e numerado de 1 a 20	|Inteiro|	N/A|
|Prazo de submissão|	Prazo de submissão da proposta	|Inteiro|	Dias|
|Data de celebração|	Data de celebração do Contrato	|Data|	dd-mm-aaaa|
|Data de fecho|	Data de fecho do processo no Portal Base	|Data|	dd-mm-aaaa|
|Diferença entre data de celebração e fecho|	Diferença entre data de celebração e fecho	|Inteiro|	Dias|
|Prazo de execução|	Prazo previsto para a execução da obra|	Inteiro|	Dias|
|Preço Base|	Preço base para propostas a concurso|	Monetário|	€|
|Preço Inicial|	Preço inicial acordado entre adjudicatário e adjudicante	|Monetário|	€|
|Categoria Preço I.|	1 - Entre 0 e 250 mil; 2 - entre 250 mil e 1 Milhão; 3 – acima de 1 Milhão |	Inteiro|	N/A|
|Preço Efetivo|	Preço efetivo no final da obra|	Monetário	|€|
|Diferença de preço|	Diferença entre preço inicial e preço efetivo|	Monetário|	€|
|Percentagem da Diferença de preço|	Preço Inicial dividido pelo Preço Efetivo	|Percentagem	|Percentagem|
|Critério de adjudicação|	Critério de adjudicação utilizado classificar as propostas durante o concurso público	|Texto|	N/A|
|Categoria do Critério de adjudicação|	1 - Critério multifator; 2 - Critério preço mais baixo; 0 - Critério de adjudicação em falta	|Inteiro|	N/A|
|Classificação do critério multifator|	Peso do fator “preço” no critério multifator|	Percentagem	|Percentagem|
|Caução|	Valor da caução, se aplicável |Alfanumérico	|Percentagem, lógico|
|Publicado no Jornal EU|	Se o contrato foi publicado em jornal da união europeia	|Lógico	|N/A|
|Tipo de fim do contrato|	1 – Cumprimento integral do contrato 2 – Cumprimento não integral do contrato	|Texto|	N/A|
|Número de concorrentes|	Número de concorrentes do concurso	|Inteiro	|N/A|
|Envolve aquisição conjunta|	Se o contrato envolve aquisição por várias entidades (VERDADEIRO-FALSO-N/A)	|Lógico|	N/A|
|Adjudicado por uma central de compras|	Se o contrato foi adjudicado por uma central de compras (VERDADEIRO-FALSO-N/A)|	Lógico|	N/A|
|Celebração de um acordo quadro|	Se o contrato foi celebrado por um acordo quadro (VERDADEIRO-FALSO-N/A)|	Lógico	|N/A|
|Leilão eletrónico|	Se o contrato foi executado com recurso a leilão eletrónico (VERDADEIRO-FALSO-N/A)	|Lógico|	N/A|
|Adotada uma fase de negociação|	Se foi adotada uma fase de negociação (VERDADEIRO-FALSO-N/A)	|Lógico|	N/A|
|Contratação por lotes|	Se a contratação se realizou por lotes (VERDADEIRO-FALSO-N/A)|	Lógico|	N/A|
|Justificação para mudança de prazo|	Justificação para mudança de prazo (formato livre)|	Texto	|N/A|
|Justificação para mudança de preço|	Justificação para mudança de preço (formato livre)	|Texto|	N/A|


## License

MIT License

Copyright (c) 2022 Luís J. Sousa, João Poças Martins and Luís Sanhudo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

All research papers published using this dataset must cite the work of the authors of this project. The correct way to cite this work is provided in the "Citation" section.

