# Base de Dados de Impactos de PSA em Regiões Tropicais

Site estático para disponibilização do Produto Técnico-Tecnológico da dissertação:

**Impactos socioeconômicos e ambientais de Pagamento por Serviços Ambientais em regiões tropicais: uma revisão sistemática**

Autor: **Alexander Afonso Nogueira Cavalcante**  
Programa de Pós-Graduação em Economia Profissional — Universidade Federal do Amazonas

## O que há neste repositório

```text
.
├── index.html
├── style.css
├── script.js
├── .nojekyll
└── data/
    ├── base-dados-psa-tropicos.xlsx
    ├── base-dados-psa-tropicos.csv
    ├── estudos-resumo.json
    └── dicionario-de-dados.csv
```

## Como publicar no GitHub Pages

1. Crie um repositório público no GitHub.
2. Envie todos os arquivos deste pacote para a raiz do repositório.
3. Abra **Settings > Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/root`.
6. Clique em **Save**.

A página ficará disponível em:

```text
https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/
```

Se o repositório se chamar `SEU-USUARIO.github.io`, a página ficará em:

```text
https://SEU-USUARIO.github.io/
```

## Teste local

Para testar antes de enviar ao GitHub, abra a pasta no terminal e rode:

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

Abrir o `index.html` diretamente no navegador pode impedir o carregamento do JSON por restrições de segurança do navegador.

## Atualização dos dados

- Substitua `data/base-dados-psa-tropicos.xlsx` pela nova versão da planilha completa.
- Substitua `data/base-dados-psa-tropicos.csv` pela versão CSV completa.
- Atualize `data/estudos-resumo.json` caso queira que a tabela interativa reflita novos estudos.
- Atualize `data/dicionario-de-dados.csv` caso novas variáveis sejam adicionadas.

## Licença

Defina uma licença antes da publicação final. Sugestões comuns:

- **Código do site:** MIT License.
- **Base de dados:** CC BY 4.0 ou CC0, conforme a intenção de reutilização.

## Citação sugerida

Cavalcante, A. A. N. (2026). *Base de dados de impactos de Pagamentos por Serviços Ambientais em regiões tropicais* [Dataset]. GitHub.
