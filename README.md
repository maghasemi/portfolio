# portfolio

Source of the personal site for M. Amin Ghasemi, served at https://aminghasemi.de.

Each portfolio lives in its own folder and is one self-contained `index.html` with no build step.

| Path | Contents |
| --- | --- |
| `postdoc/` | Postdoc page and its CV (`Amin_Ghasemi_CV_Academic.pdf`). |
| `assets/` | Images shared by all pages. |
| `figures/metMatchAudit/` | The two metMatchAudit README figures recolored to the site palette, ready to copy into that repository's `man/figures/`. |
| `index.html` | Redirects the bare domain to `postdoc/` until a general page exists. |
| `CNAME` | Custom domain for GitHub Pages. |

To add a portfolio, create a new folder (for example `bioinformatics/`) with its own `index.html` and CV PDF, and reference shared images as `../assets/...`.

Open any `index.html` in a browser to preview it.
