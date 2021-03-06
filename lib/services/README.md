# Hydrogen <img src="https://cdn.rawgit.com/nteract/hydrogen/17eda245/static/animate-logo.svg" alt="hydrogen animated logo" height="50px" align="right" />

## Services API

The [Atom Services API](https://flight-manual.atom.io/behind-atom/sections/interacting-with-other-packages-via-services/) is a way for Atom packages to interact with each other. Hydrogen both provides and consumes *services* to add additional features to itself. `./lib/services` is our container folder for anything that functions through the [Atom Services API](https://flight-manual.atom.io/behind-atom/sections/interacting-with-other-packages-via-services/). If the service is considered a *provided service*, then it is located inside of `./lib/services/provided`. If the service, however, is considered a *consumed service*, then it is located inside of `./lib/services/consumed`.


## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/nteract/hydrogen/blob/master/LICENSE.md) file for details.
