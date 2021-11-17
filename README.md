## bkash-self-service-mw

This repository is for Self Service Middleware. It has two services `verifyservice` and `selfservice`. 
And all the shared modules reside in `libs` module.


### Getting Started

This project requires `python 3.9.6`. If you do not have this version installed, 
use `pyenv` to use this specific version for this project.


### Local Setup

Make sure you have `python 3.9.6` and `poetry` installed in you machine.

1. Clone this repo.
2. Install dependency with `poetry install`
3. Install pre commit hook with `poetry run pre-commit install`
4. Install commit message hook with `poetry run pre-commit install --hook-type commit-msg`
5. Start the project with `docker-compose up --build`

### Testing

To run test, use `pytest .` command.
