# manaus-ai-builder
Repositório contendo MVPs e scripts de IA/Python para ideias/sonhos (produtividade e experimentos)
 markdown
 # 🚀 Meu Portfólio de Ideias e Protótipos (MVPs)

Bem-vindo ao meu repositório! Aqui estão reunidos os meus primeiros sistemas e experimentos práticos. Desenvolvi esses projetos de forma totalmente autodidata, utilizando o **Modo IA do Google** para estruturar a lógica e programando scripts em **Python**. Meu objetivo é resolver problemas reais de mercado, logística e comércio — com um olhar especial para a realidade da minha cidade, Manaus (AM).

---

## 🛠️ Ferramentas que Utilizei

* **Para criar as Telas (Front-end):** Atoms.dev (com a ajuda de assistentes de IA)
* **Para a Lógica do Sistema (Back-end):** Linguagem Python (executada pelo Google Colab)
* **Inteligência Artificial:** Inteligência do Google (Gemini API)

---

## 🎵 1. ScoreBuddy AI (Projeto Principal)

* **O Problema:** Estudantes iniciantes de música erram notas, ritmo e afinação quando treinam sozinhos em casa, pois não têm ninguém para corrigi-los na hora.
* **A Solução:** Um assistente virtual que ouve o aluno tocar e diz o que ele precisa melhorar.
* **Como Funciona:** O sistema em Python ouve o áudio gravado pelo aluno e descobre quais notas foram tocadas. Depois, envia essas informações para a IA do Gemini, que compara o áudio com a partitura correta e gera um relatório mostrando os erros de notas e de ritmo.
* **Tecnologias:** Python, Biblioteca Librosa (para análise de áudio), Gemini API e Atoms.dev.
* **Links do Projeto:**
  * 💻 [Ver Código no Google Colab](https://colab.research.google.com/drive/1LPxuZWxsa4FR7s4kie0OXe-pY0wZgXUr?usp=sharing)
  * 🎨 [Ver Telas no Atoms.dev](https://atoms.dev/pt-BR/app/85adf3b29f554c849ed035945187ce2f)

---

## 📈 2. ManausEstoque AI (Varejo de Bairro & Impacto Social)

* **O Problema:** Pequenos comércios de bairro em Manaus perdem dinheiro e desperdiçam alimentos porque os produtos vencem esquecidos nas prateleiras.
* **A Solução:** Um sistema que avisa quando os produtos estão perto de vencer e cria promoções automáticas.
* **Como Funciona:** O código em Python analisa as datas de validade dos produtos. Quando encontra itens que vão vencer logo, ele pede para a IA (Gemini) criar mensagens de propaganda personalizadas para que o comerciante envie direto para os clientes no WhatsApp.
* **O que aprendi na prática:** Aprendi a trabalhar com organização de datas e horários em Python (`datetime`), garantindo que o sistema não trave na hora de calcular os dias restantes para o vencimento.
* **Links do Projeto:**
  * 💻 [Ver Código no Google Colab](https://colab.research.google.com/drive/1ACdWjqHVNRRs6ib2ydFxXwzcEF7pLi9c?usp=sharing)
  * 🎨 [Ver Telas no Atoms.dev](https://atoms.devpt-BR/app/cbb7a8e965c54888be5660b9b7c25250)

---

## 📍 3. ManausRotas (Logística Urbana e Economia Local)

* **O Problema:** Entregadores e motoboys em Manaus gastam muito tempo e combustível porque os clientes digitam os endereços errados ou incompletos na hora da compra.
* **A Solução:** Um organizador de rotas que corrige os endereços e calcula o caminho mais curto entre os bairros.
* **Como Funciona:** A inteligência artificial lê o endereço digitado pelo cliente e corrige os erros de digitação. Depois, o sistema envia o endereço corrigido para um mapa digital (Geopy), que organiza as entregas colocando as casas mais próximas primeiro.
* **O que aprendi na prática:** Criei uma estratégia de segurança (*Fallback*): se o endereço vier muito errado, a IA tenta consertar o texto antes de enviar para o mapa, evitando que o aplicativo trave ou dê erro para o entregador.
* **Links do Projeto:**
  * 💻 [Ver Código no Google Colab](https://colab.research.google.com/drive/1c0TR2mE25fecjfskIjkOEbjTNYcqKAnQ?usp=sharing)
  * 🎨 [Ver Telas no Atoms.dev](https://jsnaxs.pub.atoms.world/)

---

## 📥 4. InboxFlow (Organizador de E-mails)

* **O Problema:** Profissionais e freelancers perdem muito tempo limpando caixas de entrada lotadas e acabam deixando mensagens importantes passarem batidas.
* **A Solução:** Um painel inteligente que resume e organiza seus e-mails automaticamente.
* **Como Funciona:** O sistema se conecta com a caixa de e-mails e exibe um resumo da mensagem em apenas 3 tópicos, avisa se o e-mail é urgente e já deixa respostas automáticas prontas para enviar.

### 💰 Planos do Sistema

| Plano | Preço | O que inclui |
| :--- | :--- | :--- |
| **Teste Gratuito** | R\$ 0 (14 dias) | Teste básico com limite de até 500 e-mails organizados. |
| **Plano Completo** | R\$ 79,90/mês | Organização por etiquetas, resumos avançados e avisos urgentes no WhatsApp. |

* **Links do Projeto:**
  * 💻 [Ver Código no Google Colab](https://colab.research.google.com/drive/1FLthlURw-YKy2XAQuaH6Ba3zcia3VGlM?usp=sharing)
  * 🎨 [Ver Telas no Atoms.dev](https://atoms.devpt-BR/share/9c1bd17eb3144660b659b9380fd03c4b/v1)

---

## 👥 5. TalentMatch AI (Análise de Currículos para RH)

* **O Problema:** Pequenas empresas e startups gastam horas e horas lendo dezenas de currículos para encontrar candidatos técnicos.
* **A Solução:** Uma ferramenta que lê os currículos e diz quais candidatos combinam mais com a vaga.
* **Como Funciona:** O sistema em Python abre arquivos em PDF de currículos. A IA lê as informações e compara com o que a vaga de emprego pede, dando uma nota de compatibilidade e resumindo os pontos fortes do candidato.
* **O que aprendi na prática:** Como cada pessoa faz o currículo de um jeito, tive que aprender a criar instruções (prompts) muito firmes e claras para a IA, garantindo que ela devolva a resposta sempre organizada do mesmo jeito, sem quebrar as telas do aplicativo.
* **Links do Projeto:**
  * 💻 [Ver Código no Google Colab](https://colab.research.google.com/drive/16JaSs-Zq0QMK18ZZpljXb_4omTJXlZd4?usp=sharing)
  * 🎨 [Ver Telas no Atoms.dev] *(Em desenvolvimento)*

---

## 🗒️ Conclusão e Próximos Passos

Este repositório reúne as minhas primeiras grandes ideias. Como sou um construtor iniciante e autodidata, usei o **Modo IA do Google** como meu tutor e parceiro para estruturar a lógica desses projetos e meus testes no mundo da tecnologia, focando sempre em problemas que vejo acontecer de verdade no comércio de Manaus por exemplo.

Aprender a juntar pequenos códigos em Python (mesmo com scripts simples) com a inteligência da IA abriu minha mente. Meu próximo passo é continuar estudando e praticando programação para transformar esses protótipos em sistemas cada vez mais completos e robustos.
