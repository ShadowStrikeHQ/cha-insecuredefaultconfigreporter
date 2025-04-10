# cha-InsecureDefaultConfigReporter
Identifies configuration files using insecure default settings, highlighting potential vulnerabilities related to default passwords, open ports, and permissive access controls. - Focused on Analyzes system or application configurations against predefined security benchmarks (e.g., CIS benchmarks). Uses pyyaml to parse configuration files and jsonschema to validate them against defined schemas, highlighting deviations from security best practices.

## Install
`git clone https://github.com/ShadowStrikeHQ/cha-insecuredefaultconfigreporter`

## Usage
`./cha-insecuredefaultconfigreporter [params]`

## Parameters
- `-h`: Show help message and exit
- `-s`: Path to the JSON schema file for validation.
- `-t`: No description provided
- `-l`: No description provided

## License
Copyright (c) ShadowStrikeHQ
