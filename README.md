<div align="center">

<!-- ========================================================= -->
<!--  SUBSTITUA O CAMINHO ABAIXO PELO CAMINHO DA SUA LOGO      -->
<!--  Exemplo: ./logo_pamela.jpeg  ou  ./assets/logo.png       -->
<!-- ========================================================= -->

<img src="./logo pamela.jpeg" width="160" alt="Estúdio Reis Unhas" />

<br/><br/>

# 💅 Estúdio Reis Unhas
### Sistema de Agendamento Premium

<p>
  <img src="https://img.shields.io/badge/Versão-2.0-c9a84c?style=for-the-badge&labelColor=162018" />
  <img src="https://img.shields.io/badge/HTML-Arquivo%20Único-e34c26?style=for-the-badge&labelColor=162018" />
  <img src="https://img.shields.io/badge/Offline-100%25-5a9e7a?style=for-the-badge&labelColor=162018" />
  <img src="https://img.shields.io/badge/Responsivo-Mobile%20%26%20Desktop-74b9c0?style=for-the-badge&labelColor=162018" />
</p>

<br/>

<!-- ========================================================= -->
<!--  COLE O LINK DO SEU SISTEMA AQUI QUANDO TIVER PUBLICADO   -->
<!-- ========================================================= -->

<a href="SEU_LINK_AQUI" target="_blank">
  <img src="https://wandersondfarias.github.io/SISTEMA-DE-SAL-O-DE-UNHA-PAMELLA/" />
</a>

<br/><br/>

---

</div>

## 📋 Sobre o Projeto

O **Sistema de Agendamento do Estúdio Reis Unhas** é uma solução completa, elegante e **100% offline** desenvolvida exclusivamente para **Pamella Reis** — Uberaba, MG.

Tudo funciona em **um único arquivo HTML**, sem necessidade de servidor, banco de dados ou internet após o primeiro carregamento. Os dados são salvos diretamente no navegador do dispositivo.

> **Para usar:** Baixe o arquivo `index.html` → Abra no navegador → Pronto! ✅

---

## ✨ Funcionalidades

| Recurso | Descrição |
|---|---|
| 📅 **Calendário Interativo** | Navegue entre meses, visualize dias com agendamentos |
| ⏰ **Horários Disponíveis** | Seleção visual de horários, sem sobreposição |
| 📝 **Formulário de Agendamento** | Cadastro rápido com nome, telefone, serviço e horário |
| 💰 **Controle Financeiro** | Acompanhe ganhos diários, mensais e total geral |
| 📊 **Gráfico de Ganhos** | Visualização dos ganhos dia a dia no mês atual |
| 🍩 **Gráfico de Serviços** | Distribuição dos serviços mais realizados (gráfico rosca) |
| ⚙️ **Gerenciar Serviços** | Cadastre, edite preços e exclua serviços quando quiser |
| 🗑️ **Exclusão com Confirmação** | Modal de segurança antes de qualquer exclusão |
| 🌙 **Tema Claro / Escuro** | Alterne entre os temas com um clique |
| 📱 **100% Responsivo** | Funciona perfeitamente no celular e no computador |
| 💾 **Dados Salvos Localmente** | Nada se perde ao fechar o navegador |
| 🔒 **Privacidade Total** | Nenhum dado é enviado para a internet |

---

## 🎨 Design

O sistema foi desenvolvido com uma identidade visual sofisticada inspirada no logo do **Estúdio Reis Unhas**:

- **Tema escuro elegante** com tons verde-musgo profundo (`#0e1a14`)
- **Detalhes dourados** (`#c9a84c`) como cor principal de destaque
- **Tipografia refinada** — Cormorant Garamond (serifada clássica) nos títulos + Jost no corpo
- **Animações suaves** e feedback visual em todas as ações
- **Ícone de coroa animada** ✨ no cabeçalho com identidade da marca
- **Modo claro** disponível para uso durante o dia

---

## 📂 Estrutura do Projeto

```
📁 Estúdio Reis Unhas/
│
├── 📄 index.html          ← Sistema completo (único arquivo necessário)
├── 🖼️ logo_pamela.jpeg    ← Logo do estúdio
└── 📖 README.md           ← Este arquivo de documentação
```

---

## 🚀 Como Usar

### Passo 1 — Baixar
Faça o download do arquivo `index.html` para o seu computador ou celular.

