# EAGLE APP | Organizador de Informações para Imposto de Renda em Excel

Planilha desenvolvida no **Microsoft Excel** para centralizar dados cadastrais, informações bancárias e registros de entradas financeiras que podem apoiar a **organização prévia de documentos para a declaração de Imposto de Renda**.

## Sumário

- [Visão geral](#visão-geral)
- [Objetivo](#objetivo)
- [Organização e funcionalidades](#organização-e-funcionalidades)
- [Ferramentas e recursos utilizados](#ferramentas-e-recursos-utilizados)
- [Como utilizar](#como-utilizar)
- [Competências demonstradas e melhorias futuras](#competências-demonstradas-e-melhorias-futuras)
- [Autor e contato](#autor-e-contato)

## Visão geral

O projeto possui informações para a declaração de Imposto de Renda em uma interface organizada no Excel, facilitando o registro e a consulta de dados cadastrais, bancários e financeiros. A planilha possui três áreas principais: TITULAR, INFORMES e NOTAS, além de uma aba auxiliar oculta chamada Bancos. O preenchimento é manual, sem integração com fontes externas ou processamento automático de declarações fiscais.

## Objetivo

Facilitar o registro, a localização e a conferência de informações financeiras e cadastrais utilizadas na preparação da declaração de Imposto de Renda. O projeto busca **centralizar e organizar os dados em uma única planilha**, tornando o processo de preenchimento mais prático, intuitivo e eficiente. Além disso, pretende **padronizar o armazenamento das informações, reduzir possíveis erros de preenchimento e agilizar a consulta aos registros**, proporcionando maior controle e organização dos dados necessários à declaração.


## Organização e funcionalidades

| Aba | Conteúdo|
| --- | ---|
| **TITULAR** | Dados pessoais e de contato; informações sobre alterações cadastrais, cônjuge e residência no exterior. 
| **INFORMES** | Cadastro de até **três registros bancários**, com instituição, valor atual e campo de referência a anexo. 
| **NOTAS** | Registro de entradas financeiras com **DATA**, **CATEGORIA** e **VALOR**. 
| **Bancos** (oculta) | Relação auxiliar de instituições financeiras. | 

### Navegação e apresentação

- Menu lateral com acesso às abas **TITULAR**, **INFORMES** e **NOTAS** por hiperlinks internos.
- Controles visuais **Próximo** e **Voltar** para avançar ou retornar entre as áreas de preenchimento.
- Interface personalizada com identidade visual **EAGLE**, elementos gráficos e campos organizados por finalidade.

**Sobre os anexos:** os campos exibem nomes de documentos, mas os arquivos correspondentes não estão incorporados à planilha analisada. Esses campos funcionam como referências textuais, não como um sistema de armazenamento de comprovantes.

## Ferramentas e recursos utilizados

| Ferramenta ou recurso | Aplicação no projeto |
| --- | --- |
| **Microsoft Excel** | Estruturação das abas, entrada de dados, formatação e interface de navegação. |
| **Tabela do Excel** | Organização e filtragem dos lançamentos na aba NOTAS. |
| **Validação de dados** | Restrição de preenchimento às opções previstas para respostas cadastrais e categorias das entradas. |
| **Fórmula `SOMA`** | Cálculo automático do total dos três valores bancários registrados. |
| **Hiperlinks internos** | Navegação entre telas por menu lateral e controles de avanço/retorno. |


## Como utilizar

1. **Abra o arquivo `.xlsm` no Microsoft Excel**, preferencialmente na versão para desktop, para preservar o comportamento esperado da interface e os recursos de VBA.
2. Na aba **TITULAR**, revise e preencha os dados cadastrais. Utilize as opções **SIM/NÃO** nos campos de seleção.
3. Acesse **INFORMES** pelo menu lateral ou pelo controle **Próximo**. Registre a instituição financeira, o valor atual e, se necessário, o nome do documento correspondente a cada um dos três bancos.
4. Confira o **TOTAL**, calculado automaticamente com base nas três células de valor.
5. Acesse **NOTAS** para incluir registros de entrada com data, categoria e valor. Utilize os filtros da tabela para consultar os lançamentos.
6. Utilize **Próximo**, **Voltar** e o menu lateral para alternar entre as seções.


## Competências demonstradas e melhorias futuras

### Competências evidenciadas

- **Estruturação de informações:** separação de dados cadastrais, bancários e de recebimentos em abas específicas.
- **Padronização da entrada de dados:** uso de validações e de uma tabela com campos e categorias definidos.
- **Cálculo e conferência:** aplicação de uma fórmula de soma para consolidar valores de três registros.
- **Design de interface em Excel:** criação de navegação interna e organização visual orientada ao preenchimento.
- **Organização de uma solução reutilizável:** divisão funcional das informações e preparação para documentação técnica.

### Melhorias futuras

O projeto tem como objetivo evoluir para uma **ferramenta mais completa de organização, análise e simulação do Imposto de Renda**.

As principais melhorias planejadas incluem:

- **Ampliação das funcionalidades:** adicionar controle de dependentes, despesas dedutíveis, bens e dívidas.
- **Automação e validação:** implementar cálculos automáticos, validação de dados e alertas de inconsistências.
- **Gestão financeira aprimorada:** expandir o controle bancário e detalhar rendimentos, impostos retidos e despesas.
- **Dashboard interativo:** desenvolver indicadores, gráficos e análises de rendimentos, deduções e patrimônio.
- **Simulação tributária:** estimar impostos e possíveis restituições, comparando diferentes modalidades de dedução.
- **Melhoria da experiência:** aprimorar a navegação, proteger fórmulas e permitir a atualização dos parâmetros tributários.

## Autor e contato

- **Autor:** Kauã Castro
- **LinkedIn:** [https://www.linkedin.com/in/kauã-castro]
