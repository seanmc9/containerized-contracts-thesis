# The Containerized Contracts Thesis

## What
Smart contract infra and design is the way it is because we’ve been so turbo constrained by gas costs on mainnet to this point, not bc it’s necessarily the best way to do it. Just like when we went from designing things monolithically because we were on mainframes to microservice/Docker frameworks because the constraints changed, the same thing will happen with smart contracts with the advent of rollups.

“Containerized” refers to a contract that essentially follows the principles of [Docker](https://www.docker.com/resources/what-container/) and [containerization](https://aws.amazon.com/what-is/containerization/) and is designed for the paradigm that every instance of it will be deployed as a new contract (like how Docker containers are built from scratch every time/are emphemeral).

## Why
It yields a ton of really nice benefits, the main ones I’ve found so far are that development iteration can speed up a ton bc it doesn’t have to be one central/monolithic contract or set of contracts that everything is dependent on and that must be centrally managed, and then also with rollups it’s super nice bc to integrate with a new one you just have to add a new rpc config to wherever people are deploying the containerized contracts from and that's it!

## Examples
- [JokeRace](https://github.com/jk-labs-inc/jokerace)
- [Containerized Friendtech](https://github.com/seanmc9/containerized-friendtech)
- [Containerized Revnet](https://github.com/seanmc9/containerized-revnet)
