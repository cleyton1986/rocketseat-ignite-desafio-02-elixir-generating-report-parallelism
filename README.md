<p align="center">
  <img  src="./assets/cover-elixir.png">
</p>

<h1 align="center">
  Ignite (Elixir) - Rocketseat
</h1>

<h3 align="center">
  Desafio 02 - Gerando relatórios usando Paralelismo
</h3>

<blockquote align="center">“Tudo deveria se tornar o mais simples possível, mas não simplificado - Albert Einstein”!</blockquote>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/cleyton1986/rocketseat-ignite-desafio-02-elixir-generating-report-parallelism?color=%2304D361">

  <a href="https://www.linkedin.com/in/cleytonalves">
    <img alt="Made by Cleyton" src="https://img.shields.io/badge/Made%20by-Cleyton_Alves-Alves%2304D361">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">

  <a href="https://github.com/cleyton1986/rocketseat-ignite-desafio-02-elixir-generating-report-parallelism/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/cleyton1986/rocketseat-ignite-desafio-02-elixir-generating-report-parallelism?style=social">
  </a>
</p>

<p align="center">
  <a href="#tecnologias-e-recursos">Tecnologias e Recursos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#específicação-dos-testes">Especificação de testes</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#instalação-e-execução">Instalação e execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#calendar-entrega">Entrega</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>


## Tecnologias e recursos

- [Elixir](https://elixir-lang.org/install.html)
- [CSV](https://pt.wikipedia.org/wiki/Comma-separated_values)

</br>

## Sobre o desafio

Nesse desafio, você deverá gerar o mesmo relatório com os mesmos dados do desafio anterior mas dessa vez os dados estão fracionados em três arquivos com 10 mil linhas cada e o relatório deve ser gerado usando esses três arquivos em paralelo.

Observe que o resultado final do cálculo de horas de cada pessoa para ano, mês e total de horas deve ser o mesmo do desafio anterior, já que os dados continuam iguais.

O relatório gerado a partir dos arquivos (que estão disponíveis para download logo abaixo) deve estar no seguinte formato:

```js 
%{
  all_hours: %{
        danilo: 500,
        rafael: 854,
        ...
    },
  hours_per_month: %{
        danilo: %{
            janeiro: 40,
            fevereiro: 64,
            ...
        },
        rafael: %{
            janeiro: 52,
            fevereiro: 37,
            ...
        }
    },
  hours_per_year: %{
        danilo: %{
            2016: 276,
            2017: 412,
            ...
        },
        rafael: %{
            2016: 376,
            2017: 348,
            ...
        }
    }
}

```

Os caracteres ... é o espaço onde ficaria o resto dos dados. Esse é apenas um exemplo visual do que o retorno da função deve possuir, beleza?

</br>

##  Download do arquivos

  - [part_1.csv](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/ef3f1650-5374-4430-bc33-e89b51ad949a/part_1.csv?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221009%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221009T171439Z&X-Amz-Expires=86400&X-Amz-Signature=3a6ca573d89e80c776360553e7ee101df7fecd6f13e514d81aae6e4386c67f74&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22part_1.csv%22&x-id=GetObject)
  - [part_2.csv](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/019635f0-d0ed-4b42-b69b-939d7492563c/part_2.csv?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221009%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221009T171454Z&X-Amz-Expires=86400&X-Amz-Signature=acbba6d6829dc3db1e469e5a667aed0b7b7bca060406f468fb2b9cf426f5150c&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22part_2.csv%22&x-id=GetObject)
  - [part_3.csv](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/4800edf6-8d81-4209-9841-b45a9d8fa951/part_3.csv?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221009%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221009T171507Z&X-Amz-Expires=86400&X-Amz-Signature=941ef4e47d2d52cf08409c9d909ac93fde2472bdfdb9605b9f9571153a8cf413&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22part_3.csv%22&x-id=GetObject)

</br>

## Específicação dos testes

### Você deve cumprir para que os testes do desafio anteiror passem.
</br>

## :calendar: Entrega

Esse desafio foi entregue na plataforma Skylab - Rocketseat.
</br>

<p align="center">
  <img  src="./assets/test-result.png">
</p>

## Instalação e execução
</br>


### Configuração do ambiente:
<p>
  💿 (
    <a href="https://www.notion.so/Ambiente-de-desenvolvimento-Trilha-Elixir-aa2399b4ec17447582d04cbce8ffa12f">Guia de instalação e configuração do Ambiente - Elixir </a>
  )
</p>
</br>

```bash
# OBS.: ANTES DE PROCEDIMENTO, CERTIFIQUE-SE QUE O ELIXIR ESTEJA INSTALADO NO SEU COMPUTADOR CORRETAMENTE.

# Clone esse repositório
$ git clone https://github.com/cleyton1986/rocketseat-ignite-desafio-02-elixir-generating-report-parallelism

# Entre no diretório
$ cd rocketseat-ignite-desafio-02-elixir-generating-report-parallelism

# baixe as dependencias
$ mix deps.get

# para compilar o projeto, execute o comando
$ mix compile

# para rodar os testes, execute o comando
$ mix test

# para mais detalhes
$ mix test --cover

# acessando o iex
$ iex -S mix

# teste usando o paralelismo (usando o iex)
iex> ReportsHoursParallel.build(["part-1.csv", "part-2.csv", "part-3.csv"])
```
## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

 implementado por 👨🏽‍💻 Cleyton Alves e desenvolvido 💜 by Rocketseat.
