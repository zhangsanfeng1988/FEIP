This library is FreeCash FEIP protocol
This library dependent freecrypto and freetx

freecrypto is distributed on PyPI and is available on Linux/macOS and Windows and supports Python 2.7/3.5+ and PyPy3.5-v5.8.1+

example:


$ pip3 install freecrypto

$ pip3 install freetx

If you are on a system that doesn't have a precompiled binary wheel (e.g. FreeBSD) then pip will fetch source to build yourself. You must have the necessary packages.

On Debian/Ubuntu the necessary system packages are:

    build-essential
    automake
    pkg-config
    libtool
    libffi-dev
    python3-dev (or python-dev for Python 2)
    libgmp-dev (optional)

On macOS the necessary Homebrew packages are:

    automake
    pkg-config
    libtool
    libffi
    gmp (optional)



example:

	url:port/get_all_tx
  
	url:port/get_base_by_utxo?utxo=d54cb03ede7fd27fbacca0595b9e9a31e06c2023afaa1be83e9c1078c7b4cd45

my example:
	http://47.115.137.45:6178/get_all_tx
	
	http://47.115.137.45:6178/get_base_by_utxo?utxo=d54cb03ede7fd27fbacca0595b9e9a31e06c2023afaa1be83e9c1078c7b4cd45
	



	
