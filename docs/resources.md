# External resources and fallback plan

RideRent Challenge 1 intentionally does **not** depend on a third-party API. The document says that if no external API is used, the project must justify this and document the libraries/services used.

| Resource | Type | URL | Licence | Key? | RF |
|---|---|---|---|---|---|
| React | Library | https://react.dev/ | MIT | No | RNF-06 |
| React Router | Library | https://reactrouter.com/ | MIT | No | RNF-05/RNF-06 |
| Lucide React | Library | https://lucide.dev/ | ISC | No | RNF-06 |
| Vite | Build tool | https://vite.dev/ | MIT | No | RNF-01/RNF-06 |

Fallback: local seed data and localStorage keep the prototype usable if no API/backend is available. Production should replace this with a server database and secure authentication.
