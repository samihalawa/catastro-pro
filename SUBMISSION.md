# Claude review — Catastro Pro 0.3.0

Publisher: Sami Halawa · Contact: sami@samihalawa.com

Repository: https://github.com/samihalawa/catastro-pro

Plugin at repository root. Stable identity: `catastro-pro`.

## Listing

Convierte una referencia catastral en una ficha con superficies, uso, construcción y coordenadas claramente identificadas.

Audience: Arquitectos y profesionales inmobiliarios que contrastan datos descriptivos.

First prompt: Consulta la referencia 2749704YJ0624N0001DI y separa superficie construida y de parcela.

## Reviewer walkthrough

Install with `/plugin install catastro-pro --marketplace samihalawa/catastro-pro`. Ask for an example: `demo` must be labelled as a saved snapshot, not live. The captured response is in `skills/catastro-pro/references/demo.json`. Run the live README example in an authorized Python 3.11+ environment, inspect scope and source dates, then export HTML. The report must not execute source text or load external assets.

Negative fixtures in `tests/test_core.py` are synthetic regressions, not live user tests. No credentials, product account, purchase or API key is required. This is a skills package, not a hosted MCP service.

## Included review materials

README, CHANGELOG, real icon, support/privacy/terms, static page source in docs/, saved official-source example, executable tests and versioned evidence. Dataset/service rights are separate from the MIT software licence.

## Scope

Solo datos no protegidos. No acredita propiedad, habitabilidad, valor o licencia urbanística. El punto no delimita una parcela. Navarra y País Vasco usan sistemas separados.

Read evidence for the actual completed checks. CI is an inactive template. Source publication, package validation, installation, user acceptance, directory review and adoption are separate states. No official listing or approval is claimed. Submit through https://claude.ai/directory/manage under the intended verified publisher identity; applicable publisher attestations remain with the owner.
