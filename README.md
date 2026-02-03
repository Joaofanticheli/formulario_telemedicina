# 🏥 Formulário de Pré-Consulta - Telemedicina

Formulário HTML semântico, acessível e validado para plataforma de telemedicina, seguindo padrões WCAG 2.1 e boas práticas de desenvolvimento frontend.

## 📌 Sobre o Projeto
Formulário completo de pré-consulta médica desenvolvido como exercício integrador do módulo de **Formulários e Acessibilidade**. Foca em:
- **HTML Semântico** (tags corretas para cada contexto)
- **Acessibilidade em HTML** (labels corretos, navegação por teclado, `aria-describedby`)
- **Validação Nativa HTML5** (`required`, `pattern`, `min/max`, `type`)
- **Organização de formulários reais** (saúde digital)

## 🛠️ Tecnologias Utilizadas
- **HTML5** (semântico, form validation, novos input types)
- **Acessibilidade** (ARIA labels, fieldset/legend, aria-describedby, navegação por teclado)


## ✨ Funcionalidades Implementadas

### ✅ Validação Nativa
- CPF com máscara (`pattern`)
- Email e telefone com validação nativa
- Campos numéricos com `min/max`
- Datas com restrição de mínimo
- Uploads com `accept` (PDF ou imagem)

### ♿ Acessibilidade (base HTML)
- Navegação por teclado (Tab/Shift+Tab)
- Labels associados a todos os campos(`for`/`id`)
- aria-describedby para textos de ajuda
- Fieldsets e legends para contexto semântico

### 🏗️ Estrutura Semântica
- Seções organizadas com `<fieldset>` e `<legend>`
- Inputs apropriados (`date`, `tel`, `number`, `file`)
- Hierarquia clara de botões (apenas um `type="submit"`)


## 📁 Estrutura do Projeto
formulario_telemedicina/
├── index.html # Formulário principal (HTML puro)
├── README.md # Esta documentação
└── .gitignore # Configurações do Git
