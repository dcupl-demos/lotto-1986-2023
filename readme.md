<div align="center">
	<h1 align="center">dcupl-demos/lotto-1986-2022</h1>
	<p align="center">Lottery numbers in Austria from 1986 til 2022<br />Demo project for <a href="http://www.dcupl.com?utm_source=github.com&utm_medium=readme&utm_campaign=dcupl-demos-lotto" target="_blank">dcupl</a>, App Development Platform for Data-Intensive Web Applications.</p> <br />
</div>

<p align="center">
<strong>@dcupl/cli</strong><br/>
  <a href="https://npmjs.com/package/@dcupl/cli">
    <img src="https://img.shields.io/npm/v/@dcupl/cli/latest.svg?style=flat-square" alt="dcupl CLI" />
  </a>
  <a href="https://npmjs.com/package/@dcupl/cli" rel="nofollow">
    <img src="https://img.shields.io/npm/dt/@dcupl/cli.svg?style=flat-square" alt="dcupl CLI">
  </a>
</p>

<p align="center">
<strong>@dcupl/core</strong><br/>
  <a href="https://npmjs.com/package/@dcupl/core">
    <img src="https://img.shields.io/npm/v/@dcupl/core/latest.svg?style=flat-square" alt="dcupl CLI" />
  </a>
  <a href="https://npmjs.com/package/@dcupl/core" rel="nofollow">
    <img src="https://img.shields.io/npm/dt/@dcupl/core.svg?style=flat-square" alt="dcupl Core">
  </a>
</p>

<p align="center">
  <a href="https://github.com/dcupl" title="dcupl on github"><span class="sr-only">GitHub</span><svg fill="#0225EE" width="30" heigth="30"><path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd"></path></svg></a>
</p>

<hr>

# Lotto AUT 1986-2022

This Project was generated using the `@dcupl/cli`. More information can be found on [https://dcupl.com](https://dcupl.com) and especially in the [dcupl Docs](https://docs.dcupl.com).

## win2day dataset
The initial dataset is published by win2day - https://www.win2day.at/lotterie/lotto/lotto-statistik-zahlen-ergebnisse-download - the online gaming platform of the Austrian Lotteries. The formatting of the original data has been revised and redundancies have been reduced. The data respectively the whole project is also published on [kaggle](https://www.kaggle.com/datasets/gernotbernkopf/lottery-austria-1986-til-2022).

## different currencies
Be aware that winning totals up to 2001 are in ATS - Austria's currency _Schilling_ - and in EUR starting with 2001 up to 2022. Therefore three applications have been defined and the resources have been tagged with ATS and EUR.

## dcupl Expressions
The model description includes two ***expressions***, which concatenate the drawn numbers - on the one hand sorted in ascending order and on the other hand sorted as drawn.

### 1) Setup

```
npm install
```

### 2) Connect your local project with the dcupl Console

- Go to [https://console.dcupl.com](https://console.dcupl.com) and create your **free** account.
- Set your `projectId` in the dcupl.config.json
- Set your `apiKey` in the dcupl.secrets.json
- Push your local workspace to the dcupl Console using the CLI `dcupl files:push --tag my-first-push`


### 3) Start your development server

```
dcupl serve
```

### 4) View your data in the dcupl Console
Switch to "Local Dev Server" and open one of the predefined applications. View your data in the **Data Explorer Tab** in the dcupl Console.