# Readme Claim Check

Free composite Action. Fails CI when a README sells GitHub Marketplace, `pip install`, or a costume price without the files that would make the sentence true.

This is the mid-band leftover of Allowed Sales: origin first, files before slogans. Not a paid Marketplace App. Not $39/month. Not a sacrament.

## Use

```yaml
- uses: actions/checkout@v4
- uses: ironiclawdoctor-design/readme-claim-check@main
```

Pin a tag once you cut one. Default branch is a convenience, not a promise.

## What it flags

- "GitHub Marketplace" / "Marketplace ready" and no `action.yml`
- `pip install …` and no `pyproject.toml` or `setup.py`
- Warning only: `v9999999` or `$39/month` costume language

## Grassroots

Born from a repo that advertised Marketplace and `gh extension install` without an Action file. The crowd already has linters and security scanners. They do not usually fail the build for a README that outruns the tree.

## Small ask

If this saved you a false listing, [sponsor the account](https://github.com/sponsors/ironiclawdoctor-design) at the smallest tier, or buy the four-page sheet (`allowed_sales_fft.pdf`, $40) once a Stripe Payment Link is live. No link until that link exists.

## License

Use it. Cut claims. Ship files.
