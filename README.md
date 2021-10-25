# FormularioGamaItauTec05
Este é um formulário criado como pré requisito de avaliação para os candidatos que foram aprovados para a terceira faze da trilha preparatória, [Itaú Tech], Turma 05 como parte do processo seletivo para preenchimento de vagas de pessoas com deficiência da instituição Itaú.

DESCRIÇÃO DO PROJETO:
Conforme escopo do projeto, tem-se neste repositório um formulário para a captura de informações pessoais de um usuário, com as seguintes características:
Campos para preenchimento:
• Dados de identificação Pessoal: Nome Completo, CPF, RG, Sexo.
• Dados de EndereçoEndereço/rua/logradouro, Número, Bairro, Cidade, Estado, CEP.
• Dados Contato: E-mail Telefone Fixo, Telefone Celular, 
Todos os campos contam com as melhores práticas de acessibilidade a partir da concepção de desenho universal User Experience, contando com dicas de digitação e devida rotulação dos itens, a título de exemplo da utilização dos atributos Label, Label-aria, placeholder etc.

FUNCIONALIDADES
Em vista de que a regra de negócio do projeto estabelece que os  campos Nome, CPF, Endereço, Numero e Telefone Celular são obrigatórios, considerando a necessidade de evitar o preenchimento equivocado de dados, neste forma foram adotados algumas práticas de Front visando a validação de dados, quais sejam.
• Para a inserção do dado CPF, foram criados 4 campos, veiculados à um Label, com limite de três caracteres nos três primeiros campos e dois caracteres no quarto. Considerando que os campos são obrigatórios com a tag, required, e que CPF no brasil contém necessariamente 11 dígitos, o campo é capaz de eliminar o  erro de quantidade de carácteres, mas sem valida-lo algoritmicamente.
• O mesmo princípio foi adotado nos campos CEP e telefone Celular e Telefone Fixo.

REFERÊNCIAS DE PESQUISA
https://developer.mozilla.org
https://www.gama.academy
https://www.hostinger.com.br/tutoriais
