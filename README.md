# Capwatch

Watch your cryptoportfolio in a console

![Demo](http://i.imgur.com/ZkrFDtL.png)

## Installation

    $ gem install capwatch

```bash
cat <<EOT > ~/.capwatch
{
  "name": "Basic Fund",
  "symbols": {
    "MAID": 25452.47,
    "GAME": 22253.51,
    "ANS": 3826.53,
    "FCT": 525.67875,
    "SC": 4152770,
    "DCR": 453.22,
    "BTC": 8.219,
    "ETH": 166.198,
    "KMD": 19056.20,
    "LSK": 5071.42
  }
}
EOT
```

    $ capwatch

## Fund Examples

Fund examples can be found [here](funds/demo)

Demo funds taken from www.bluemagic.info

Data is being processed from from http://coinmarketcap.com
