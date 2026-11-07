# LedgerFlow

[![CI](https://github.com/koustav516/ledgerflow/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/koustav516/ledgerflow/actions/workflows/ci.yml)

LedgerFlow is a ledger service built with Spring Boot 4.1 and Java 21. It records financial transactions as double-entry journal entries, keeps account balances consistent, and exposes them through a REST API. The project is developed trunk-based: every change lands on a protected `master` branch through a pull request that has to pass CI (`mvn verify`).

## Running locally

```bash
./mvnw verify          # build and run tests
./mvnw spring-boot:run # start the service
```
