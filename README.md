# PSD_Therapies

Catálogo público de packs de experiências demonstrativas do projeto **PSD Serious Game** em Godot 4.

A aplicação consulta `terapias/catalogo.json` e permite descarregar individualmente os ficheiros de cada terapia para a pasta local do utilizador.

## Packs disponíveis

- **Tricofobia (Seringas)** — protótipo inicial com manifesto e prompt de demonstração. A designação clínica habitual do medo de agulhas é *tripanofobia*; o nome de interface conserva a designação do projeto.
- **Aracnofobia** — exemplo incompleto.
- **Claustrofobia** — exemplo incompleto.

Os packs ainda não constituem tratamentos clínicos funcionais ou validados. A cena 3D e a IA terapêutica ainda não estão implementadas.

## Adicionar conteúdo a um pack

Colocar os recursos na pasta `terapias/<id>/` e manter o respetivo `manifest.json` atualizado. O catálogo principal em `terapias/catalogo.json` identifica os packs apresentados pela aplicação.

Não incluir dados pessoais, credenciais ou informação confidencial neste repositório público.
