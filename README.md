# 🎯 English Practice - 30 Minutos Diários

App interativo para praticar inglês com IA. Foco em vocabulário IT, dificuldade progressiva e gamificação.

## ✨ Funcionalidades

- ⏱️ **Sessão de 30 minutos** cronometrada
- 📊 **Estatísticas em tempo real** (corretas, erradas, pontos, acurácia)
- 🎚️ **Dificuldade progressiva** (Fácil → Médio → Difícil)
- 🔊 **Áudio fonética** com pronuncia em inglês
- 📚 **4 tipos de exercício**:
  - Múltipla escolha (tradução)
  - Tradução de frases
  - Escrita (digitar tradução)
  - Preenchimento (complete a palavra)
- 🔥 **Streak counter** (dias consecutivos)
- 💾 **Persistência de dados** (localStorage)
- 📱 **Responsivo** (desktop, tablet, mobile)

## 🚀 Como Usar

### Localmente
1. Baixa o ficheiro `index.html`
2. Abre com qualquer navegador
3. Começa a praticar!

### GitHub Pages (Recomendado)

#### Passo 1: Criar repositório no GitHub
```bash
1. Vai a github.com
2. Clica em "New repository"
3. Nome: english-practice
4. Público (Public)
5. Clica "Create repository"
```

#### Passo 2: Upload dos ficheiros
```bash
# Opção A: Git (linha de comando)
git clone https://github.com/SEU_USERNAME/english-practice.git
cd english-practice
cp index.html .
git add index.html
git commit -m "Add English Practice app v3"
git push

# Opção B: GitHub Web (mais fácil)
1. Entra no repositório
2. Clica em "Add file" > "Upload files"
3. Arrasta o index.html
4. Clica "Commit changes"
```

#### Passo 3: Ativar GitHub Pages
1. Vai para Settings do repositório
2. Na esquerda, clica "Pages"
3. Source: "Deploy from a branch"
4. Branch: "main" / Folder: "/ (root)"
5. Clica "Save"

#### Pronto! ✅
A app estará disponível em:
```
https://SEU_USERNAME.github.io/english-practice/
```

## 📋 Correções Implementadas (v3)

### 🔴 Críticas
- ✅ Escapar quotes em `onclick` (evita quebras com apóstrofos)
- ✅ Streak = 1x/dia (verifica data anterior)
- ✅ Exercícios regeneram ao mudar dificuldade

### 🟠 Altas
- ✅ Sistema fuzzy melhorado (plurais, espaços, case-insensitive)
- ✅ Validação de input vazio
- ✅ Indicador dificuldade com animação

### 🟡 Médias
- ✅ Evitar duplicatas de exercícios
- ✅ Feedback visual do áudio (animação)
- ✅ Responsividade em mobile/tablet

### 🎨 Design Melhorado
- ✅ Gradiente atraente mas não distrativo
- ✅ Animações suaves
- ✅ Tema moderno (cards, shadows, transições)
- ✅ Acessibilidade melhorada
- ✅ Scrollbar customizado

## 📊 Estrutura de Dificuldade

| Nível | Vocab. | Frases | Trigger |
|-------|--------|--------|---------|
| Fácil | Básico | Saudações | Início |
| Médio | Técnico IT | Troubleshooting | 5 acertos |
| Difícil | Avançado | Infraestrutura | 8 acertos |

## 💾 Dados Persistentes

Os dados são guardados em `localStorage`:
- `streak` - Dias consecutivos
- `lastSessionDate` - Última data de prática

## 🛠️ Tecnologias

- HTML5
- CSS3 (Gradients, Flexbox, Grid, Animations)
- Vanilla JavaScript
- Web Speech API (para áudio)

## 📱 Compatibilidade

✅ Chrome/Edge/Firefox (desktop)
✅ Safari (desktop e iOS)
✅ Mobile browsers (Android, iOS)

## 🐛 Se encontrares erros

1. Abre a consola (F12)
2. Verifica se há mensagens de erro
3. Testa o áudio (pode não funcionar sem permissão)

## 📝 Futuras Melhorias

- [ ] Exportar progresso (PDF/CSV)
- [ ] Multiplicador de pontos por streak
- [ ] Dark mode
- [ ] Histórico de sessões
- [ ] Leaderboard online
- [ ] Custom word lists

## 👨‍💻 Autor

Diego Michael Busse - ITC Mozambique, TSI-3

## 📄 Licença

MIT - Usa livremente!

---

**Mantém a prática diária! 🚀**
