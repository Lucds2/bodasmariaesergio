# 👑 Convite Digital | Bodas de Ouro (Maria & Sérgio)

Um convite web interativo, elegante e totalmente responsivo desenvolvido para celebrar as Bodas de Ouro (50 anos de casados) de Maria e Sérgio. A plataforma foi projetada para partilhar os detalhes do evento com os convidados e simplificar ações cruciais, como a confirmação de presença e a gestão de presentes de forma totalmente digital.

---

## 🚀 Funcionalidades Implementadas

* **Design Temático e Elegante:** Utilização de fontes clássicas e sofisticadas importadas do Google Fonts (`Roboto Condensed`, `Rouge Script`, `Belius`), além de animações de pétalas e elementos visuais que remetem à celebração de 50 anos de união.
* **Sistema Pix "Copia e Cola" Integrado:** Exibição dinâmica de um QR Code para presentes e um botão interativo para copiar automaticamente a chave Pix para a área de transferência do utilizador, oferecendo excelente usabilidade.
* **Confirmação de Presença Digital (RSVP):** Botões direcionais integrados que facilitam a resposta dos convidados através do Google Forms.
* **Validação de Transações por WhatsApp:** Link direto configurado para a API do WhatsApp com mensagem pré-definida para o envio imediato do comprovativo de pagamento.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído focando-se em desempenho e compatibilidade móvel (Mobile-First):

* **HTML5:** Estruturação semântica de toda a página de convite, contendo blocos organizados para a mensagem central, informações sobre o jantar por adesão e secções dedicadas aos botões de ação.
* **CSS3:** Estilização geral (`style.css`), layouts flexíveis e transições fluidas adaptadas para ecrãs de smartphones e computadores.
* **JavaScript (Vanilla):** Implementação de lógica nativa no final do documento para a funcionalidade `copiarTexto()`, criando um elemento dinâmico de área de transferência temporária para garantir compatibilidade com múltiplos navegadores e disparo de alertas visuais (`alert`).

---

## 📂 Estrutura do Repositório

* `/images`: Diretório contendo os recursos visuais, como o logótipo das Bodas, o vetor de pétalas e a imagem gerada do QR Code.
* `index.html`: Toda a marcação estrutural do convite e o motor Javascript para a cópia de texto.
* `style.css`: Estilização e identidade visual da plataforma.

---

## 🔧 Como Executar Localmente

Se pretender clonar e testar esta aplicação na sua máquina:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/Lucds2/bodasmariaesergio.git](https://github.com/Lucds2/bodasmariaesergio.git)
Aceda à pasta do projeto:

Bash
cd bodasmariaesergio
Inicie o projeto:

Abra o diretório no VS Code e clique em Go Live utilizando a extensão Live Server para inspecionar a página e os comportamentos dos botões no seu navegador.

📬 Autor
Desenvolvido por Luciano dos Santos.

Estudante de Análise e Desenvolvimento de Sistemas & Programador Fullstack.