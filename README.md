# ir-facilitado-projeto-excel
Planilha inteligente para pré-declaração de IRPF. Conta com menus de navegação, listas de validação e resumo consolidado para facilitar o preenchimento do programa da Receita Federal

Agregador de Dados para Imposto de Renda: Facilitando a Vida com o Leão
Este é meu segundo projeto prático de Excel, desenvolvido como desafio de laboratório na DIO (Digital Innovation One). Desta vez, o foco foi criar uma ferramenta que resolva um problema real e anual de milhões de brasileiros: a organização de dados para a Declaração de Imposto de Renda.

O Desafio
O objetivo proposto pelo professor Felipe foi construir um agregador de dados que ajudasse o usuário a controlar suas entradas e saídas de maneira eficiente. O desafio pedia uma interface amigável, navegação prática e, principalmente, a validação das informações para evitar erros humanos.

O Que a Planilha Faz?
Como alguém que trabalha com qualidade e processos, busquei criar uma ferramenta onde os dados não ficassem apenas "jogados", mas sim estruturados para o preenchimento direto no programa da Receita Federal.

Estrutura de Abas:
Menu Lateral: Navegação rápida e intuitiva entre todas as seções.

Titular: Centralização de dados pessoais, ocupação e dados bancários para restituição.

Informes: Controle de saldos em contas bancárias com espaço para anexos.

Entradas: Registro mensal de rendimentos (Salários, Aluguéis, Dividendos).

Deduções: Organização de gastos com Saúde, Educação e Previdência.

Resumo Final: O "coração" do projeto. Uma aba que soma tudo automaticamente e diz exatamente em qual campo do programa do IR você deve lançar cada valor.

Minha Experiência de Aprendizado
Neste projeto, meu maior aprendizado foi entender que uma planilha robusta precisa ser à prova de erros. Para isso, explorei conceitos que antes pareciam complexos:

Validação de Dados Dinâmica: Usei uma aba AUXILIAR para criar listas suspensas. Isso garante que, se eu escrever "Salário" na entrada, a fórmula de soma vai encontrar exatamente essa palavra, sem erros de digitação.

A Função SOMASE: Aprendi a "filtrar" o caos. Com essa fórmula, a planilha separa automaticamente o que é rendimento tributável do que é isento, poupando horas de cálculo manual.

UX/UI no Excel: Implementar o menu lateral me ensinou que a aparência da ferramenta é tão importante quanto o cálculo. Se a planilha é bonita e fácil de usar, a chance de manter o controle financeiro atualizado é muito maior.

Como Utilizar
Faça o download do arquivo .xlsx.

Comece preenchendo seus dados na aba TITULAR.

Lance seus ganhos e gastos mensais nas abas ENTRADAS e DEDUÇÕES.

No momento da declaração, basta abrir a aba RESUMO FINAL e copiar os valores para o programa oficial.

Reflexão de Aluno
Este projeto me mostrou que o Excel é muito mais que uma "calculadora de tabelas". É uma ferramenta de organização de pensamento. Documentar esse processo no GitHub está sendo uma experiência nova e incrível de compartilhar minha evolução técnica.

Projeto desenvolvido por Wanderson durante o curso de Excel da DIO. Focado em: Organização, Validação e Eficiência.
