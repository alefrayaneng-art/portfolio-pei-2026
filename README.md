# Alef Lab: portfólio de trabalho 2026

Site estático (HTML e CSS próprios, sem build, sem script e sem fonte externa) com registros do trabalho de Alef Rayan em 2026 como professor do Programa Ensino Integral (PEI), em Jundiaí/SP: Robótica (3ª série A), Tecnologia e Inovação (6º ao 9º ano), Matemática (7º A), eletiva "Meu Mundo com IA" (6º e 7º anos) e tutoria.

O objetivo é mostrar à gestão escolar, com evidência, o trabalho feito. O texto descreve apenas o que cada arquivo mostra.

## Estrutura

| Página | Conteúdo |
|---|---|
| `index.html` | Capa, destaque do PDI 2026 (registro do Diário de Classe e acompanhamento no Professor Presente, em linha do tempo) e destaques |
| `protagonismo-juvenil.html` | Princípio: Protagonismo Juvenil |
| `pedagogia-da-presenca.html` | Princípio: Pedagogia da Presença |
| `educacao-interdimensional.html` | Princípio: Educação Interdimensional |
| `quatro-pilares.html` | Princípio: Quatro Pilares da Educação |
| `formacao-continuada.html` | Premissa: Formação Continuada |
| `replicabilidade.html` | Premissa: Replicabilidade |
| `corresponsabilidade.html` | Premissa: Corresponsabilidade (reunida com outras páginas, por falta de evidência própria forte) |
| `excelencia-em-gestao.html` | Premissa: Excelência em Gestão |
| `praticas-pei.html` | Eletivas, Guia de Aprendizagem, Nivelamento e Recuperação, Práticas Experimentais e Tutoria |

Cada página abre com a definição em uma linha e a fonte, seguida de cartões de evidência (título, data, turma, o que comprova e o arquivo ou a indicação de que ele não foi publicado). Clicar numa imagem a amplia (sem JavaScript, com `:target` do CSS).

`assets/` guarda as imagens (`pdi/`, `img/`), os PDFs (`pdf/`) e as miniaturas (`thumbs/`), com nomes curtos e sem dados pessoais.

## Privacidade

- Nenhum dado de estudante é publicado: listas, fichas, formulários respondidos e fotos com rosto ficam de fora.
- Capturas de sistema têm CPF, nome e foto de perfil ocultados.
- PDFs foram copiados sem metadados; imagens, sem EXIF.

## Como publicar no GitHub Pages

Envie esta pasta para um repositório e ative Pages na branch principal, pasta raiz. O arquivo `.nojekyll` evita processamento. Para ver localmente, abra `index.html`.

O arquivo `VERIFICACAO.md` (resultado das verificações e origem de cada evidência) fica fora do controle de versão (`.gitignore`) porque lista caminhos do computador do autor.
