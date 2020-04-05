[<img src="https://raw.githubusercontent.com/ForgeRock/forgerock-logo-dev/master/Logo-fr-dev.png" align="right" width="220px"/>](https://developer.forgerock.com/)

| |Current Status|
|---|---|
|Build|[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2FOpenBankingToolkit%2Fcdr-standards-bom%2Fbadge%3Fref%3Dmaster&style=flat)](https://actions-badge.atrox.dev/OpenBankingToolkit/cdr-standards-bom/goto?ref=master)|
|Tag |[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/openbankingtoolkit/cdr-standards-bom)](https://github.com/OpenBankingToolKit/cdr-standards-bom/tags)|
|Release|[![GitHub release](https://img.shields.io/github/v/release/OpenBankingToolKit/cdr-standards-bom?sort=semver)](https://github.com/OpenBankingToolKit/cdr-standards-bom/releases)|
|Code coverage|[![codecov](https://codecov.io/gh/OpenBankingToolkit/cdr-standards-bom/branch/master/graph/badge.svg)](https://codecov.io/gh/OpenBankingToolkit/cdr-standards-bom)|
|License|![license](https://img.shields.io/github/license/ACRA/acra.svg)|

Consumer Data Right (CDR) Standards Bill of Materials (BOM) maven pom
=====================================================================

Maven pom descriptor BOM of all maven CDR components.

Basically, the BOM allows add as many CDR dependencies as need without worrying about mixing bad versions.

Consumer Data Right Standards: https://consumerdatastandardsaustralia.github.io/standards.

## Artifact
cdr-bom

## Usage
```
<dependencies>
  <dependency>
      <groupId>com.forgerock.cdr.standards</groupId>
      <artifactId>cdr-standards-bom</artifactId>
      <version>${cdr-standards-bom.version}</version>
      <type>pom</type>
      <scope>import</scope>
  </dependency>
  ...
</dependencies>
```

