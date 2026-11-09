# Taió Plumbing System — Hub

**Versão 1.0** · Projeto *Taió Plumbing System* (Mestrado em Geologia, UFSC)

🔗 **Acesso:** <https://thubaraleii.github.io/TAIO-HUB/>

Página inicial que reúne as quatro aplicações web do projeto de modelagem do sistema intrusivo de Taió (SC).

## Conteúdo

| Aplicação | Descrição |
|---|---|
| **Modelo 3D interativo** | Bloco 3D com topografia, unidades, soleiras/diques e ferramenta de corte |
| **Seção 2D interativa** | Mapa em planta + seção transversal sincronizados, com linhas de corte livres e traçados fixos |
| **Dashboard geoquímico** | Diagramas de classificação, critérios de Peate, ETR, Harker e mapa sincronizado |
| **Webmap** | Mapa Leaflet em tela cheia com geologia, estruturas, poços e geoquímica |

Cada aplicação é um repositório independente, publicado em GitHub Pages:
[taio-plumbing-system-3d](https://github.com/Thubaraleii/taio-plumbing-system-3d) ·
[taio-plumbing-system-2d](https://github.com/Thubaraleii/taio-plumbing-system-2d) ·
[TAIO-DASH](https://github.com/Thubaraleii/TAIO-DASH) ·
[TAIO-WEBMAP](https://github.com/Thubaraleii/TAIO-WEBMAP).

## Idioma

O botão **EN / PT** alterna a página entre português e inglês; a escolha é lembrada no navegador e repassada aos aplicativos pelo parâmetro `?lang=en`. Cada aplicativo traz também o botão **← Hub** para voltar a esta página.

## Uso

Abra `index.html` no navegador ou acesse a versão publicada (GitHub Pages). Não requer instalação nem servidor.

## Estrutura

```
index.html        página do hub
assets/           logotipo e ícones
```

## Referências

1. Milani, E. J.; Melo, J. H. G.; Souza, P. A.; Fernandes, L. A.; França, A. B. (2007). Bacia do Paraná. *Boletim de Geociências da Petrobras*, 15(2), 265–287.
2. Schneider, R. L.; Mühlmann, H.; Tommasi, E.; Medeiros, R. A.; Daemon, R. F.; Nogueira, A. A. (1974). Revisão estratigráfica da Bacia do Paraná. In: *Anais do 28º Congresso Brasileiro de Geologia*, Porto Alegre, SBG, 1, 41–65.
3. Frank, H. T.; Gomes, M. E. B.; Formoso, M. L. L. (2009). Review of the areal extent and the volume of the Serra Geral Formation, Paraná Basin, South America. *Pesquisas em Geociências*, 36(1), 49–57.
4. Peate, D. W. (1997). The Paraná–Etendeka Province. In: Mahoney, J. J.; Coffin, M. F. (eds.), *Large Igneous Provinces*. AGU Geophysical Monograph 100, 217–245.
5. Agafonkin, V. **Leaflet** — an open-source JavaScript library for interactive maps. <https://leafletjs.com>
6. Plotly Technologies Inc. (2015). **Collaborative data science** (Plotly.js). Montréal. <https://plot.ly>
7. Mapzen / Amazon Web Services. **Terrain Tiles** (formato Terrarium). <https://registry.opendata.aws/terrain-tiles/>
8. OpenStreetMap contributors. **OpenStreetMap**. <https://www.openstreetmap.org/copyright>
9. CPRM/SGB — Serviço Geológico do Brasil. **Geologia e Recursos Minerais do Estado de Santa Catarina — Mapa Geológico 1:500.000 (SIG SC)**. <https://geosgb.sgb.gov.br>
10. ANP — Agência Nacional do Petróleo, Gás Natural e Biocombustíveis. **Dados abertos — poços**. <https://www.gov.br/anp>
11. Harris, C. R. et al. (2020). Array programming with NumPy. *Nature*, 585, 357–362.
12. Virtanen, P. et al. (2020). SciPy 1.0: fundamental algorithms for scientific computing in Python. *Nature Methods*, 17, 261–272.
13. Jordahl, K. et al. **GeoPandas**. Zenodo. <https://geopandas.org>; Gillies, S. et al. **Shapely** e **Rasterio**. <https://github.com/shapely/shapely>, <https://github.com/rasterio/rasterio>.

## Licença e uso

- **Código** (scripts de geração e JavaScript das páginas): licença **MIT** — ver [`LICENSE`](LICENSE).
- **Produtos gerados** (HTML, figuras, tabelas derivadas): **CC BY 4.0** — uso, adaptação e redistribuição permitidos com atribuição ao autor.
- **Dados de terceiros** incorporados mantêm as licenças e os termos das fontes originais (tabela em *Créditos e fontes de dados*).
- Os modelos são **interpretativos** e dependem da qualidade e da densidade dos dados de entrada; **não substituem** estudo geológico, hidrogeológico ou geotécnico de detalhe, nem devem ser usados como base única para decisões de engenharia, perfuração ou licenciamento.
- Fornecido “como está”, sem garantias de qualquer tipo.

## Créditos e fontes de dados

| Fonte | Uso | Termos |
|---|---|---|
| Levantamento de campo do autor (pontos, estruturas, geoquímica, MDE de drone) | Dados primários da área de Taió | CC BY 4.0 (autor) |
| CPRM/SGB — Mapa Geológico do Estado de Santa Catarina 1:500.000 (SIG SC) | Geologia regional, falhas, fraturas e diques regionais | Dados abertos CPRM/SGB — citar a fonte |
| ANP — Tabela de poços (dados abertos) | Poços de petróleo/gás (posição e profundidade total) | Dados abertos ANP — citar a fonte |
| Cadastro de poços do Sistema Aquífero Guarani (SAG) | Poços do SAG (posição e profundidade), arquivo KML do projeto | Citar a fonte original do cadastro |
| OpenStreetMap contributors | Rios, estradas e localidades | ODbL 1.0 — © OpenStreetMap contributors |
| Esri World Imagery | Imagem de satélite (tiles e textura) | Termos da Esri — uso com atribuição |
| CARTO / OpenTopoMap | Mapas base do webmap | Atribuição nos próprios mapas (OSM, SRTM, OpenTopoMap CC-BY-SA) |
| AWS Terrain Tiles (formato Terrarium) | Relevo e batimetria regionais (derivados de SRTM, GEBCO e outras fontes) | Atribuição conforme o provedor dos tiles |
| Plotly.js (MIT), Leaflet (BSD-2-Clause) | Bibliotecas de visualização embutidas/carregadas nas páginas | Licenças originais |

## Como citar

> JESUS, A. H. de. **Taió Plumbing System — Hub**, versão 1.0. 2026. Projeto *Taió Plumbing System* — Mestrado em Geologia, UFSC. Disponível em: <https://thubaraleii.github.io/TAIO-HUB/>.

## Autoria

**Afonso Henrique de Jesus** — Mestrado em Geologia, Universidade Federal de Santa Catarina (UFSC).
Projeto: *Architecture and Geochemical Evolution of the Taió Intrusive Plumbing System* (Taió, SC — Bacia do Paraná).
