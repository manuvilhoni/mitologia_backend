# mitologia_backend
## Requisitos Funcionais
 
 
1. **Cadastro de Usuários**
 
- Qualquer usuário deve ter acesso ao formulário de cadastro com campos obrigatórios para nome, e-mail, telefone, data de nascimento, endereço (rua, número, complemento, cidade, estado, CEP) e senha.
 
- O site deve se ter validação de e-mail e telefone (ex.: formato correto, e-mail único).
 
 
 
2. **Login de Usuários**
 
- O site deve conter um formulário de login com campos para e-mail ou telefone e senha para qualquer usuário.
 
3. **Admin**
 
 - Os admins devem conseguir gerenciar seus usuários (possibilitando visualizar, editar e deletar usuários).
 
- Os admins devem conseguir gerenciar os itens do mapa (possibilitando visualizar, adicionar, editar e deletar os itens do menu)
 
- Os admins devem conseguir gerenciar as mitologias (possibilitando visualizar, adicionar, editar e deletar)
 
 
3. **Recuperação de Senha**
 
- O site deve conter um formulário de recuperação de senha com os campos nome e email.
 
## Requisitos Não Funcionais
 
1. **Segurança**
 
- Hashing seguro das senhas no banco de dados
 
- O site deve conter diferentes níveis de acesso (usuarios comuns e administradores)
 
- Criptografia de dados (senha).
 
2. **Usabilidade**
 
- O site deve conter a interface de usuário intuitiva e fácil de usar.
 
- O design do site deve ser responsivo para funcionar bem em dispositivos móveis e desktops.
 
- O site deve conter um painel administrativo fácil de usar e navegar.
 
3. **Acessibilidade**
 
- Garantir que o site seja acessível para pessoas com deficiências visuais/ auditivas
 
## Tarefas
 
- [ ] Criar modelo de dados para usuários/admins e mitologias  no banco de dados.
- [ ] Implementar o endpoint para gerenciar usuários.
- [ ] Implementar a ferificação de usuario em cada endpoint.
- [ ] Limitar acesso de endpoints a usuarios e admins.
- [ ] Criar pagina para gerenciar mitologias.# mitologia_backend
