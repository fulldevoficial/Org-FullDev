# Documento de Estrutura do MVP – Indicador de Cursos (FullDev)

## 1. Visão Geral
O **Indicador de Cursos** será uma das primeiras funcionalidades da FullDev Online, permitindo que usuários compartilhem avaliações reais sobre cursos, faculdades e plataformas educacionais.  

**Objetivos:**
- Criar uma base confiável de opiniões para orientar desenvolvedores antes de investir em cursos ou matrículas.  
- Permitir que instituições tenham perfis oficiais para responder feedbacks, criando uma dinâmica semelhante ao ReclameAqui, mas focada em educação e tecnologia.  

---

## 2. Regras de Acesso
- **Usuário não logado:** pode navegar, pesquisar e ler publicações, mas não interagir.  
- **Usuário logado:** pode criar publicações, comentar, promover posts e acompanhar o status de suas contribuições.  
- **Perfil de Marca (CNPJ válido):** pode personalizar perfil institucional, responder publicações e receber selo de verificação.  

---

## 3. Cadastro e Autenticação

### Usuário Comum
- Login via e-mail/senha.  
- Vinculação obrigatória ao LinkedIn para autenticar identidade.  
- Cadastro com **CPF único e obrigatório**.  

### Pagina de Marca
- Cadastro iniciado por representante.  
- **Dados exigidos:** CNPJ, nome da instituição, site oficial, e-mail de contato.  
- Validação interna da FullDev para evitar duplicidade.  
- Perfil institucional recebe selo de verificação e pode responder avaliações.  

---

## 4. Fluxo da Publicação
1. Usuário logado acessa o formulário e preenche:  
   - Título, nome e imagem do curso  
   - Senioridade (iniciante, intermediário, avançado)  
   - Dificuldade percebida (rating 1–5)  
   - Didática do instrutor (texto)  
   - Usabilidade da plataforma (texto)  
   - Valor e formas de pagamento  
   - Tempo de utilização  
   - Nota geral (rating 1–5)  
   - Stack (select box: Frontend, Backend, Dados, etc.)  
   - Justificativa da avaliação (texto)  

2. **Moderação prévia:**  
   - Filtro automático de palavrões/termos proibidos → exige correção manual.  
   - Moderador revisa → aprova (entra no feed) ou reprova (notificação ao autor).  

---

## 5. Interações na Plataforma
- **Comentários:** sem moderação prévia, mas removíveis por moderador.  
- **Likes/Dislikes:** em posts e comentários.  
- **Promover publicação:** sistema de hype (ícone de foguinho).  
- **Ranking dinâmico:** posts mais hypados aparecem no topo.  
- **Resposta da marca:** perfis institucionais podem responder oficialmente avaliações.  

---

## 6. Telas Principais

### Tela Inicial
- Cursos patrocinados em destaque.  
- Barra de pesquisa + filtros por stack.  
- Lista de recomendações em alta.  
- Publicações com selo se houver resposta oficial da marca.  

### Tela de Detalhamento
- **Topo:** imagem, título, nota geral, autor (com LinkedIn).  
- **Corpo:** justificativa e indicadores (didática, usabilidade, preço, etc.).  
- **Resposta da marca:** campo editável para instituições (com selo).  
- **Comentários:** com likes/dislikes e hover mostrando dados do autor.  

---

## 7. Tela de Configuração do Usuário

### 7.1 Perfil
- Foto, nome público, @username, bio, localidade.  
- Stack principal e senioridade.  
- LinkedIn obrigatório para postar no Indicador.  
- Portfólio opcional.  

### 7.2 Conta & Segurança
- E-mail, senha (alteração com validação), logout de todos os dispositivos.  

### 7.3 Identidade Validada
- CPF obrigatório, imutável após cadastro.  
- Consentimento para termos de uso.  

### 7.4 Preferências
- Tema (claro/escuro).  
- Stacks de interesse.  

### 7.5 Privacidade
- Exibir LinkedIn publicamente (toggle).  
- Mostrar estatísticas públicas (toggle).  

### 7.6 Marcas Vinculadas
- Lista de vínculos (Administrador/Atendente).  
- Solicitação de vínculo a marca com status (pendente/aprovado/recusado).  

---

## 8. Área do Representante de Marca
- Visualiza todas as avaliações da marca.  
- Pode responder oficialmente (sem moderação prévia, mas sujeito a remoção).  
- Histórico de respostas/edições.  
- Métricas básicas sobre menções e interações.  

---

## 9. Centro de Notificações

### Usuário Comum
- Comentários, likes/dislikes, status da publicação (aprovada, reprovada, em revisão).  

### Usuário com Marca Vinculada
- Notificações sobre novas menções, comentários e interações em publicações da marca.  

### Moderador
- Publicações pendentes, denúncias, vínculos de marca.  

---

## 10. Painel do Moderador
- **Visão geral:** métricas de revisão, denúncias e vínculos.  
- **Fila de publicações:** listar e aprovar/reprovar em lote.  
- **Denúncias:** remover conteúdo ou notificar autor.  
- **Solicitações de vínculo/marca:** aprovar ou recusar com comentários.  
- **Regras:** logs de todas as ações para rastreabilidade.  

---
