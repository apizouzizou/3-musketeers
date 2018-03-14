# cash

## currencies converter

Cash is a currency converter API. It permits you to convert any amount from a currency to another one
he is written in node.js. all the currencies are display [RightHere](http://akep.us/currencies)

## Installation

First, Fork and Clone the repo on our device, then install dependencies running the next commande

```
$  npm install
```

## Usage

Using the API in terminal with next command :

```
$ node bin/index.js <amount> <currency> <currency>
```


Set the default currency

```
$ node bin/index.js --save <currency>
```

Exemple :

```
$ node index.js 10 eur usd
```

## Useful Commands

```$node index.js <commands>
```

--help to show the help message.
--version to show the version number.
