# Katamari Company

_A summary of the running loss of local restaurants to deep-pocketed private 
equity and national chains._

## Technics

Site is built with [Jekyll](http://jekyllrb.com) and served with GitHub Pages.

## Requirements

- Ruby 2.5.3
- Bundler

## Development

After checking out the repo, run `git config core.hooksPath .githooks` to enable
automatic markdown formatting. Alternatively run `yarn format` to manually
format the Markdown files.

To run in development locally:

```bash
yarn && bundle install
yarn serve
```

Run `yarn format` to manually format the Markdown files.

## Contributing

Add an entry to `_data/companies.yml`, make sure you fill out the following
fields:

```yml
example:
  name: "Example, Inc." # Company failed/bought/sold/acquired
  date: 2019-11-26 00:00:00 # Date of sale
  buyer: "Shell Corporation, Inc." # Name of new owning company
  url: https://example.com # URL to press release/more info
  notes: "Some notes" # Relevant notes (keep it less than 512 chars)
```

Test it locally, then open a PR.

## License

[MIT](LICENSE)
