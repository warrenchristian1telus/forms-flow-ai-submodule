# forms-flow-ai-submodule

FormsFlow AI inside a submodule, to allow for fluid updates and separate custom code and configuration

This is a proof-of-concept to test better managing updates, security patches, custom code and deployment configs.

## Run local development environment in Docker

$ docker compose up -d ./aot-forms-flow-ai/forms-flow-bpm-db ./aot-forms-flow-ai/forms-flow-forms-db ./aot-forms-flow-ai/forms-flow-webapi-db
