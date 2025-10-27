Senac
Curso de Programação







Documentação Funcional e Não Funcional


Equipe: Eduardo, Tiago, Davi e Uelinton










Outubro de 2025

Documentação Funcional

RF001 – Cadastro de Usuários
O sistema deve permitir o cadastro de novos usuários informando nome completo, telefone, e-mail, senha, CPF ou CNPJ. Também deve oferecer a opção de autenticação por reconhecimento facial.
RF002 – Busca de Serviços
O sistema deve permitir a pesquisa de serviços por nome, categoria, preço ou quantidade de reservas realizadas, apresentando os resultados de forma ordenada e filtrável.
RF003 – Realização de Compra
O sistema deve permitir que o usuário selecione e adicione serviços ao carrinho de compras, finalizando o pagamento via cartão de crédito, boleto bancário ou Pix.
RF004 – Emissão de Relatórios
O sistema deve gerar relatórios mensais de vendas contendo lista de serviços vendidos, quantidade total de vendas, valor total e histórico de transações.
RF005 – Alteração de Informações do Usuário
O sistema deve permitir que o usuário edite suas informações pessoais, como endereço, telefone, e-mail e senha, de forma segura e auditável.

Documentação Não Funcional

RNF001 – Desempenho
A busca por serviços deve retornar resultados em menos de 2 segundos, mesmo sob alta demanda (até 1000 requisições por minuto).
RNF002 – Segurança
As senhas devem ser armazenadas com algoritmo de hash seguro (ex.: bcrypt, Argon2). O sistema deve implementar autenticação em dois fatores (2FA) via aplicativo autenticador e garantir conexão HTTPS.
RNF003 – Usabilidade
A interface deve ser intuitiva, responsiva e compatível com os navegadores modernos (Chrome, Firefox e Edge), adaptando-se a diferentes tamanhos de tela.
RNF004 – Confiabilidade
A taxa de falhas do sistema não deve ultrapassar 0,5% ao mês. Em caso de falhas críticas, deve possuir mecanismos de recuperação e registro de logs para auditoria.
RNF005 – Escalabilidade
O sistema deve suportar aumento de até 20% no número de usuários ativos sem degradação perceptível de desempenho, mantendo flexibilidade para expansão futura.
