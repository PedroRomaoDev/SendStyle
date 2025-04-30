
# 🛒 PHPecommerce

![PHP](https://img.shields.io/badge/PHP-7.x-blue)
![Status](https://img.shields.io/badge/status-%20concluído-green)
![Last Commit](https://img.shields.io/github/last-commit/PedroRomaoDev/PHPecommerce)

Projeto de e-commerce desenvolvido em **PHP puro**, utilizando o padrão de arquitetura **MVC (Model-View-Control)**. O sistema permite navegação entre menus de usuário e administrador, organização por camadas e manipulação de banco de dados com MySQL.

---


## 📁 Estrutura de Pastas

```
📦 PHPecommerce
├── Control/         → Lógica de controle da aplicação (Controllers)
├── Model/           → Regras de negócio e acesso ao banco de dados (Models)
├── View/            → Telas e componentes visuais (Views)
├── SQL/             → Scripts e estrutura do banco de dados
├── css/             → Estilos CSS utilizados no front-end
├── js/              → Scripts JavaScript (validações, interações, etc.)
├── img/             → Imagens do sistema
├── uploads/         → Arquivos enviados pelo usuário
├── index.php        → Entrada principal do sistema
├── menuADM.php      → Menu da área administrativa
├── menuUsuario.php  → Menu da área do usuário
└── telainicial.php  → Tela de boas-vindas/inicial
```

---

## ⚙️ Tecnologias Usadas

- PHP (procedural)
- HTML5 + CSS3
- JavaScript
- MySQL
- XAMPP / WAMP para ambiente local

---

## ✅ Funcionalidades Implementadas

- Menu específico para usuário e administrador
- Barra de pesquisa de produtos (nova funcionalidade 💡)
- Estrutura MVC simples e organizada
- Manipulação de banco de dados com MySQL
- Separação entre lógica, interface e dados
- Upload de arquivos e uso de sessões

---

## 🚀 Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/PedroRomaoDev/PHPecommerce.git
   ```

2. Coloque a pasta clonada no diretório do seu servidor local (ex: `htdocs` para XAMPP)

3. Importe o banco de dados:
   - Acesse `phpMyAdmin`
   - Crie um banco de dados (ex: `phpecommerce`)
   - Importe o arquivo `.sql` que está na pasta `SQL`

4. Acesse o projeto no navegador:
   ```
   http://localhost/PHPecommerce/
   ```

---

## 📌 Possíveis Melhorias Futuras

- Refatoração para uso de PHP com orientação a objetos
- Sistema de autenticação e permissões
- Cadastro e gerenciamento de produtos via painel ADM
- Integração com gateway de pagamento (ex: PagSeguro ou Stripe)
- Responsividade com Bootstrap ou Tailwind

---

## 📬 Contato

Desenvolvido por **Pedro Romão**  
[GitHub](https://github.com/PedroRomaoDev) • [LinkedIn](https://www.linkedin.com/in/pedro-rom%C3%A3o-2615572b3/) • pedroromaodev@email.com


