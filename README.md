# PoC for mobilityDCAT-AP Governance

This repo is contribution to how to present Governance document with mobilityDCAT-AP repositories.

This is by no means an official document for mobilityDCAT-AP, for that, refer to https://github.com/mobilityDCAT-AP/mobilityDCAT-AP/tree/gh-pages/Governance%20and%20maintenance%20concept

For more see https://github.com/mobilityDCAT-AP/mobilityDCAT-AP/issues/111

## Usage
### Using GitHub UI
This should work for GitHub wiki too:

Go to GitHub repository, go to `src` and open `SUMMARY.md`. See that the links are working well.


### Using single markdown page

Open `one-long-page.md` in the root.

Personally I would reformat it a bit but you see the concept.

### Building mdbook based site

Install `mdbook`

Within this repository:

```shell
mdbook serve
```

and open <http://localhost:3000>
