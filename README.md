genhost
=======

This script will randomly generate hostnames by picking words from the
provided word list. The pool of words comes from Oren Tirosh's
[mnemonic encoding](http://web.archive.org/web/20090918202746/http://tothink.com/mnemonic/wordlist.html)
project.

This project is forked from [elasticdog's genhost](https://github.com/elasticdog/genhost). Changes are:

* do not keep track of used words
* generates a three-words hostname
* domain is optional (second argument)

Usage
-----

Just run the script and provide the number of hostnames you'd like to
generate:

    $ ./genhost 4
    dublin-chaos-bambino
    cloud-suzuki-podium
    conan-mailbox-uncle
    desert-scuba-gabriel

And with a domain:

    $ ./genhost 4 github.io
    clarion-screen-money.github.io
    python-bali-equator.github.io
    stock-opus-master.github.io
    second-tourist-anatomy.github.io

