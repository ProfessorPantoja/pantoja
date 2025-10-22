# 🧠 Template: Site para Psicólogos

## 🎯 Sobre este template

Site profissional completo para psicólogos, otimizado para conversão de pacientes.

**Design:**
- Cores calmas e profissionais (azul/verde suaves)
- Layout limpo e acolhedor
- 100% responsivo
- SEO otimizado

**Seções:**
- Hero com foto e credenciais
- Sobre mim
- Especialidades/Abordagem
- Modalidades de atendimento (online/presencial)
- Depoimentos
- FAQ
- Contato/CTA

---

## 📝 COMO USAR (Passo a Passo)

### 1. COLETAR DADOS DO CLIENTE

Envie o **Formulário de Briefing** (ver `BRIEFING-PSICOLOGO.md`)

### 2. EDITAR O TEMPLATE

Abra `index.html` e procure por `[TEXTOS EM COLCHETES]` - são os pontos para substituir:

**Meta Tags (linhas 7-13):**
- `[NOME COMPLETO]`
- `[CIDADE]`
- `[ESPECIALIDADE]`
- `[NÚMERO]` (CRP)
- `[ONLINE/PRESENCIAL]`

**Hero (linhas 303-311):**
- `[URL_FOTO_IMGUR]` - foto profissional
- `[NOME COMPLETO]`
- `[ESPECIALIDADE]`
- `[ABORDAGEM]` - ex: "Terapia Cognitivo-Comportamental"
- `[NÚMERO]` (CRP)
- `[CIDADE]`
- `[ESTADO]`

**Sobre (linhas 318-328):**
- `[PARÁGRAFO 1]` - apresentação e formação
- `[PARÁGRAFO 2]` - jornada e experiência
- `[PARÁGRAFO 3]` - como trabalha
- `[FRASE DE IMPACTO]` - filosofia de atendimento

**Especialidades (linhas 337-353):**
- `[ESPECIALIDADE 1/2/3]` - áreas de atuação
- Descrição de cada uma

**Atendimento (linhas 361-376):**
- Manter ou remover cards (online/presencial)
- `[ENDEREÇO/BAIRRO]`
- `[CIDADE]`

**Depoimentos (linhas 386-390):**
- `[DEPOIMENTO]`
- `[INICIAIS]`
- `[IDADE]`

**FAQ (linhas 398-417):**
- Personalizar respostas conforme perfil do psicólogo

**Contato (linhas 428-441):**
- `[DDD][TELEFONE]` - número WhatsApp
- `[WHATSAPP]` - número formatado visualmente
- `[EMAIL]`
- `[CIDADE]` - `[ESTADO]`

**Footer (linha 452):**
- `[NOME COMPLETO]`
- `[NÚMERO]` (CRP)

---

## 🎨 PERSONALIZAR CORES (Opcional)

No arquivo, linhas 20-27, altere as variáveis:

```css
--primary: #4A7C8C;        /* Cor principal */
--primary-dark: #3A6575;   /* Variação escura */
--secondary: #7FA99B;      /* Cor secundária */
--accent: #D4A574;         /* Cor de destaque */
```

**Sugestões de paletas:**

**Azul Sereno (padrão):**
- Primary: #4A7C8C
- Secondary: #7FA99B

**Verde Calmo:**
- Primary: #6B9080
- Secondary: #A4C3B2

**Roxo Suave:**
- Primary: #8B7E9B
- Secondary: #B9A9C6

**Rosa Acolhedor:**
- Primary: #C48B9F
- Secondary: #D4A5A5

---

## 📸 FOTO DO PSICÓLOGO

**Requisitos:**
- Foto profissional
- Fundo neutro ou desfocado
- Boa iluminação
- Formato: JPG ou PNG
- Tamanho: mínimo 500x500px

**Como adicionar:**

1. Cliente envia foto
2. Faz upload no Imgur: https://imgur.com/upload
3. Copia link direto (termina em .jpg ou .png)
4. Cola na linha 304: `background-image: url('LINK_AQUI');`

---

## 🚀 DEPLOY

### Opção 1: Netlify (Grátis - RECOMENDADO)

1. Cria repo no GitHub com o site
2. Conecta no Netlify
3. Deploy automático
4. Domínio grátis: `nome.netlify.app`

### Opção 2: GitHub Pages

1. Cria repo público
2. Settings → Pages → Source: main branch
3. Domínio: `usuario.github.io/repo`

### Opção 3: Vercel

Similar ao Netlify, também grátis

---

## ✅ CHECKLIST ANTES DE ENTREGAR

- [ ] Todos os `[COLCHETES]` foram substituídos
- [ ] Foto aparece corretamente
- [ ] Links do WhatsApp funcionam
- [ ] Email funciona
- [ ] Testado no celular (responsivo)
- [ ] SEO: title e description preenchidos
- [ ] Cores personalizadas (se solicitado)
- [ ] Cliente aprovou o conteúdo

---

## 💰 UPSELL: Melhorias Extras

**Blog (+R$ 500):**
- Adicionar seção de artigos
- Ajuda no SEO

**Agendamento Online (+R$ 800):**
- Integrar Calendly ou similar

**Formulário de Contato (+R$ 300):**
- FormSubmit ou Formspree

**Google Analytics (+R$ 200):**
- Rastreamento de visitantes

---

## 🎯 TEMPO ESTIMADO

- Edição do template: 1-2 horas
- Upload de foto: 15 min
- Deploy: 30 min
- Revisões: 1-2 horas

**Total: 3-5 horas**

---

## 📞 DÚVIDAS?

Consulte a documentação completa em `/docs/ESTRATEGIA-SITES-2000.md`
