# Apex & SOQL Studies

A small Salesforce DX learning repository with introductory Apex and SOQL examples.

## What's inside

| File | Purpose |
| --- | --- |
| [`hello.apex`](APEX-Exercicios/myfirstproject/scripts/apex/hello.apex) | A string variable and debug output in anonymous Apex |
| [`account.soql`](APEX-Exercicios/myfirstproject/scripts/soql/account.soql) | A query selecting `Id` and `Name` from `Account` |
| [`live.cls`](APEX-Exercicios/myfirstproject/force-app/main/default/classes/live.cls) | An initial Apex class with an empty constructor |

## Project layout

The Salesforce DX project that contains the `force-app` source directory is:

```text
APEX-Exercicios/myfirstproject/
├── force-app/main/default/classes/
├── scripts/apex/
├── scripts/soql/
└── sfdx-project.json
```

Open this directory in VS Code when working with the source project. Its configuration uses Salesforce API version 64.0.

The outer `APEX-Exercicios/` directory also contains starter configuration files and copies of the sample scripts from the initial setup.

## Explore the examples

1. Install the Salesforce CLI and Salesforce Extensions for VS Code.
2. Connect a Salesforce development organization.
3. Open `scripts/apex/hello.apex` and run it as anonymous Apex.
4. Open `scripts/soql/account.soql` and run the query against your connected organization.

## Tools

Salesforce DX · Apex · SOQL · VS Code

## Next learning goals

- Classes and methods.
- Collections.
- SOQL filters.
- Apex unit tests.

## Documentation

- [Salesforce Extensions for VS Code](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI](https://developer.salesforce.com/tools/salesforcecli)
