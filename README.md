# 📝 Formulário de Inscrição – IPA (Igualdade Para o Oeste)

Um formulário moderno, acessível e responsivo para novos sócios se juntarem à **Igualdade Para o Oeste**, uma associação comprometida com a promoção da igualdade e dos direitos humanos na região Oeste de Portugal.

---

## 🌟 Principais Características

- 🎨 **Design Moderno**: Interface limpa e profissional com Tailwind CSS  
- 📱 **Responsivo**: Total compatibilidade com desktop, tablet e mobile  
- ⚡ **Validação em Tempo Real**: Verificação instantânea de campos e emails  
- 💬 **Integração com WhatsApp**: Convite automático para a comunidade  
- 🔒 **Processamento Seguro**: Dados enviados via Formspree, sem backend  
- ✅ **UX Aprimorada**: Feedback visual e mensagens de sucesso personalizadas

---

## 🚀 Funcionalidades

### 📋 Recolha de Dados
- **Pessoais**: Nome civil/social, contactos, morada  
- **Adicionais**: Data/local de nascimento, NIF, formação, profissão  
- **Pagamentos**: Preferência entre Transferência, MB WAY e Multibanco  
- **RGPD**: Consentimentos explícitos para dados e comunicações  

### ✅ Validações Automáticas
- Confirmação de email (campos devem coincidir)  
- Formatação automática de NIF e telefone  
- Campos obrigatórios claramente identificados  

### 🎉 Pós-Submissão
- Mensagem de sucesso personalizada  
- Convite automático para grupo no WhatsApp  
- Notificação por email para a organização  

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** – Estrutura semântica  
- **Tailwind CSS** – Framework utilitária para estilos responsivos  
- **JavaScript Vanilla** – Funcionalidade leve e direta no cliente  
- **Formspree** – Processamento seguro de formulários  
- **Google Fonts (Inter)** – Tipografia moderna e legível  

---

## ⚙️ Como Usar

### 1. Clonar o Repositório
```bash
git clone https://github.com/[seu-username]/formulario-ipa.git
cd formulario-ipa
open index.html  # ou abrir manualmente no browser
````

### 2. Personalizar

No ficheiro `index.html`:

* **Alterar o endpoint do formulário**
  Linha **\~200** → Substituir pelo ID do seu formulário Formspree

* **Atualizar o link do WhatsApp**
  Linha **\~400** → Inserir link da sua comunidade

* **Customizar o design com Tailwind CSS**
  Principais classes para alterar:

  * `bg-blue-600` – Cor principal dos botões
  * `text-blue-600` – Cor dos elementos em destaque
  * `bg-gradient-to-br from-blue-50 to-indigo-100` – Fundo do formulário

---

## 📱 Responsividade

O layout adapta-se automaticamente:

| Dispositivo               | Layout                                      |
| ------------------------- | ------------------------------------------- |
| **Desktop (≥1024px)**     | Duas colunas, agrupando campos relacionados |
| **Tablet (768px–1023px)** | Layout misto, otimizado                     |
| **Mobile (<768px)**       | Layout em coluna única                      |

---

## 🔒 Privacidade e Segurança

* **Conformidade com RGPD**: Inclui consentimentos explícitos
* **Formspree**: Processamento seguro via HTTPS
* **Sem Armazenamento Local**: Dados não são guardados no frontend
* **Validações Client-side**: Antes de qualquer envio

---

## 📧 Configurar Email com Formspree

1. Criar conta em [formspree.io](https://formspree.io)
2. Criar novo formulário e copiar seu Form ID
3. Substituir `manboonn` no HTML pelo seu Form ID
4. Confirmar o email de destino
5. O formulário envia os seguintes campos:

| Campo               | Descrição                          |
| ------------------- | ---------------------------------- |
| `email`             | Email principal do sócio           |
| `nome_civil`        | Nome legal                         |
| `nome_social`       | Nome preferido (opcional)          |
| `morada`            | Endereço completo                  |
| `localidade`        | Cidade/Vila                        |
| `data_nascimento`   | Data de nascimento                 |
| `naturalidade`      | Local de nascimento                |
| `nif`               | Número de contribuinte             |
| `telefone`          | Número de contacto                 |
| `email_confirmacao` | Campo de confirmação de email      |
| `habilitacoes`      | Grau de formação                   |
| `profissao`         | Área profissional                  |
| `forma_pagamento`   | Método de pagamento escolhido      |
| `autorizacao_dados` | Consentimento para tratamento RGPD |
| `comunicacoes`      | Aceita comunicações (opcional)     |

---

## 🎨 Guia de Estilo

### Paleta de Cores

```css
/* Cores principais usadas */
--blue-primary: #2563eb;    /* Tailwind blue-600 */
--blue-hover: #1d4ed8;      /* Tailwind blue-700 */
--green-success: #10b981;   /* Tailwind green-500 */
--gray-text: #374151;       /* Tailwind gray-700 */
```

### Ícones

* SVG inline para performance otimizada
* Uso de [Heroicons](https://heroicons.com), compatível com Tailwind
* Ícone do WhatsApp incluído

---

## 🌐 Deploy

### GitHub Pages

1. Fazer push do projeto para GitHub
2. Ir a **Settings > Pages**
3. Selecionar a branch `main`
4. O site ficará disponível em:
   `https://[username].github.io/[repo-name]`

### Netlify (alternativa)

1. Conectar repositório GitHub
2. Deploy automático a cada commit
3. Suporte para domínio personalizado

---

## 🤝 Contribuições

Contribuições são bem-vindas!

1. Faça um fork deste repositório
2. Crie uma branch:

```bash
git checkout -b feature/nova-funcionalidade
```

3. Commit das suas mudanças:

```bash
git commit -m "Adiciona nova funcionalidade"
```

4. Push para o seu repositório:

```bash
git push origin feature/nova-funcionalidade
```

5. Abra um Pull Request

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License**. Consulte o ficheiro `LICENSE` para mais detalhes.

---

## 📞 Contacto

**Igualdade Para o Oeste (IPA)**
🌐 Site: [somosipa.pt](https://somosipa.pt)
📧 Email: [geral@somosipa.pt](mailto:geral@somosipa.pt)
💬 WhatsApp: [+351 914 096 818](https://wa.me/351914096818)

---

## 🙏 Agradecimentos

* [Tailwind CSS](https://tailwindcss.com) – Framework CSS
* [Formspree](https://formspree.io) – Processamento de formulários
* [Heroicons](https://heroicons.com) – Ícones SVG gratuitos
* [Google Fonts – Inter](https://fonts.google.com/specimen/Inter)

