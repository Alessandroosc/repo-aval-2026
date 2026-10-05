# Changelog

Todas as mudanças relevantes deste projeto são documentadas neste arquivo.

O formato segue o [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/)
e o projeto adota o [Versionamento Semântico](https://semver.org/lang/pt-BR/).

## [1.1.0] - 2026-10-05

### Adicionado

- Testes para validar notas inválidas e os limites de 0 e 10.
- Classificação de alunos com média igual ou superior a 9,0 como “Aprovado com distinção”.

### Alterado

- Cálculo da média simplificado com métodos de array, sem mudança de comportamento.
- Média exibida com uma casa decimal e vírgula como separador.

### Corrigido

- Classificação da média 7,0 como “Aprovado”.

## [1.0.0] - 2026-09-14

### Adicionado

- Cálculo da média aritmética das notas.
- Classificação da situação do aluno: Aprovado, Recuperação ou Reprovado.
- Execução pela linha de comando (`npm start -- <notas>`).
- Integração contínua com testes e verificação de Conventional Commits.
