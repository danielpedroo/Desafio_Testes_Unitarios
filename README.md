# Projeto de Testes Unitários em C# - DIO Trilha .NET

Este projeto faz parte da trilha .NET oferecida pela DIO (Digital Innovation One) e tem como objetivo implementar testes unitários para um sistema existente. O contexto do projeto envolve a resolução de problemas frequentes no software, como bugs, falhas de validação, entre outros, por meio da implementação de testes unitários.

## Estrutura do Projeto
O projeto consiste em dois componentes principais: um projeto console e um projeto de testes usando xUnit.

### Projeto Console
O projeto console possui duas classes principais: `ValidacoesLista` e `ValidacoesString`. Essas classes contêm métodos responsáveis por realizar diversas validações em listas e strings, respectivamente.

#### Classe `ValidacoesLista`

- `RemoverNumerosNegativos`: Remove os números negativos de uma lista.
- `ListaContemDeterminadoNumero`: Verifica se um número está presente na lista.
- `MultiplicarNumerosLista`: Multiplica todos os elementos da lista por um número.
- `RetornarMaiorNumeroLista`: Retorna o maior número presente na lista.
- `RetornarMenorNumeroLista`: Retorna o menor número presente na lista.

#### Classe `ValidacoesString`

- `RetornarQuantidadeCaracteres`: Retorna a quantidade de caracteres em um texto.
- `ContemCaractere`: Verifica se um determinado trecho está presente no texto.
- `TextoTerminaCom`: Verifica se um trecho está presente no final do texto.

### Projeto de Testes (xUnit)
O projeto de testes contém classes de teste correspondentes às classes do projeto console, ou seja, `ValidacoesListaTests` e `ValidacoesStringTests`. Cada classe de teste contém métodos de teste para validar os métodos das classes correspondentes.

#### Classe `ValidacoesListaTests`

- `DeveRemoverNumerosNegativosDeUmaLista`: Testa se os números negativos são removidos corretamente da lista.
- `DeveConterONumero9NaLista`: Verifica se a presença do número 9 na lista é corretamente identificada.
- `NaoDeveConterONumero10NaLista`: Garante que a ausência do número 10 na lista é corretamente identificada.
- `DeveMultiplicarOsElementosDaListaPor2`: Testa a correta multiplicação de todos os elementos da lista por 2.
- `DeveRetornar9ComoMaiorNumeroDaLista`: Verifica se o método retorna corretamente o maior número da lista.
- `DeveRetornarOitoNegativoComoMenorNumeroDaList`: Testa se o método retorna corretamente o menor número da lista.

#### Classe `ValidacoesStringTests`

- `DeveRetornar6QuantidadeCaracteresDaPalavraMatrix`: Testa se a contagem correta de caracteres é retornada para a palavra "Matrix".
- `DeveContemAPalavraQualquerNoTexto`: Verifica se a presença da palavra "qualquer" no texto é corretamente identificada.
- `NaoDeveConterAPalavraTesteNoTexto`: Testa a correta identificação da ausência da palavra "teste" no texto.
- `TextoDeveTerminarComAPalavraProcurado`: Verifica se o texto termina corretamente com a palavra "procurado".

## Implementação dos Testes
O projeto de testes já possui uma estrutura inicial, incluindo classes e métodos de teste. A implementação dos testes deve ser concluída, conforme as regras estabelecidas, para garantir uma cobertura eficaz das funcionalidades do sistema.

O código-fonte e as instruções detalhadas podem ser encontrados [aqui](https://github.com/danielpedroo/trilha-net-testes-unitarios-desafio). Este projeto é uma contribuição valiosa para a prática de testes unitários na trilha .NET da DIO.
