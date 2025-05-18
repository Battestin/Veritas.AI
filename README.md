# 🧭 Veritas.AI

Um verificador de fatos automatizado baseado em agentes de IA com Google Gemini.  
Você pergunta se algo é verdade — ele responde com evidências, parecer técnico e explicação popular.

---

## ⚙️ O que é?

**Veritas.AI** é um sistema multiagente que transforma desinformação em clareza.  
Basta digitar uma pergunta do tipo:

> ❓ "Vacinas causam autismo?"  
> ❓ "A Terra é plana?"  
> ❓ "5G causa câncer?"  

O sistema ativa 3 agentes autônomos:

1. 🕵️ **Agente Coletor de Evidências**  
   Busca fontes confiáveis: artigos científicos, veículos jornalísticos, checadores de fatos.

2. ⚖️ **Agente Avaliador de Veracidade**  
   Analisa as evidências e classifica: **VERDADEIRO**, **FALSO**, **IMPRECISO**, ou **NÃO CONCLUSIVO**.

3. 🧠 **Agente Explicador Popular**  
   Traduz o parecer técnico para linguagem clara e didática. Ideal para leigos, familiares ou grupos de WhatsApp.

---

## 📌 Por que usar?

- 🔍 Verificação baseada em múltiplas fontes confiáveis
- 🧠 Explicações acessíveis e livres de jargões
- 🤖 Automatizado e transparente com uso de Google Gemini
- 🧰 Pronto para ser estendido com mais agentes (ex: viés, contexto histórico, polarização)

---

## 🚀 Requisitos

- Google Colab ou ambiente Python
- Conta com acesso à [Google Gemini API](https://ai.google.dev/)
- Biblioteca `google-adk` instalada:

```bash
pip install -q google-adk
