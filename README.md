# 📋 Sobre o Projeto

Este projeto consiste na conversão fiel de um design do Figma para código HTML e CSS, desenvolvido como atividade prática da disciplina de **Programação Front-End**. O objetivo principal foi demonstrar habilidades em:

* Interpretação precisa de protótipos visuais
* Desenvolvimento responsivo com abordagem **Mobile First**
* Implementação de **HTML semântico**
* Organização e otimização de código CSS
* Uso de **variáveis CSS** para manutenibilidade

---

## 🎯 Objetivos Alcançados

* ✅ Fidelidade ao design original
* ✅ Responsividade completa (Mobile **320px → Desktop 1980px**)
* ✅ Metodologia **Mobile First**
* ✅ Performance otimizada (**95/100** no Google Lighthouse)
* ✅ Código semântico e acessível
* ✅ Estrutura organizada e reutilizável

---

## 🚀 Demo

* 🌐 Site Online: [https://cocaagency.vercel.app/](https://cocaagency.vercel.app/)

---

## 📊 Métricas de Performance

O projeto alcançou excelentes resultados de performance e qualidade:

|           Métrica |   Score   |    Status    |
| ----------------: | :-------: | :----------: |
|       Performance |  95 / 100 | 🟢 Excelente |
|    Acessibilidade |  96 / 100 | 🟢 Excelente |
| Melhores Práticas |  82 / 100 |    🟡 Bom    |
|               SEO | 100 / 100 |  🟢 Perfeito |


<img width="613" height="96" alt="performance" src="https://github.com/user-attachments/assets/cbe6a9e0-074f-47f6-b757-b4627eac8950" />

### Gráficos de Performance


<img width="1522" height="711" alt="performancetest" src="https://github.com/user-attachments/assets/be16a00e-936e-43ae-a688-d04579ee1061" />

**Core Web Vitals (exemplos):**

* **First Contentful Paint (FCP):** 1.9s
* **Largest Contentful Paint (LCP):** 1.9s
* **Cumulative Layout Shift (CLS):** 0.107
* **Speed Index:** 2.4s

### GIF de acesso em tempo real do Site


![performancegif](https://github.com/user-attachments/assets/60bf4d2d-1374-4144-a84b-62cd411c52f7)


---

## 🛠️ Tecnologias Utilizadas

* **HTML5** - Estruturação semântica do conteúdo
* **CSS3** - Estilização e layout responsivo
* **CSS Variables** - Gerenciamento de tokens de design
* **Flexbox / Grid** - Sistema de layout moderno
* **Media Queries** - Implementação da responsividade
* **Stylelint** - configuração em `config/.stylelintrc.json`
* **Prettier** - se configurado
* **Vercel** - Plataforma de deploy e hospedagem

---

## 📁 Estrutura do Projeto

```
coca-design-to-code/
├── .vscode/
│ └── settings.json
├── config/
│ ├── node_modules/
│ ├── .stylelintrc.json
│ ├── package-lock.json
│ └── package.json
├── CSS/
│ └── styles.css
├── resources/
│ ├── icons/
│ └── images/
│ ├── desktop-version/
│ ├── mobile-version/
│ └── tablet-version/
├── index.html
└── README.md
```

> Nota: os arquivos de configuração (package.json, .stylelintrc.json, node_modules) estão dentro da pasta `config/`. Se você preferir, pode movê-los para a raiz para facilitar execução de scripts sem apontar a pasta — mas não deixei instruções para a execução dos mesmos por ser algo mais relacionado ao desenvolvimento do projeto e não a execução do proprio.

---

## 🚀 Como Executar Localmente

### Pré-requisitos

* Navegador web moderno
* Editor de código (recomendado: **VS Code**)

### Passo a passo

1. Clone o repositório:

```bash
git clone [https://github.com/PabloTzeliks/coca-design-to-code.git](https://github.com/PabloTzeliks/coca-design-to-code.git)
```

2. Entre no diretório do projeto:

```bash
cd coca-design-to-code
```

3. Abra o projeto no VS Code (opcional):

```bash
code .
```

4. Abra `index.html` no navegador (duplo clique) ou utilize Live Server conforme abaixo.

---

### 🔧 Desenvolvimento com Live Server (recomendado)

* Instale a extensão **Live Server** no VS Code
* Clique com o botão direito em `index.html` → **Open with Live Server**
* O site abrirá automaticamente em: `http://localhost:5500`

---

## 📱 Breakpoints Responsivos

| Dispositivo    | Largura | Características                 |
| -------------- | ------- | ------------------------------- |
| Mobile Pequeno | 320px   | Layout em coluna única          |
| Mobile Médio   | 375px   | Ajustes finos para mobile comum |
| Tablet         | 768px   | Layout intermediário / grid     |
| Laptop         | 1024px  | Layout de desktop reduzido      |
| Desktop        | 1440px  | Layout completo do design       |
| Desktop Full   | 1980px  | Layout em telas muito grandes   |

---

## ✨ Features Implementadas

* **Design Pixel Perfect** — Alta fidelidade ao protótipo
* **Responsividade Completa** — Adaptação fluida entre todos os breakpoints
* **Acessibilidade** — Uso de tags semânticas e atributos ARIA quando aplicáveis
* **Performance Otimizada** — Técnicas para carregamento rápido e baixo custo de render
* **Código Limpo** — Organização, modularidade e reutilização de estilos
* **CSS Moderno** — Variáveis CSS e boas práticas de layout (Flexbox / Grid)

**Destaques:**

* Performance: **95/100** no Lighthouse
* Acessibilidade: **96/100** no Lighthouse
* SEO: **100/100** nas verificações básicas de SEO
* Deploy automático via **Vercel**

---

## 🤝 Contribuição

Este projeto foi desenvolvido como atividade acadêmica. Sugestões, correções e feedbacks são bem-vindos.

---

## 📄 Licença

Projeto de uso acadêmico — disponível para fins educacionais.

---

## 👨‍💻 Autor

**Pablo Ruan Tzeliks**

* Turma: WEG MI 78
* GitHub: [@PabloTzeliks](https://github.com/PabloTzeliks)
* Projeto: **coca-design-to-code**

---
