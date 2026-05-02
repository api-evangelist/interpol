# Interpol (interpol)

INTERPOL (International Criminal Police Organization) is an inter-governmental
organization with 196 member countries that helps police worldwide work
together to make the world a safer place. INTERPOL exposes a public Notices
web service that returns Red, Yellow, and UN Notices data. An OpenAPI
description of that service is published by the bundesAPI community and
mirrored in this repository.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/interpol/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- International
- Law Enforcement
- Notices
- Police

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-04-28

## APIs

### Interpol Notices API

The INTERPOL Notices API provides public, unauthenticated access to Red,
Yellow, and UN Notices, including notice metadata and associated images.
The API is queryable by name, nationality, age range, sex, and issuing
country.

**Human URL:** [https://interpol.api.bund.dev](https://interpol.api.bund.dev)

**Base URL:** https://ws-public.interpol.int/notices/v1/

#### Endpoints

- `GET /red` and `GET /red/{noticeID}` and `GET /red/{noticeID}/images`
- `GET /yellow` and `GET /yellow/{noticeID}` and `GET /yellow/{noticeID}/images`
- `GET /un` and `GET /un/{noticeType}/{noticeID}` and `GET /un/{noticeType}/{noticeID}/images`

#### Properties

- [Documentation](https://interpol.api.bund.dev)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/interpol/refs/heads/main/openapi/interpol-openapi.yml)

## Common Properties

- [Website](https://www.interpol.int/)
- [Source (bundesAPI)](https://github.com/bundesAPI/interpol-api)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
