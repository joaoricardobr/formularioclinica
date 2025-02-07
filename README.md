

# Formulário de Paciente - Clínica de Estética

Este repositório contém o código-fonte do site da Clínica de Estética, incluindo um formulário interativo para coleta de informações de pacientes.

## 📌 Recursos e Funcionalidades
- **Formulário Completo**: Captura dados pessoais, histórico médico e procedimentos desejados.
- **Persistência de Dados**: Os dados preenchidos são salvos no `localStorage`, evitando perda ao recarregar a página.
- **Validação de Formulário**: Garante que os campos obrigatórios sejam preenchidos corretamente.
- **Integração com Formspree**: Envia os dados para um endpoint configurado.
- **Encaminhamento para WhatsApp**: Após o envio, uma mensagem formatada é gerada para contato via WhatsApp.
- **Design Responsivo**: Estilizado em azul escuro e dourado, adequado para dispositivos móveis e desktops.

## 🚀 Tecnologias Utilizadas
- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- **Formspree (para recebimento de formulários)**

## 📂 Estrutura do Projeto
```
/
├── index.html  # Estrutura principal do site
├── styles.css  # Estilização da página
├── script.js   # Funções de validação e envio
└── README.md   # Documentação do projeto
```

## 📌 Como Usar
1. Clone este repositório:
   ```sh
   git clone https://joaoricardobr.github.io/formularioclinica
   ```
2. Abra o arquivo `index.html` no navegador.

## 📝 Configuração do Formspree
Para utilizar o Formspree corretamente, altere o `action` do formulário no `index.html` para sua chave de API do Formspree:
```html
<form id="patientForm" action="https://formspree.io/f/sua-chave" method="POST">
```

## 📞 Contato
Este site foi desenvolvido por **João Ricardo, engenheiro de computação**.
- **Instagram**: [@joaoricardo.pe](https://www.instagram.com/joaoricardo.pe)
- **WhatsApp**: [Contato](https://wa.me/)

---
🛠 Desenvolvido com dedicação por João Ricardo 🚀

