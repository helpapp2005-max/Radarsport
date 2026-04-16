# Radarsport
npm install express axios cors
node server.js
http://localhost:3000/api/jogos
{
  "name": "radar-sport-api",
  "version": "1.0.4",
  "description": "datas e estatisticas de das maiores casas de aposta",
  "main": "index.js",
  "scripts": {
    "test": "node test.js"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/victorratts13/radar-sport-api.git"
  },
  "keywords": [
    "bet365",
    "betway",
    "betFair",
    "betano",
    "rivalo",
    "tipbet",
    "888sport",
    "sportingbet",
    "radar-sports",
    "radar-sport-api",
    "s5",
    "sport",
    "api"
  ],
  "author": "Victor Ratts",
  "license": "MIT",
  "bugs": {
    "url": "https://github.com/victorratts13/radar-sport-api/issues"
  },
  "homepage": "https://github.com/victorratts13/radar-sport-api#readme",
  "dependencies": {
    "axios": "^1.6.0"
  }
}

{
  "name": "radar-sport-api",
  "version": "1.0.4",
  "lockfileVersion": 2,
  "requires": true,
  "packages": {
    "": {
      "name": "radar-sport-api",
      "version": "1.0.4",
      "license": "MIT",
      "dependencies": {
        "axios": "^1.6.0"
      }
    },
    "node_modules/asynckit": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/asynckit/-/asynckit-0.4.0.tgz",
      "integrity": "sha512-Oei9OH4tRh0YqU3GxhX79dM/mwVgvbZJaSNaRk+bshkj0S5cfHcgYakreBjrHwatXKbz+IoIdYLxrKim2MjW0Q=="
    },
    "node_modules/axios": {
      "version": "1.8.2",
      "resolved": "https://registry.npmjs.org/axios/-/axios-1.8.2.tgz",
      "integrity": "sha512-ls4GYBm5aig9vWx8AWDSGLpnpDQRtWAfrjU+EuytuODrFBkqesN2RkOQCBzrA1RQNHw1SmRMSDDDSwzNAYQ6Rg==",
      "license": "MIT",
      "dependencies": {
        "follow-redirects": "^1.15.6",
        "form-data": "^4.0.0",
        "proxy-from-env": "^1.1.0"
      }
    },
    "node_modules/combined-stream": {
      "version": "1.0.8",
      "resolved": "https://registry.npmjs.org/combined-stream/-/combined-stream-1.0.8.tgz",
      "integrity": "sha512-FQN4MRfuJeHf7cBbBMJFXhKSDq+2kAArBlmRBvcvFE5BB1HZKXtSFASDhdlz9zOYwxh8lDdnvmMOe/+5cdoEdg==",
      "dependencies": {
        "delayed-stream": "~1.0.0"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/delayed-stream": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/delayed-stream/-/delayed-stream-1.0.0.tgz",
      "integrity": "sha512-ZySD7Nf91aLB0RxL4KGrKHBXl7Eds1DAmEdcoVawXnLD7SDhpNgtuII2aAkg7a7QS41jxPSZ17p4VdGnMHk3MQ==",
      "engines": {
        "node": ">=0.4.0"
      }
    },
    "node_modules/follow-redirects": {
      "version": "1.15.6",
      "resolved": "https://registry.npmjs.org/follow-redirects/-/follow-redirects-1.15.6.tgz",
      "integrity": "sha512-wWN62YITEaOpSK584EZXJafH1AGpO8RVgElfkuXbTOrPX4fIfOyEpW/CsiNd8JdYrAoOvafRTOEnvsO++qCqFA==",
      "funding": [
        {
          "type": "individual",
          "url": "https://github.com/sponsors/RubenVerborgh"
        }
      ],
      "engines": {
        "node": ">=4.0"
      },
      "peerDependenciesMeta": {
        "debug": {
          "optional": true
        }
      }
    },
    "node_modules/form-data": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/form-data/-/form-data-4.0.0.tgz",
      "integrity": "sha512-ETEklSGi5t0QMZuiXoA/Q6vcnxcLQP5vdugSpuAyi6SVGi2clPPp+xgEhuMaHC+zGgn31Kd235W35f7Hykkaww==",
      "dependencies": {
        "asynckit": "^0.4.0",
        "combined-stream": "^1.0.8",
        "mime-types": "^2.1.12"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/mime-db": {
      "version": "1.52.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.52.0.tgz",
      "integrity": "sha512-sPU4uV7dYlvtWJxwwxHD0PuihVNiE7TyAbQ5SWxDCB9mUYvOgroQOwYQQOKPJ8CIbE+1ETVlOoK1UC2nU3gYvg==",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/mime-types": {
      "version": "2.1.35",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.35.tgz",
      "integrity": "sha512-ZDY+bPm5zTTF+YpCrAU9nK0UgICYPT0QtT1NZWFv4s++TNkcgVaT0g6+4R2uI4MjQjzysHB1zxuWL50hzaeXiw==",
      "dependencies": {
        "mime-db": "1.52.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/proxy-from-env": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/proxy-from-env/-/proxy-from-env-1.1.0.tgz",
      "integrity": "sha512-D+zkORCbA9f1tdWRK0RaCR3GPv50cMxcrz4X8k5LTSUD1Dkw47mKJEZQNunItRTkWwgtaUSo1RVFRIG9ZXiFYg=="
    }
  },
  "dependencies": {
    "asynckit": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/asynckit/-/asynckit-0.4.0.tgz",
      "integrity": "sha512-Oei9OH4tRh0YqU3GxhX79dM/mwVgvbZJaSNaRk+bshkj0S5cfHcgYakreBjrHwatXKbz+IoIdYLxrKim2MjW0Q=="
    },
    "axios": {
      "version": "1.8.2",
      "resolved": "https://registry.npmjs.org/axios/-/axios-1.8.2.tgz",
      "integrity": "sha512-ls4GYBm5aig9vWx8AWDSGLpnpDQRtWAfrjU+EuytuODrFBkqesN2RkOQCBzrA1RQNHw1SmRMSDDDSwzNAYQ6Rg==",
      "requires": {
        "follow-redirects": "^1.15.6",
        "form-data": "^4.0.0",
        "proxy-from-env": "^1.1.0"
      }
    },
    "combined-stream": {
      "version": "1.0.8",
      "resolved": "https://registry.npmjs.org/combined-stream/-/combined-stream-1.0.8.tgz",
      "integrity": "sha512-FQN4MRfuJeHf7cBbBMJFXhKSDq+2kAArBlmRBvcvFE5BB1HZKXtSFASDhdlz9zOYwxh8lDdnvmMOe/+5cdoEdg==",
      "requires": {
        "delayed-stream": "~1.0.0"
      }
    },
    "delayed-stream": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/delayed-stream/-/delayed-stream-1.0.0.tgz",
      "integrity": "sha512-ZySD7Nf91aLB0RxL4KGrKHBXl7Eds1DAmEdcoVawXnLD7SDhpNgtuII2aAkg7a7QS41jxPSZ17p4VdGnMHk3MQ=="
    },
    "follow-redirects": {
      "version": "1.15.6",
      "resolved": "https://registry.npmjs.org/follow-redirects/-/follow-redirects-1.15.6.tgz",
      "integrity": "sha512-wWN62YITEaOpSK584EZXJafH1AGpO8RVgElfkuXbTOrPX4fIfOyEpW/CsiNd8JdYrAoOvafRTOEnvsO++qCqFA=="
    },
    "form-data": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/form-data/-/form-data-4.0.0.tgz",
      "integrity": "sha512-ETEklSGi5t0QMZuiXoA/Q6vcnxcLQP5vdugSpuAyi6SVGi2clPPp+xgEhuMaHC+zGgn31Kd235W35f7Hykkaww==",
      "requires": {
        "asynckit": "^0.4.0",
        "combined-stream": "^1.0.8",
        "mime-types": "^2.1.12"
      }
    },
    "mime-db": {
      "version": "1.52.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.52.0.tgz",
      "integrity": "sha512-sPU4uV7dYlvtWJxwwxHD0PuihVNiE7TyAbQ5SWxDCB9mUYvOgroQOwYQQOKPJ8CIbE+1ETVlOoK1UC2nU3gYvg=="
    },
    "mime-types": {
      "version": "2.1.35",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.35.tgz",
      "integrity": "sha512-ZDY+bPm5zTTF+YpCrAU9nK0UgICYPT0QtT1NZWFv4s++TNkcgVaT0g6+4R2uI4MjQjzysHB1zxuWL50hzaeXiw==",
      "requires": {
        "mime-db": "1.52.0"
      }
    },
    "proxy-from-env": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/proxy-from-env/-/proxy-from-env-1.1.0.tgz",
      "integrity": "sha512-D+zkORCbA9f1tdWRK0RaCR3GPv50cMxcrz4X8k5LTSUD1Dkw47mKJEZQNunItRTkWwgtaUSo1RVFRIG9ZXiFYg=="
    }
  }
}


