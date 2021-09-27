
Copied this Connector initially from the Blocktane code 26-Jun-2021 PMC

Initially from Hummingbot 0.40 (current latest) release.

To use, in the console select "connect", then "Peatio" for exchange.

If there are compile problems, check the Python library versions - Crypto==1.4.1, Mako==1.1.2 SQLAlchemy==1.3.6, aiohttp==3.6.2
Eg.
pip install aiohttp
pip install aiohttp==3.6.2

python ./setup.py clean

python ./setup.py install

python ./setup.py build

python setup.py build_ext --inplace -j 8

python bin/hummingbot.py

