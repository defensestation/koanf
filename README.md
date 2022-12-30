## Koanf Providers
![koanf](https://user-images.githubusercontent.com/547147/72681838-6981dd00-3aed-11ea-8f5d-310816c70c08.png)

**koanf** (pronounced _conf_; a play on the Japanese _Koan_) is a library for reading configuration from different sources in different formats in Go applications. It is a cleaner, lighter [alternative to spf13/viper](#alternative-to-viper) with better abstractions and extensibility and fewer dependencies.

koanf comes with built in support for reading configuration from files, command line flags, and environment variables, and can parse JSON, YAML, TOML, and Hashicorp HCL. Any external dependencies are detatched from the core into sub-packages, so only the ones that are explicitly referenced get compiled into an application.

[![Run Tests](https://github.com/knadh/koanf/actions/workflows/test.yml/badge.svg)](https://github.com/knadh/koanf/actions/workflows/test.yml) [![GoDoc](https://godoc.org/github.com/knadh/koanf?status.svg)](https://godoc.org/github.com/knadh/koanf) 

### Project github
[Koanf Offical](https://github.com/knadh/koanf)

### Providers
- AWS Secrets Manager
- AWS Parameter Store

## Examples
- [Secrets Manager](https://github.com/defensestation/koanf/blob/main/examples/read-secretsmanager/main.go)
- [Parameter Store](https://github.com/defensestation/koanf/blob/main/examples/read-parameterstore/main.go)