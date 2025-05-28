# 📋 Descrição do Projeto

Vertice é um sistema bancário completo para gerenciamento de contas, funcionários e clientes, com persistência em banco de dados MySQL. O sistema implementa funcionalidades avançadas como autenticação segura, controle hierárquico de permissões, operações financeiras e geração de relatórios financeiros. Ele foi desenvolvido com base em conceitos sólidos de Programação Orientada a Objetos (POO) e utiliza recursos avançados do banco MySQL, como gatilhos, procedures, views e auditoria para garantir integridade e segurança.

# ⚙️ Funcionalidades Principais

Autenticação segura de usuários (funcionários e clientes) com senha e OTP (One-Time Password).
Gerenciamento de contas bancárias (Poupança, Corrente e Investimento) com operações:
Abertura e encerramento de contas
Depósitos, saques, transferências
Consulta de saldo e extratos
Gestão de funcionários com controle hierárquico e permissões diferenciadas.
Geração de relatórios financeiros exportáveis em Excel e PDF.
Auditoria detalhada de todas as operações críticas para segurança e rastreabilidade.
Persistência robusta usando MySQL com estruturas avançadas:
Gatilhos, stored procedures, views e validações diretamente no banco.
Interface gráfica amigável (tecnologia de front-end à escolha da equipe).

# 📋 Requisitos do Sistema

Funcionais
Login com senha e OTP (válido por 5 minutos).
Controle de tentativas e bloqueio de usuários.
Operações bancárias: abertura, encerramento, depósito, saque, transferência e extrato.
Gestão de funcionários com níveis hierárquicos.
Geração e exportação de relatórios financeiros.
Auditoria de todas as ações relevantes.

Não Funcionais
Desempenho: consultas rápidas (<2 segundos para 1.000 transações).
Segurança: senhas criptografadas, validação no banco.
Usabilidade: interface clara e intuitiva.
Escalabilidade para até 100 contas e 10.000 transações.

# 📚 Tecnologias Utilizadas

Banco de dados: MySQL
Linguagem back-end: Java

📄 Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

