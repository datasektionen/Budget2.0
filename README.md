# Budget2.0


## Setup
* Install [pyenv](https://github.com/pyenv/pyenv) with `brew install pyenv`(mac) or [this installation script](https://github.com/pyenv/pyenv-installer)(linux)
* Add `eval "$(pyenv init -)"` to your `.bashrc`
* Install [pipenv](https://pipenv.readthedocs.io/en/latest/)
* Create a virual environment and install the dependencies by running `pipenv install --dev` in your project repo
[A nice text on why pipenv + pyenv is awesome](https://hackernoon.com/reaching-python-development-nirvana-bb5692adf30c)

## Tests
As this is a system supposed to handle economic information all endpoints should be well tested.

Tests are written in pytest-style, that is with fixtures.

Some useful packages that we probably will use:
* [factory\_boy](https://factoryboy.readthedocs.io/en/latest/) - Used for generating fake data to make requests towards.



