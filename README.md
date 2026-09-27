# Design Essencial no Figma para Criadores v6.2

Curso aberto INEMA.CLUB. 18 aulas em 6 módulos, inspirado no OSWork v6.2. Caso fictício Luz de Rua.

Produção completa estimada: 8–12 horas, incluindo estudo e montagens. As práticas curtas não substituem a produção final. Computador e conta Figma necessários para editar.

Imagens criadas pelo recurso nativo de imagens do Codex. A ferramenta não expõe seletor nem confirmação de uma versão chamada 2.5; nenhum modelo externo foi substituído. Diagramas e exemplos tipográficos são HTML autoral, não capturas do Figma. A interface real do Figma não foi operada nesta produção; os caminhos foram conferidos na documentação oficial em 25/09/2026. O kit contém imagem e roteiro, não um arquivo .fig pronto.

Reconstrução: `python3 montar.py`. Evidências de auditoria e leitura em context/.

## English / Español

[English](https://inematds.github.io/curso-figma-criadores/en/) · [Español](https://inematds.github.io/curso-figma-criadores/es/)

Textos traduzidos com GPT-6 Luna por subagentes nativos da assinatura Codex, sem API externa. Ilustrações originais compartilhadas; progresso e anotações separados por idioma.

Após montar o português, reaplique os catálogos salvos:

```sh
python3 scripts/i18n_local.py build .
python3 scripts/verify_i18n.py .
node scripts/check_i18n_browser.cjs . /tmp/curso-i18n-checks
```

Requer Python/BeautifulSoup e os pacotes locais Babel/Playwright indicados nos scripts. A montagem não chama modelos nem redes. Mudanças na fonte PT exigem revisar os catálogos `i18n/`. O motor oficial `assets/curso.js` é preservado; a proteção de importação é gerada em `assets/curso-i18n.js` e nas edições traduzidas.

Evidências em `context/validacao-i18n.md`. Revisões por agentes são simuladas, não testes com alunos reais.
