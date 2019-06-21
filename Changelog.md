# Changelog
Todas as mudanças deste projeto serão documentadas neste arquivo.

O modelo deste é baseado em [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
e este projeto adere à [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased
## [2.0.1] 22-04-2019
### Changed
- Implementação de validação para um único cadastro biométrico por conta.

### Fixed
- Sistema biométrico permitindo multiplos cadastros biométricos.

## [2.0.0] 15-04-2019
### Added
- Implementação de leitura biométrica para acesso de Usuário.
- Recarga de celular pelo aplicativo bancário. 
- Perfil de usuário.

### Changed
- Corrigido não reconhecimento do 9° número de celular na função de recarga.
- Corrigido não reconhecimento de caracteres especiais no perfil de usuário.
- Corrigido erro em transferências entre contas onde o valor retornava a conta de origem.
- Corrigido limite de crédito negativo.

### Removed
- Função de controle financeiro.

## [1.4.0] 25-03-2019
### Removed
- Controle financeiro.

## [1.3.0] 16-03-2019
### Added
- Implementação de leitura biométrica para acesso de Usuário.

## [1.2.1] 08-03-2019
### Changed
- Inclusão do 9° dígito automaticamente no campo de número de celular.

### Fixed
- 9° dígito nos números de celulares não reconhecido.

## [1.2.0] 01-03-2019
### Added
- Recarga de celular pelo aplicativo bancário. 

## [1.1.1] 26-02-2019
### Changed
- Padrão de caracteres especiais atualizado.

### Fixed
- Caracteres especiais não reconhecidos

## [1.1.0] 22-02-2019
### Added
- Perfil de usuário

## [1.0.2] 15-02-2019
### Changed
- Referênciado corretamente os campos de agência e conta do destinatário.

### Fixed
- Transferência entre contas retorna a conta de origem.

## [1.0.1] 08-02-2019
### Changed
- Adicionado um algoritmo validando os valores do limite, não permitindo serem menores que 0.

### Fixed
- Limite de crédito negativo.

## [1.0.0] 03-02-2019
### Added
- Controle financeiro.
- Consulta de limites de crédito.
- Transferência bancária entre contas.
- Consulta de extrato bancário.
- Acesso de usuário.

## [1.0.0-alpha.4] 28-01-2019
### Added
- Controle financeiro

## [1.0.0-alpha.3] 20-01-2019
### Added
- Consulta de limites de crédito

## [1.0.0-alpha.2] 15-01-2019
### Added
- Transferência bancária entre contas

## [1.0.0-alpha.1] 10-01-2019
### Added
- Consulta de extrato bancário

## [1.0.0-alpha] 04-01-2019
### Added
- Acesso de usuário
