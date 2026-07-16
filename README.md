# Fresh Commerce Inventory API

Production-shaped demo service for the Erik James V12 Postman API Catalog.

## Endpoints

- `GET /health`
- `GET /products`
- `POST /products`
- `GET /products/{sku}`
- `PATCH /products/{sku}`
- `DELETE /products/{sku}`

## Run locally

```sh
npm start
```

The API listens on `http://localhost:3000`. Its OpenAPI 3.0 contract is [`index.yaml`](index.yaml).

## Catalog automation

The PEAS onboarding workflow generates a Postman workspace, baseline, smoke, and contract collections, a mock, disabled-by-default monitor, Production and Staging environments, Git linkage, CI, and API Catalog placement.
