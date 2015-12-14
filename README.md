# JPMorgan
A Simple Stock Example for testing purposes.

As a starting point we have two major classes, Stock and GBCEShareIndex.
I decided to make Stock an abstract class, because we have two different implementations of the method that calculates the dividend yield.
I decided to not use an interface, because all the type Stock methods are common (except the aforementioned). We also have the Trade class, which could be an inner class of Stock, but decided against it, as it's more clear to be in a separate file.

All methods are implemented according to the specifications.
