# Bharat Address Pilots

Ready-to-fork pilot templates for cities and wards.

## What is here
- `city-template/`: baseline structure for a new city pilot.
- `sample-ward/`: example ward dataset and metadata.

## Quickstart
```bash
# copy the template to a new city pilot folder
cp -R city-template <city-slug>
```
Then edit the copied files to match the target city and data.

## Usage notes
- Use `sample-ward/` as a reference for structure and naming.
- Keep data aligned with the schema in `BharatAddress/specs`.
- Validate datasets with `BharatAddress/tools-validator` before sharing.

## Suggested workflow
1. Create a new pilot folder using `city-template/`.
2. Populate wards and metadata.
3. Run schema validation and QC checks.
4. Share findings through the docs site or issues.

## Who should use this
- ULB teams piloting Bharat Address.
- Contributors preparing sample datasets.

## Links
- Specs: https://github.com/BharatAddress/specs
- Docs: https://bharataddress.github.io

## License
See `LICENSE`.

## Contributing
- Central guidelines: https://github.com/BharatAddress/.github/blob/main/AGENTS.md
