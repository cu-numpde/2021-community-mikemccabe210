# Community Software Analysis Proposal

## Software: *Optax*

Optax is an optimization library in the JAX ecosystem. Optax is intended to be a functional alternative to various other JAX-based optimization packages. Essentially, it uses gradient transformation functions that explicitly take in and output updated state objects. These transformations use the information stored in the state (momentum for SGD, history for LBFGS, ect) to alter/rescale/adjust the direction of gradients extracted from JAX. The primary audience for the package are JAX users who are predominantly deep learning practioners, but it is applicable to any other users of gradient-based optimization in JAX though it doesn't have the types of bells and whistles (line search, TR, convergence checks) you'd expect in a deterministic optimization package.

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL |   https://github.com/deepmind/optax/ |
| Main/documentation website | https://optax.readthedocs.io/en/latest/   |
| Year project was started | 2021, though it split out of an experimental part of JAX  |
| Number of contributors in the past year | 37|
| Number of contributors in the lifetime of the project | 37  |
| Number of distinct affiliations | 4 plus some personal emails|
| Where do development discussions take place? | Github issues  |
| Typical number of emails/comments per week? | 2  |
| Typical number of commits per week? | 1 |
| Typical commit size | ~60 insertions|
| How does the project accept contributions? | Pull requests  |
| Does the project have an automated test suite? | yes |
| Does the project use continuous integration? | yes |
| Are any legal/licensing steps required to contribute? | Yes |

The project doesn't require rights to your contribution, but does require contributors to sign a CLA.

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [X] I have installed the software
- [X] I have run at least one example
- [X] I have run the test suite
- [X] The test suite passes

### Notes/concerns/risks

I don't think it's necessarily topical, but I'm probably going to end up contributing to crikit (assuming there's something that needs doing over there). There are a few issues marked as good first issues that seem pretty reasonable. I'm also familiar with the library and there are a couple enhancements that don't look too complicated.

#### Note on copyright
CLA required, but no concerns.
