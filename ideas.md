Aug 13 goals

* [ ] discussion of [associative scan](https://jax.readthedocs.io/en/latest/_autosummary/jax.lax.associative_scan.html) operation on GPU
  * `jnp.arange`, `jnp.cumprod` can both be implemented with the associative scan, should be enough for expectation algorithms
  * Vasicek interest rates have [non-associative scan](https://jax.readthedocs.io/en/latest/_autosummary/jax.lax.scan.html) implementation.
  * Simulating time to death using timesteps is finding minimum index with value `1` where `1` is when a death occurs.
* [ ] Enhance infrastructure for [ESG.jl](https://github.com/JuliaActuary/EconomicScenarioGenerators.jl)'s listed performance tests. 
