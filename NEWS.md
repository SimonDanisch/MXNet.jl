$ v0.0.6 (2015.12.02)

* Variants of Xaiver initializers (@vchuravy)
* More arithmetic operators on symbolic nodes
* Basic interface for symbolic node attributes (@vchuravy)

# v0.0.5 (2015.11.14)

* char-lstm example.
* Network visualization via GraphViz.
* NN-factory for common models.
* Convenient `@nd_as_jl` macro to work with `NDArray` as Julia Arrays.
* Refactoring: `Symbol` -> `SymbolicNode`.
* More evaluation metrics (@vchuravy, @Andy-P)

# v0.0.4 (2015.11.09)

* ADAM optimizer (@cbecker)
* Improved data provider API.
* More documentation.
* Fix a bug in array data iterator (@vchuravy)

# v0.0.3 (2015.10.27)

* Model prediction API.
* Model checkpoint loading and saving.
* IJulia Notebook example of using pre-trained imagenet model as classifier.
* Symbol saving and loading.
* NDArray saving and loading.
* Optimizer gradient clipping.
* Model training callback APIs, default checkpoint and speedometer callbacks.
* Julia Array / NDArray data iterator.
* Sphinx documentation system and documents for dynamically imported libmxnet APIs.

# v0.0.2 (2015.10.23)

* Fix a bug in build script that causes Julia REPL to exit.

# v0.0.1 (2015.10.23)

Initial release.

* Basic libmxnet API.
* Basic documentation, overview and MNIST tutorial.
* Working MNIST and cifar-10 examples, with multi-GPU training.
* Automatic building of libmxnet with BinDeps.jl.

