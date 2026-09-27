# LION APP - Agregador de Dados para IRPF (Excel / WPS Office) 📊🦁

Este repositório contém a solução desenvolvida para o desafio de projeto da **[Digital Innovation One (DIO)](https://dio.me)**. O **LION APP** é uma ferramenta prática, interativa e organizada desenvolvida do zero no Excel/WPS Office para auxiliar no controle, organização e validação de dados financeiros essenciais para a Declaração Anual de Imposto de Renda (IRPF).

---

## 🎯 Objetivos do Projeto
*   **Centralização de Dados:** Reunir em um só lugar todas as informações do Titular (Nome, CPF, Título de Eleitor, etc.), rendimentos e despesas dedutíveis.
*   **Interface Amigável e Portátil:** Criação de um menu de navegação prático com botões funcionais que rodam de forma leve e responsiva.
*   **Integridade da Informação:** Aplicar validações, restrições e máscaras visuais para evitar erros comuns de preenchimento.

---

## 🏗️ Recursos e Soluções Implementadas

A planilha foi estruturada focando em uma experiência de usuário limpa, profissional e totalmente funcional:
*   **Aba Titular:** Organização completa dos dados cadastrais obrigatórios para a declaração (CPF, Título de Eleitor, Contatos, etc.).
*   **Menu de Navegação Inteligente:** Utilização de **Hiperlinks Dinâmicos Diretos nas Células/Botões**. Ao clicar nos botões "Titular", "Informes" ou "Notas", o usuário transita instantaneamente pelas abas e é direcionado para links externos importantes, como o perfil profissional do LinkedIn.
*   **Validação de Dados por Lista (Dropdowns):** Na aba de Notas, a coluna de Categoria foi totalmente automatizada utilizando a Validação de Dados. O usuário conta com um menu de opções travado e padronizado contendo as categorias: **holerite**, **CNPJ** e **freelancer**, garantindo a consistência dos lançamentos.
*   **Tratamento e Formatação:** Aplicação de máscaras de formatação personalizada para CEP, Telefone, Celular e CPF, padronizando a entrada de dados.
*   **Governança e Proteção de Células:** O design, os rótulos de texto e as células contendo fórmulas de soma foram totalmente bloqueados e protegidos. O usuário consegue clicar e modificar exclusivamente os campos amarelos de preenchimento de dados, tornando a ferramenta totalmente à prova de erros acidentais.

---

## 📂 Estrutura do Repositório

```text
├── Capturar.PNG           # Print da interface - Dados do Titular
├── Capturar1.PNG          # Print da interface - Informes de Rendimentos
├── Capturar2.PNG          # Print da interface - Notas Bancárias
├── LION_APP_IRPF.xlsx     # Arquivo principal do projeto Excel protegido
└── README.md              # Documentação oficial do projeto
```

---

## 📸 Capturas de Tela do Sistema

Aqui está a demonstração visual do **LION APP** rodando diretamente na interface de usuário:

### 1. Dados do Titular
Campos de cadastro obrigatórios e máscaras de dados automáticas em funcionamento.
![Dados do Titular](Capturar.PNG)

### 2. Informes de Rendimentos Bancários
Painel com os bancos e o cálculo consolidado de saldos automáticos.
![Informes de Rendimentos](Capturar1.PNG)

### 3. Notas Bancárias e Extratos de Holerites
Controle de entradas mensais com lista de categorias e integrado aos links de navegação rápida.
![Notas Bancárias](Capturar2.PNG)

---

## 🚀 Como Utilizar a Ferramenta

1.  **Download:** Baixe o arquivo `LION_APP_IRPF.xlsx` deste repositório.
2.  **Navegação:** Use os botões com hiperlinks integrados para navegar pelas seções ("Próximo", "Anterior") e acessar os links externos.
3.  **Preenchimento:** Insira seus dados cadastrais e selecione as opções corretas nas listas de categoria (holerite, CNPJ ou freelancer) nas áreas permitidas (células amarelas). O restante do aplicativo está protegido para sua segurança.

---

## 🧠 Aprendizados e Superação Técnica
O maior destaque deste projeto foi a **adaptabilidade técnica**. Diante de barreiras operacionais locais para execução de scripts VBA (Macros), a arquitetura do menu foi completamente redesenhada utilizando hiperlinks nativos de alta portabilidade, validações de listas estruturadas e recursos avançados de proteção de células. Isso garantiu que o projeto funcionasse perfeitamente em qualquer plataforma, simulando o comportamento de um aplicativo real de mercado de forma independente.

---

## 👤 Autor

Desenvolvido por **Amanda Carvalho**  
*   [Meu GitHub](https://github.com)

---
*Este projeto faz parte do bootcamp da DIO. Sinta-se à vontade para dar uma estrela ⭐️ se este repositório te ajudou!*
# lion-app-irpf
