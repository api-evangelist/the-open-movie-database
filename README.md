# The Open Movie Database

The OMDb API is a RESTful web service to obtain movie, series, and episode information. All content and images on the site are contributed and maintained by users. Access movie and TV metadata including title, year, genre, director, cast, plot, ratings, and IMDb data. Search by title or look up by IMDb ID. Requires a free API key obtained at omdbapi.com/apikey.aspx.

**Website:** [omdbapi.com](https://www.omdbapi.com/)  
**Documentation:** [omdbapi.com](https://www.omdbapi.com/)  
**Sign Up:** [omdbapi.com/apikey.aspx](https://www.omdbapi.com/apikey.aspx)

---

## APIs

| API | Description | Base URL |
|-----|-------------|----------|
| [The Open Movie Database API](https://www.omdbapi.com/) | Movie, series, and episode metadata by IMDb ID or title | `https://www.omdbapi.com` |

---

## OpenAPI Specifications

| Spec | File |
|------|------|
| The Open Movie Database API | [openapi/the-open-movie-database-openapi.yml](openapi/the-open-movie-database-openapi.yml) |

**Endpoints:**
- `GET /` — Get movie or series by IMDb ID (`i`) or title (`t`)
- `GET /search` — Search movies and series by title keyword (`s`)

---

## Naftiko Capabilities

### Workflow Capabilities

| Workflow | File | Description |
|----------|------|-------------|
| Movie Lookup | [capabilities/movie-lookup.yaml](capabilities/movie-lookup.yaml) | Search and retrieve movie, series, and episode metadata |

### Shared Per-API Definitions

| API | File |
|-----|------|
| The Open Movie Database API | [capabilities/shared/the-open-movie-database.yaml](capabilities/shared/the-open-movie-database.yaml) |

---

## Spectral Rules

| Ruleset | File |
|---------|------|
| OMDb API Rules | [rules/the-open-movie-database-rules.yml](rules/the-open-movie-database-rules.yml) |

---

## JSON Schemas

| Schema | File |
|--------|------|
| Movie | [json-schema/the-open-movie-database-movie-schema.json](json-schema/the-open-movie-database-movie-schema.json) |

---

## JSON Structure

| Structure | File |
|-----------|------|
| Movie | [json-structure/the-open-movie-database-movie-structure.json](json-structure/the-open-movie-database-movie-structure.json) |

---

## JSON-LD

| Context | File |
|---------|------|
| OMDb Context | [json-ld/the-open-movie-database-context.jsonld](json-ld/the-open-movie-database-context.jsonld) |

---

## Examples

| Example | File |
|---------|------|
| Get Movie By IMDb ID | [examples/the-open-movie-database-get-movie-example.json](examples/the-open-movie-database-get-movie-example.json) |

---

## Vocabulary

| Vocabulary | File |
|------------|------|
| OMDb Vocabulary | [vocabulary/the-open-movie-database-vocabulary.yml](vocabulary/the-open-movie-database-vocabulary.yml) |

---

## Authentication

Pass your API key as a query parameter on every request:

```
?apikey=YOUR_API_KEY
```

Obtain a free key at [omdbapi.com/apikey.aspx](https://www.omdbapi.com/apikey.aspx).

---

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com

---

*Profile generated 2026-05-03*
