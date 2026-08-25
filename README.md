# India PIN Code Directory

> All 155000+ PIN codes with post office, district, state, and coordinates

**Category:** india-geo · **Data:** India Post open data · **License:** CC-BY-4.0 · **Updates:** monthly

## API Endpoints

All endpoints are served as static JSON from GitHub Pages.

| Endpoint | Format |
|----------|--------|
| `/data/pincodes.json` | JSON |
| `/data/pincodes/{pin}.json` | JSON |

## Usage

```bash
curl https://chirag127.github.io/india-pincode/data.json
```

```javascript
const res = await fetch('https://chirag127.github.io/india-pincode/data.json');
const data = await res.json();
```

## Data

- Source: India Post open data
- License: CC-BY-4.0
- Last updated: `2026-08-25T03:04:42.541Z`

See `data/` for raw JSON and `data/schema.json` for the schema.

## Documentation

Visit the [interactive docs](https://chirag127.github.io/india-pincode/) for the browsable API reference.

## Contributing

Issues and PRs welcome. Ensure `data/schema.json` validates all data files.

## License

CC-BY-4.0
