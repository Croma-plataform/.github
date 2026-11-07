<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="imagens/croma-logotipo.svg">
    <source media="(prefers-color-scheme: light)" srcset="imagens/croma-logotipo-fundo-claro.svg">
    <img alt="Croma" src="imagens/croma-logotipo-fundo-claro.svg" width="420">
  </picture>
</p>

<p align="center"><b>Servidor de mídia pessoal, com identidade visual própria.</b></p>

O **Croma** reúne filmes, séries, música, fotos, TV ao vivo e livros num lugar só. Ele é feito sobre o Jellyfin (v12.4), com interface e marca próprias. O foco inicial é o desktop e a TV Samsung (Tizen); o celular vem depois.

A marca nasce de três ideias:

1. **As barras de cor das TVs antigas.** O padrão de teste servia para regular a imagem. No Croma, cada barra vira um tipo de mídia.
2. **Uma moldura 16:9,** como a de revista, mas deitada, no formato de uma tela de TV.
3. **"Croma" como luz e espectro:** cada cor carrega o seu comprimento de onda.

### Bibliotecas

| Barra | Biblioteca |
|---|---|
| `#C0C0C0` | Início |
| `#C0C000` | Filmes |
| `#00C0C0` | Séries |
| `#00C000` | Música |
| `#C000C0` | Fotos |
| `#C00000` | TV ao vivo |
| `#0000C0` | Livros |

### Repositórios

| Repositório | O que é |
|---|---|
| [`Croma`](https://github.com/Croma-plataform/Croma) | Hub: visão geral, arquitetura e especificações |
| `croma-identidade` | Identidade visual v0.1 "Barras": manual, logotipo e ícones |
| `croma-servidor` | Scripts e configuração do servidor |
| `croma-web` | Interface web, compartilhada pelo desktop e pela TV |
| `croma-desktop` | App desktop |
| `croma-tizen` | App da TV Samsung |
| `croma-android` | App Android (ainda não implementado) |
| `croma-v1` | Croma v1, arquivado |

Projeto pessoal. O código derivado do Jellyfin segue a licença GPL; o Croma não é afiliado ao projeto Jellyfin.
