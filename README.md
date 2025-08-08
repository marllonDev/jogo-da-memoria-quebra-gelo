# 🧠 Jogo de Memória - Quebra-Gelo para Equipes

Um jogo de memória interativo desenvolvido especificamente para ser usado como quebra-gelo em reuniões e dinâmicas de equipe. Combina diversão com perguntas estratégicas para promover conexões mais profundas entre colegas de trabalho.

## ✨ Funcionalidades

### 🎮 Jogo de Memória
- **12 cartas interativas** com emojis relacionados ao ambiente de trabalho
- **Sistema de pontuação** com contador de jogadas e cronômetro
- **Animações suaves** e feedback visual para uma experiência envolvente
- **Design responsivo** que funciona em desktop, tablet e mobile
- **Detecção automática de vitória** com celebração

### 💬 Sistema de Perguntas Quebra-Gelo
- **10 perguntas cuidadosamente selecionadas** para promover conversas significativas
- **Navegação flexível** (próxima, anterior, aleatória)
- **Temas variados**: crescimento profissional, interesses pessoais, dinâmica de equipe
- **Interface intuitiva** para facilitar a moderação

### 🎨 Design e UX
- **Interface moderna** com gradientes coloridos e profissionais
- **Tema otimizado para ambiente corporativo**
- **Animações e transições suaves**
- **Acessibilidade** e usabilidade pensadas para todos os níveis técnicos

## 🚀 Como Usar

### Opção 1: Execução Direta
1. Faça o download do arquivo `index.html`
2. Abra o arquivo em qualquer navegador web moderno
3. O jogo estará pronto para usar!

### Opção 2: Servidor Local (Recomendado para apresentações)
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/jogo-memoria-quebra-gelo.git

# Entre no diretório
cd jogo-memoria-quebra-gelo

# Inicie um servidor local simples
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (se tiver o http-server instalado)
npx http-server

# Acesse http://localhost:8000 no navegador

Opção 3: GitHub Pages

Faça fork deste repositório
Vá em Settings > Pages
Selecione a branch main como source
Seu jogo estará disponível em 
https://seu-usuario.github.io/jogo-memoria-quebra-gelo
🎯 Como Usar em Reuniões

Para Moderadores

Abra o jogo
 em uma tela compartilhada ou projete para todos verem
Explique as regras
: encontrar pares de emojis clicando nas cartas
Jogue colaborativamente
 com a equipe sugerindo cartas para virar
Use as perguntas
 durante ou após o jogo para iniciar conversas
Dinâmicas Sugeridas

Modo Colaborativo
: Toda a equipe joga junta, discutindo estratégias
Modo Competitivo
: Divida em times pequenos e compare pontuações
Foco nas Perguntas
: Use o jogo como aquecimento e foque nas discussões
Quebra-gelo Rápido
: 5-10 minutos no início de reuniões
🛠️ Tecnologias Utilizadas

HTML5
: Estrutura semântica e acessível
CSS3
: Animações, gradientes e design responsivo
JavaScript Vanilla
: Lógica do jogo sem dependências externas
Design Responsivo
: Funciona em todos os dispositivos
📱 Compatibilidade

✅ Chrome 60+
✅ Firefox 55+
✅ Safari 12+
✅ Edge 79+
✅ Dispositivos móveis (iOS/Android)
🎨 Personalização

O jogo foi desenvolvido para ser facilmente personalizável:

Modificar Emojis

// Linha 89 no arquivo index.html
const emojis = ['😊', '🚀', '💡', '🎯', '⭐', '🔥'];
// Substitua pelos emojis desejados (mantenha 6 únicos)

Adicionar/Modificar Perguntas

// Linha 92 no arquivo index.html
const questions = [
    "Sua pergunta personalizada aqui...",
    // Adicione quantas perguntas quiser
];

Personalizar Cores

Modifique as variáveis CSS nos gradientes para alterar o esquema de cores:

/* Exemplos de gradientes no arquivo */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

Faça fork do projeto
Crie uma branch para sua feature (
git checkout -b feature/AmazingFeature
)
Commit suas mudanças (
git commit -m 'Add some AmazingFeature'
)
Push para a branch (
git push origin feature/AmazingFeature
)
Abra um Pull Request
Ideias para Contribuições

[ ] Novos temas de emojis (natureza, comida, esportes)
[ ] Sistema de dificuldade (mais cartas, menos tempo)
[ ] Banco de perguntas categorizadas
[ ] Modo multiplayer online
[ ] Estatísticas avançadas
[ ] Temas visuais alternativos
📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo 
LICENSE
 para mais detalhes.

🎉 Casos de Uso

Empresas e Startups

Onboarding de novos funcionários
Team buildings e retreats
Reuniões de kick-off de projetos
Quebra-gelo em workshops
Educação e Treinamento

Início de cursos e workshops
Dinâmicas em sala de aula
Eventos de networking
Conferências e seminários
Comunidades e Grupos

Meetups e eventos
Grupos de estudo
Comunidades online
Eventos de networking
📞 Suporte

Encontrou um bug ou tem uma sugestão?

Abra uma 
https://github.com/seu-usuario/jogo-memoria-quebra-gelo/issues
Entre em contato: [seu-email@exemplo.com]
Desenvolvido com ❤️ para conectar pessoas e equipes

⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!