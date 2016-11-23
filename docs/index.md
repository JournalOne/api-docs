# Journal One API

## Getting Started

Die API befindet sich unter https://api.getjournal.one. Kommunikation erfolgt ausschließlich per JSON, sowohl in POST/PUT Requests, als auch in den Responses.

In der folgenden Dokumentation wird deine einfachere, nicht valide JavaScript Notation verwendet und dient lediglich zur Veranschaulichung. Die API selbst verwendet ausschließlich JSON.


## Authentifizierung

Authentifizierung erfolgt per Query-Parameter `apikey`.

**Beispiel**

    https://api.getjournal.one/website/list?apikey=insert_valid_api_key


## Endpunkte

* [/website](endpoints/website.md)


## Schema

* [website](schema/website.md)
