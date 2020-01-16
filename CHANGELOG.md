# Changelog
Todas as mudanças significativas nesse projeto serão documentadas neste arquivo.

O formato é baseado em [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), e este projeto adere ao [Versionamento Semântico](https://semver.org/spec/v2.0.0.html).

## [Não Publicado][Unreleased]

### Added/Adicionado
* Modelo de Relatório Médico em A4, para relatórios mais complexos. Por enquanto apenas em formato `INDD`.

### Changed/Modificado
* Adicionado CID-10 no SADT de Ultrassonografia obstétrica (`Z34.9`).

## [0.25.9] - `2020-01-04`

### Added/Adicionado
* Projeto de Acupuntura:
  - Logos colorido e preto-e-branco;
  - Folha de evolução - Grupo Inicial;
  - Cartão de Retornos - Grupo Inicial;
  - Guia de critérios de inclusão e exclusão do grupo.

### Changed/Modificado
* Transicionado maior parte do projeto para a [Licensa Hipocrática](https://firstdonoharm.dev/).

### Fixed/Corrigido
* Receita de Tuberculose (fase de manutenção): dose padrão é:
  - Rifampicina 150mg + Isonizida 75mg.

## [0.20.8] - `2019-12-28`

### Added/Adicionado
* Kits de Alto Custo:
  - Fenofibrato.
* Modelo próprio de TCLE para medicações de alto custo.

## [0.18.8] - `2019-12-27`

### Added/Adicionado
* Kits de Alto Custo:
  - Ciprofibrato;
  - Codeína;
  - Gabapentina;
  - Quetiapina.
* Receituários de infecções sexualmente transmissíveis:
  - Doença Inflamatória Pélvica:
    - *Ceftriaxona* e *azitromicina* (esta última incluída devido a protocolo do município de São Paulo que indica tratar preemptivamente uretrites, por alguma razão) em dose única;
    - *Doxiciclina* e *metronidazol* VO por 14 dias;
  - Vaginose bacteriana.

### Fixed/Corrigido
* Filipetas de convocação para Grupos agora são genéricas, e não específicas para grupo Psico.

## [0.12.7] - `2019-12-21`

### Added/Adicionado
* Filipetas de convocação para Grupos.
* Criado modelo de arquivo `CSV` para mala direta de convocação de Grupos.
  - ***Disclaimer:*** Dados do modelos são exemplos, com nomes gerados por computador, e não se referem a pessoas reais.

### Changed/Modificado
* Adicionado espaço para hora nas filipetas de Pregnosticon para grupo.
* Campo de nome do paciente nas filipetas de Pregnosticon (ambas) agora na camada da filipeta de modo a possibilitar mala direta (*data merge*).

## [0.11.6] - `2019-12-19`

### Added/Adicionado
* Kits de Alto Custo:
  - Atorvastatina; e
  - Clopidogrel.

### Changed/Modificado
* Logo de Pueri.

## [0.9.5] - `2019-12-09`

### Changed/Modificado
* Receituário de gestantes acima de 16 semanas:
  - Carbonato de cálcio agora com número de semanas de uso, ao invés de generizar "até 37sem".
* Receituários de puericultura com:
  - Metade apenas Adtil, metade Adtil e sulfato ferroso;
  - Duas metades apenas Adtil; e
  - Duas metades Adtil e sulfato ferroso.

## [0.8.4] - `2019-12-04`

### Added/Adicionado
* Filipeta de teste de gravidez urinário:
  - Modelo para solicitação *impromptu*;
  - Modelo para grupo de troca de receitas.

### Changed/Modificado
* SADTs:
  - Rastreio genérico agora inclui sorologias para HIV, Sífilis e Hepatites B e C.
  - Seguimento de HAS/DM movido para arquivo próprio, agora inclui também sorologias e radiografia de tórax.

## [0.6.4] - `2019-11-07`

### Changed/Modificado
* Filipetas de retorno:
  - Agora com as opções: grupo (a preencher), pré-natal, puericultura, tuberculose, e opção em branco (a preencher).
  - Reorganizada localização dos elementos.

## [0.6.3] - `2019-11-05`

### Added/Adicionado
* Filipetas de retorno.

### Changed/Modificado
* Receituários:
  - *Gestante &lt;14sem*: Removido repelente;
  - *Gestante &gt;16sem*: Removido repelente e paracetamol;
  - Repelente em algumas UBSs é distribuído diretamente no setor Mãe Paulistana, não na farmácia.

## [0.5.2] - `2019-10-29`

### Added/Adicionado
* SADT para seguimento de pacientes com Tuberculose.
* Receituários para RIPE (rifampicina + isoniazida + pirazinamida + etambutol) e RI (rifampicina + isoniazida).

## [0.4.2] - `2019-10-19`

### Added/Adicionado
* SADTs (Serviço de Apoio Diagnóstico Terapêutico) para condições mais comuns, e rastreamentos mais frequentes.
* Receituários para as patologias mais comuns cujo tratamento é protocolar, assim como receituários para puericultura e gestantes.

### Changed/Modificado
* Protocolo Mãe Paulistana - sorologias agora cobradas no 2º Trimestre devido ao estado epidemiológico de surto de Sífilis.
* Protocolo Mãe Paulistana - sorologia para toxo trimestral na gestante susceptível a toxoplasmose no 1º trimestre.

## [0.2.1] - `2019-10-10`

### Added/Adicionado
* Tabela de Cálculo de Idade Gestacional/Erro de Data, baseado em *Zugaib M, et al. Protocolos Assistenciais da Clínica Obstétrica da FMUSP. 5a Edição.*
* Protocolo Mãe Paulistana de indicação de USG morfológico na UBS.
* Regra para ignorar arquivos temporários de *InDesign*.

### Changed/Modificado
* Atualizada notificação de licensa Creative Commons na tabela principal do Mãe Paulistana.

## [0.1.0] - `2019-09-13`

### Added/Adicionado
* Código de Conduta de [Contributor Covenant v1.4.1](https://www.contributor-covenant.org/).
* [Licensa](LICENSE.md).
* Meta-arquivos git (`.gitignore` and `.gitattributes`).
* Templates do GitHub:
  - *Issues*;
  - Solicitação de melhoria;
  - Pergunta;
  - *Pull request*.
* Arquivo Leia-Me.
* Arquivo de Changelog.
* Arquivo de Guidelines de Contribuição.
* Guia do Mãe Paulistana.

[Unreleased]: https://github.com/Nereare/guias-ubs/compare/v0.25.9...HEAD
[0.25.9]: https://github.com/Nereare/guias-ubs/compare/v0.20.8...v0.25.9
[0.20.8]: https://github.com/Nereare/guias-ubs/compare/v0.18.8...v0.20.8
[0.18.8]: https://github.com/Nereare/guias-ubs/compare/v0.12.7...v0.18.8
[0.12.7]: https://github.com/Nereare/guias-ubs/compare/v0.11.6...v0.12.7
[0.11.6]: https://github.com/Nereare/guias-ubs/compare/v0.9.5...v0.11.6
[0.9.5]: https://github.com/Nereare/guias-ubs/compare/v0.8.4...v0.9.5
[0.8.4]: https://github.com/Nereare/guias-ubs/compare/v0.6.4...v0.8.4
[0.6.4]: https://github.com/Nereare/guias-ubs/compare/v0.6.3...v0.6.4
[0.6.3]: https://github.com/Nereare/guias-ubs/compare/v0.5.2...v0.6.3
[0.5.2]: https://github.com/Nereare/guias-ubs/compare/v0.4.2...v0.5.2
[0.4.2]: https://github.com/Nereare/guias-ubs/compare/v0.2.1...v0.4.2
[0.2.1]: https://github.com/Nereare/guias-ubs/compare/v0.1.0...v0.2.1
[0.1.0]: https://github.com/Nereare/guias-ubs/releases/tag/v0.0.1
