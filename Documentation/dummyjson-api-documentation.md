# API Testing Documentation – DummyJSON

Diese Collection enthält API-Tests gegen die DummyJSON Test-API.

## GET /products
- Erwartung: Statuscode 200
- Validierung: products[] enthält Objekte
- Ergebnis: PASS

## GET /products/1
- Erwartung: Statuscode 200
- Validierung: id = 1
- Ergebnis: PASS

## POST /products/add
- Erwartung: Statuscode 200 oder 201
- Validierung: title wird korrekt zurückgegeben
- Ergebnis: PASS
- Hinweis: DummyJSON speichert das Produkt nicht persistent (Demo API).

## PUT /products/1
- Erwartung: Statuscode 200
- Validierung: Title = "Updated Test Produkt"
- Ergebnis: PASS

## DELETE /products/1
- Erwartung: Statuscode 200 oder 204
- Ergebnis: PASS