![logo](https://github.com/victorratts13/radar-sport-api/blob/master/assets/img/radar-logo-2.png?raw=true)
![versão](https://img.shields.io/badge/Vers%C3%A3o-1.0.4-brightgreen) ![lang](https://img.shields.io/badge/Language-JavaScript-yellowgreen) ![man](https://img.shields.io/badge/Mananger-NPM-red)
Resumo
Radar Sport API é uma biblioteca para desenvolvimento de dados e estatisticas de jogos e casas de apostas para desenvolvimento de sistemas automatizados e cruzamento de dados. Nele é encontrado os dados e estatisticas das maiores casas de apostas.
Com ele é possivel obter dados de times, ligas, informações de jogos (passados ao vivo ou futuros) e com amplo esquema estatisticas.
Casas de aposta suportadas
É possivel obter dados e analises de diversas casas de apostas como:
bet365
betway
betFair
betano
rivalo
tipbet
888sport
sportingbet
Instalação
Para instalar utilize o gerenciador de pacotes npm
~~~bash
~$ npm install radar-sport-api --save
~~~
Configuração da casa de aposta
Após a instalação, importe a biblioteca e defina a sua betPlace
~~~javascript
//importe as bibliotecas de classe
const { sportApi } = require('radar-sport-api');
//contrua as classes
const betfair = new sportApi('betfair', { getCommonContents: false });
const bet365 = new sportApi('bet365', { getCommonContents: false });
~~~
>- OBS: ```getCommonContents``` é um metodo ultilizado para obter os "status" de servidores da sua casa de aposta. Caso haja necessidade de utilizar, defina como ```true```
Requisitando dados
A requisição de dados é feita de forma simples. Definindo
Região
Metodo
Valor
Sendo:  
Metodo : o dado q se deseja obter ou endpoind a acessar;  
Região : a hora regional q se deseja obter;  
Valor  : é o valor é chave ou Id de requisição.

Para isso, execute como exemplo:
~~~javascript
betfair.getInfo('Europe:Berlin', 'stats_season_meta', 76415).then((data) => {
console.log(data)
})
~~~
Você obterá isso:
~~~node
{
event: 'stats_season_meta',
_dob: 1593747415,
_maxage: 3600,
data: {
season: {
_id: '76415',
_doc: 'season',
_utid: 325,
_sid: 1,
name: 'Brasileiro Serie A 2020',
abbr: 'BSA 2020',
start: [Object],
end: [Object],
neutralground: false,
friendly: false,
currentseasonid: 76415,
year: '2020',
coverage: [Object],
h2hdefault: [Object]
},
sport: { _doc: 'sport', _id: 1, _sid: 1, name: 'Soccer' },
realcategory: {
_doc: 'realcategory',
_id: 13,
_sid: 1,
_rcid: 13,
name: 'Brazil',
cc: [Object]
},
tournamentids: [ 83 ],
tableids: [ 50119 ],
cupids: [],
uniquetournament: {
_doc: 'uniquetournament',
_id: 325,
_utid: 325,
_sid: 1,
_rcid: 13,
name: 'Brasileiro Serie A',
currentseason: 76415,
friendly: false
},
statscoverage: {
complexstat: true,
livetable: true,
halftimetable: true,
overunder: true,
overunderhalftime: true,
fixtures: true,
leaguetable: true,
tablerules: true,
headtohead: true,
formtable: true,
secondhalftables: true,
divisionview: true,
matchdetails: true,
lineups: true,
formations: true,
topgoals: true,
topassists: true,
disciplinary: true,
redcards: true,
yellowcards: true,
goalminute: true,
goalminscorer: true,
substitutions: true,
squadservice: true,
livescoreeventthrowin: true,
livescoreeventgoalkick: true,
livescoreeventfreekick: true,
livescoreeventshotsoffgoal: true,
livescoreeventshotsongoal: true,
livescoreeventgoalkeepersave: true,
livescoreeventcornerkick: true,
livescoreeventoffside: true,
livescoreeventfouls: true,
livescoreeventpossesion: true,
referee: true,
stadium: true,
staffmanagers: true,
staffteamofficials: false,
staffassistantcoaches: false,
jerseys: true
}
}
}
~~~
Lista de Esportes
Cada esporte, possui uma id que por definição, executa funções de dentro da api para a biblioteca. Aqui está uma lista de Esportes e suas IDs
esporte	id
Futebol Americano	16
Futebol Australiano	13
Andebol	6
badminton	31
bandy	15
basebal	3
basquetebol	2
Ciclismo	7
Corridas Motorizadas	190
Corridas Touring Car	188
Corridas de Stock Car	191
Counter-Strike	109
Cricket	21
Dardos	22
Corrida de Motos	11
DOTA	11
FloorBall	7
Futebol	1
Futebol de praia	60
Futsal	29
Formula 1	40
Hoquei de Campo	24
Hoquei de gelo	4
Corrida Indy	129
League Of Legends	110
Polo Aquatico	26
Rugby	12
Speedway	131
Tenis	5
Tenis de mesa	20
Volei	23
Volei de praia	34
Regiões
Atualmente as regiões e horarios suportados são:
região	hora
America:Argentina:Buenos_Aires	GMT-3
Europe:Berlin	GMT+2
Metodo `sportData` Para analise de dados
Para api de analise informações em massa, utilize a classe `sportData` para obter as informações que precisa.
```js
//importe as bibliotecas de classe
const { sportData } = require('radar-sport-api');
//contrua as classes
const betfair = new sportData('betfair', { 
  languageId: '514d1e14ad5c11eeebf17ba7f5dc97ad', 
  server: 'gismo', 
  getCommonContents: false, 
  lang: 'en'
});

betfair.getInfo('Europe:Berlin', 'stats\_season\_meta', 76415).then((data) => {
    console.log(data)
})
```
Obtendo dados atraves de um path especifico.
Caso conheça as rotas de indexação da S5 do sport-radar, você pode obter as informações necessarias atraves de um path especifico.
```js
betfair.getByPath('en/America:Montevideo/gismo/config\_tree\_mini/41/0/16').then(data => {
  console.log(data)
})
```
Notas de desenvolvimento
Para mais informações:
> Telegram: @vratts \\
> Email: victor@vratts.com

node_modules/