### Passo 2 — Abrir
Abra o arquivo com qualquer navegador moderno:
- ✅ Google Chrome
- ✅ Microsoft Edge
- ✅ Mozilla Firefox
- ✅ Safari (iPhone/Mac)

### Passo 3 — Usar
O sistema já estará pronto para uso imediatamente, sem instalação!

---

## 📅 Como Fazer um Agendamento

```
1. Clique em um dia no calendário
2. Selecione o horário disponível
3. Preencha o nome da cliente
4. (Opcional) Informe o telefone
5. Selecione o serviço desejado
6. Clique em "Confirmar Agendamento"
```

---

## ⚙️ Como Personalizar

### Alterar Informações de Contato
Abra o arquivo `index.html` em um editor de texto e localize:
```html
<span class="contact-pill">👤 Pamella Reis</span>
<a href="tel:+5534997929612">(34) 99792-9612</a>
<a href="https://wa.me/5534997929612">WhatsApp</a>
```
Substitua pelo nome, telefone e WhatsApp desejados.

### Alterar os Serviços e Preços
No bloco de JavaScript, localize:
```javascript
let serviceTypes = [...] || ["Pé em Mão", "Pé", "Mão", ...]
let servicePrices = {...} || { "Pé em Mão": 60, "Pé": 32, ... }
```
Edite os serviços e valores conforme sua tabela de preços.

> 💡 **Dica:** Você também pode adicionar, editar e excluir serviços diretamente dentro do sistema, na seção **"Gerenciar Serviços"** — sem precisar editar o código!

### Alterar os Horários Disponíveis
```javascript
const timeSlots = ["08:00", "09:00", "10:00", ...]
```
Adicione ou remova os horários que desejar.

### Alterar as Cores
Localize `:root {` no CSS e modifique as variáveis:
```css
--gold: #c9a84c;        /* Cor dourada principal */
--deep: #0e1a14;        /* Fundo escuro */
--panel: #1c2a1f;       /* Fundo dos cards */
```

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura semântica e acessível |
| **CSS3** | Design elegante com variáveis de tema, animações e responsividade |
| **JavaScript Puro** | Toda a lógica, sem frameworks |
| **Chart.js** | Gráficos de ganhos e distribuição de serviços (via CDN) |
| **Google Fonts** | Tipografia Cormorant Garamond + Jost |
| **Font Awesome** | Ícones modernos |
| **localStorage** | Persistência de dados no próprio navegador |

> ⚠️ **Não requer servidor** — basta abrir o arquivo `.html` no navegador!

---

## 🔒 Privacidade e Segurança

- ✅ Todos os dados ficam **salvos apenas no seu dispositivo**
- ✅ **Nenhuma informação** é enviada para a internet
- ✅ Funciona **completamente offline** após o primeiro carregamento
- ✅ Não há contas, senhas ou cadastros necessários

---

## 📞 Contato do Estúdio

<div align="center">

| | |
|---|---|
| 👤 **Responsável** | Pamella Reis |
| 📍 **Localização** | Uberaba — MG, Brasil |
| 📱 **Telefone** | [(34) 99792-9612](tel:+5534997929612) |
| 💬 **WhatsApp** | [Clique para conversar](https://wa.me/5534997929612) |

</div>

---

## 👨‍💻 Desenvolvimento

<div align="center">

Desenvolvido com dedicação para o **Estúdio Reis Unhas** 💅

<br/>

<a href="https://github.com/wandersondfarias">
  <img src="https://img.shields.io/badge/GitHub-wandersondfarias-181717?style=for-the-badge&logo=github&labelColor=0e1a14" />
</a>
&nbsp;
<a href="https://www.linkedin.com/in/wandersonfariaswf/">
  <img src="https://img.shields.io/badge/LinkedIn-Wanderson%20de%20Farias-0077B5?style=for-the-badge&logo=linkedin&labelColor=0e1a14" />
</a>

<br/><br/>

<img src="https://img.shields.io/badge/Desenvolvido%20por-Wanderson%20de%20Farias-c9a84c?style=for-the-badge&labelColor=0e1a14" />

</div>

---

## 📜 Licença

Este projeto é de **uso livre** para fins pessoais e comerciais.

---

<div align="center">

✨ *Feito com carinho para profissionais da beleza* ✨

<!-- ========================================================= -->
<!--  SUBSTITUA O CAMINHO ABAIXO PELO CAMINHO DA SUA LOGO      -->
<!-- ========================================================= -->

<br/>
<img src="./logo_pamela.jpeg" width="80" alt="Estúdio Reis Unhas" />

</div>
