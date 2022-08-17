# Linux Foundation Energy Landscape

[![Netlify Status](https://api.netlify.com/api/v1/badges/57bcc258-c6d6-4b74-ada3-f829c842e847/deploy-status)](https://app.netlify.com/sites/lfenergy/deploys)

![Landscape Template Logo]

-   [Current Version]
-   [Interactive Version]
-   [New Entries]
-   [Corrections]
-   [Non-Updated Items]
-   [License]
-   [Formats]
-   [Installation]
-   [Vulnerability reporting]

<!-- Change to the description of your landscape -->
This landscape is intended as a map to explore the open source projects in the energy sector, and also shows the member companies of the LF Energy Foundation. 

It is modelled after the [Cloud Native Computing Foundation (CNCF) landscape] and based on the same open source code.

## Current Version

[![Landscape Template][PNG]][PNG]

## Interactive Version

Please see [landscape.lfenergy.org].

## New Entries

-   Projects must be open source and hosted on or mirrored to GitHub.
-   Projects with at least 300 GitHub stars that clearly fit in an existing category are generally included. Put the project in the single category where it best fits.
-   We are unlikely to create a new category for projects as we'd rather find the best home with the current options.
-   Your project or company needs a logo and the logo needs to include the name.
-   Crunchbase organization should be the company or organization that controls the software. That is normally the owner of the trademark, whether or not a trademark has been formally filed.
-   The logo must adhere to the [landscape logo guidelines]

If you think your project should be included, please open a pull request to add it to [landscape.yml]. For the logo, please upload an SVG to the `hosted_logos` directory.

Netlify will generate a staging server for you to preview your updates. Please check that the logo and information appear correctly and then add `LGTM` to the pull request confirming your review and requesting a merge.

## Corrections

Please open a pull request with edits to [landscape.yml]. The file [processed_landscape.yml] is generated and so should never be edited directly.

If the error is with data from [Crunchbase] you should open an account there and edit the data. If you don't like a project description, edit it in GitHub. If your project isn't showing the license correctly, you may need to paste the unmodified text of the license into a LICENSE file at the root of your project in GitHub, in order for GitHub to serve the license information correctly.

More about leveraged external data sources is at https://github.com/cncf/landscapeapp\#external-data.

## Non-Updated Items

We generally remove open source projects that have not had a commit in over 3 months. Note that for projects not hosted on GitHub, we need them to mirror to GitHub to fetch updates, and we try to work with projects when their mirrors are broken. Here is view of [projects sorted by last update].

Items that have been removed can apply to be re-added using the regular New Entries criteria above.

## License

This repository contains data received from [Crunchbase]. This data is not licensed pursuant to the Apache License. It is subject to Crunchbase's Data Access Terms, available at <https://data.crunchbase.com/v3.1/docs/terms>, and is only permitted to be used with this Landscape Project which is hosted by the Linux Foundation.

Everything else is under the Apache License, Version 2.0, except for project and product logos, which are generally copyrighted by the company that created them, and are simply cached here for reliability. The trail map, static landscape, serverless landscape, and [landscape.yml] file are alternatively available under the [Creative Commons Attribution 4.0 license].

## Formats

The Landscape Template is available in these formats:

- [PNG]
- [PDF]

## Installation

You can install and run locally with the [install directions]. It's not necessary to install locally if you just want to edit [landscape.yml]. You can do so via the GitHub web interface.

## Vulnerability reporting

Please open an [issue] or, for sensitive information, email info\@cncf.io.

<!--- Update urls and references in this section -->
[Dependency Status]: https://img.shields.io/david/jmertic/landscape-template.svg?style=flat-square
[1]: https://david-dm.org/jmertic/landscape-template``
[Netlify Status]: https://api.netlify.com/api/v1/badges/9fe8d885-037d-48ce-8bf9-3bfa54152945/deploy-status
[2]: https://app.netlify.com/sites/graphql-landscape/deploys
[landscape.lfenergy.org]: https://landscape.lfenergy.org
[PDF]: https://landscape.lfenergy.org/images/landscape.pdf
[PNG]: https://landscape.lfenergy.org/images/landscape.png
[issue]: https://github.com/jmertic/landscape-template/issues/new
[projects sorted by last update]: https://landscape.lfenergy.org/format=card-mode&grouping=no&license=open-source&sort=latest-commit
<!--- These shouldn't need updated -->
[Landscape Template Logo]: images/left-logo.svg
[Current Version]: #current-version
[Interactive Version]: #interactive-version
[New Entries]: #new-entries
[Corrections]: #corrections
[Non-Updated Items]: #non-updated-items
[License]: #license
[Formats]: #formats
[Installation]: #installation
[Vulnerability reporting]: #vulnerability-reporting
[Cloud Native Computing Foundation (CNCF) landscape]: https://landscape.cncf.io
[landscape logo guidelines]: https://github.com/cncf/landscapeapp#images
[landscape.yml]: landscape.yml
[processed_landscape.yml]: processed_landscape.yml
[Crunchbase]: https://www.crunchbase.com/
[Creative Commons Attribution 4.0 license]: https://creativecommons.org/licenses/by/4.0/
[install directions]: INSTALL.md

 

