# enviroplus-btc
Turn your enviro+ sensor into a bitcoin price display.

## Requirements
1. Raspberry Pi with an internet connection (for the API call out for the exchange rate)
2. An Enviro+ Sensor. Example: https://shop.pimoroni.com/products/enviro?variant=31155658457171

## Quick Start

1. `curl -sSL https://get.pimoroni.com/enviroplus | bash`
2. `cd enviroplus-python/examples/`
3. `pip install requests`
4. `curl -sSL -O https://raw.githubusercontent.com/jdabs/enviroplus-btc/main/btc-24hrprice.py`
5. `./btc-24hrprice.py`

