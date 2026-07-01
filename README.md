# DataFilmes 2.0

Plataforma social de catalogação de filmes e séries no estilo Letterboxd. As pessoas registram o que assistiram, atribuem nota, escrevem resenhas e acompanham o que os amigos estão vendo.

## Sobre o produto

**Modelo de negócio (MVP)** freemium: gratuito para o usuário final, com monetização futura via assinatura premium (estatísticas avançadas, sem anúncios) e parcerias com serviços de streaming.

**Proposta do MVP:** permitir que uma pessoa catalogue, avalie e compartilhe com amigos os filmes e séries que assistiu, validando se há demanda por uma rede social de catalogação.

### É / Não é

| É | Não É |
|---|---|
| uma rede social de catalogação de filmes e séries | um serviço de streaming |
| gratuito no MVP, com modelo freemium | um catálogo de onde assistir (no MVP) |
| focado em registro, avaliação e amigos | uma plataforma de pirataria |

### Faz / Não faz

| Faz | Não Faz |
|---|---|
| cataloga filmes e séries assistidos | reproduz ou transmite conteúdo |
| permite avaliar com nota e escrever resenhas | vende ingressos ou assinaturas (no MVP) |
| permite seguir amigos e ver o feed de atividade | recomenda por inteligência artificial (no MVP) |
| busca títulos em uma base de metadados | funciona offline (no MVP) |

### Escopo do MVP (Onda 1)

Cadastro e login, busca e detalhe de títulos (via TMDB), marcar como assistido, atribuir nota, escrever resenha, perfil e diário pessoal, seguir amigos e feed de atividades.

Incrementos futuros: watchlist e listas personalizadas (Onda 2); curtir/comentar resenhas, estatísticas anuais e notificações (Onda 3).

### Time Scrum

Equipe enxuta de seis pessoas: Product Owner, Scrum Master, Designer UX/UI, dois Desenvolvedores full stack (front end React / back end Node) e QA (meio período).

### Métricas de validação

Usuários cadastrados na primeira semana; percentual de ativação (registraram ao menos um filme); média de filmes registrados por usuário ativo; percentual de usuários que seguem ao menos um amigo; retenção em sete dias.

## Índice da entrega

| Entregável | Ferramenta | Arquivo no repositório |
|---|---|---|
| Lean Inception + MVP Canvas | Miro | [canvas-url.txt](canvas-url.txt) (link do board) e [leaninception.pdf](leaninception.pdf) (export) |
| Backlog do Produto + DoR e DoD | Jira → PDF | [product-backlog.pdf](product-backlog.pdf) |
| Backlog da Sprint 1 | Jira → PDF | [sprint-backlog.pdf](sprint-backlog.pdf) |
| Wireframes de baixa fidelidade (mobile e desktop) | Figma → PNG | [wireframes/](wireframes/) |
| Vídeo de apresentação (2 a 4 min) | Gravação | [showcase.mp4](showcase.mp4) e [video-url.txt](video-url.txt) |

O vídeo de apresentação está disponível em dois formatos: pelo link do YouTube contido em [video-url.txt](video-url.txt) e como arquivo local na raiz do repositório em [showcase.mp4](showcase.mp4).

## Estrutura do repositório

```
datafilmesv2/
  README.md                  (descrição do projeto e índice da entrega)
  canvas-url.txt              (URL pública do board do Miro)
  leaninception.pdf           (export do board: Lean Inception + MVP Canvas)
  product-backlog.pdf         (gerado a partir do Jira)
  sprint-backlog.pdf          (gerado a partir do Jira)
  showcase.mp4                (vídeo de apresentação)
  video-url.txt                (link do vídeo no YouTube)
  wireframes/
    01-cadastro-login.png                (mobile)
    02-busca.png                         (mobile)
    03-detalhe-avaliar.png                (mobile)
    04-diario.png                        (mobile)
    04b-diario-estado-vazio.png           (mobile, estado de lista vazia do diário)
    desktop-01-cadastro-login.png        (desktop)
    desktop-02-busca.png                 (desktop)
    desktop-03-detalhe-avaliar.png       (desktop)
    desktop-04-diario.png                (desktop)
    desktop-04b-diario-estado-vazio.png  (desktop, estado de lista vazia do diário)
```

A pasta `wireframes/` contém as telas de baixa fidelidade em duas versões: **mobile** (arquivos `0X-*.png`) e **desktop** (arquivos `desktop-0X-*.png`), cobrindo cadastro/login, busca, detalhe/avaliação e diário (incluindo o estado de lista vazia).
