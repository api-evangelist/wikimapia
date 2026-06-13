# Wikimapia

Wikimapia is a collaborative geographic wiki that layers crowdsourced place information onto satellite imagery. Launched in 2006, the platform covers over 32 million geographic objects contributed by its global community of users. The REST API provides programmatic access to places, categories, streets, and geographic searches.

## API

- **Base URL**: `https://api.wikimapia.org`
- **Documentation**: https://wikimapia.org/api/
- **Authentication**: API key (query parameter `key`)
- **Formats**: JSON, KML
- **Rate Limit**: 100 requests per 5 minutes per registered domain

## Key Endpoints

| Function | Description |
|---|---|
| `place.getbyid` | Retrieve full details for a place by ID |
| `place.search` | Full-text search for places |
| `place.getnearest` | Find places nearest to a coordinate |
| `place.getbyarea` | Get places within a bounding box |
| `place.getbytile` | Get places within a map tile |
| `category.getall` | List all place categories |
| `language.getall` | List supported languages |
| `street.getbyid` | Retrieve a street by ID |

## Resources

- [Website](https://wikimapia.org/)
- [API Documentation](https://wikimapia.org/api/)
- [GitHub Organization](https://github.com/Wikimapia)
- [Get API Key](https://wikimapia.org/api/?action=my_keys)

## Maintainer

Kin Lane — kin@apievangelist.com
