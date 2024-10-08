[![Netlify Status]][2]

<!-- Change to the name of your landscape -->
# Landscape Template

![Landscape Template Logo]

-   [Current Version]
-   [Interactive Version]
-   [Adding New Items]
-   [Corrections]
-   [Stale Entries]
-   [License]
-   [Formats]
-   [Installation]
-   [Vulnerability reporting]

<!-- Change to the description of your landscape -->
This landscape maps the Tazama Project's Ecosystem. 
It is modelled after the [Cloud Native Computing Foundation (CNCF) landscape] and based on the same open source code.

## Current Version

[![Landscape Template][PNG]][PNG]

## Interactive Version

Please see [landscape view].

## Adding New Items

-   The addidion of a Project entry will be at the discretion of the Tazama TSC. Project's must be open source and hosted on or mirrored to GitHub.
-   Your project or company needs a logo and the logo needs to include the name.
-   Crunchbase organization should be the company or organization that is the owner of the trademark, whether or not a trademark has been formally filed.
-   The logo must adhere to the [landscape logo guidelines]

If you think your company should be included, please open a pull request to add it to [landscape.yml]. For the logo, please upload an SVG to the `hosted_logos` directory.

Netlify will generate a staging server for you to preview your updates. Please check that the logo and information appear correctly and then add `LGTM` to the pull request confirming your review and requesting a merge.

## Corrections

Please open a pull request with edits to [landscape.yml]. The file [processed_landscape.yml] is generated and so should never be edited directly.

If the error is with data from [Crunchbase] you should open an account there and edit the data. If you don't like a project description, edit it in GitHub. If your project isn't showing the license correctly, you may need to paste the unmodified text of the license into a LICENSE file at the root of your project in GitHub, in order for GitHub to serve the license information correctly.

More about leveraged external data sources is at https://github.com/cncf/landscapeapp\#external-data.

## Stale Entries

We generally remove Participating Companies that have not had a commit in over 3 months. Note that for projects not hosted on GitHub, we need them to mirror to GitHub to fetch updates, and we try to work with projects when their mirrors are broken. Here is view of [projects sorted by last update].

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
[Netlify Status]: https://api.netlify.com/api/v1/badges/9fe8d885-037d-48ce-8bf9-3bfa54152945/deploy-status
[2]: https://app.netlify.com/sites/ospolandscape-landscape/deploys
[landscape view]: https://ospolandscape.todogroup.org
[PDF]: https://landscape.tazama.org/images/landscape.pdf
[PNG]: https://landscape.tazama.org/images/landscape.png
[issue]: https://github.com/jmertic/landscape-template/issues/new
[projects sorted by last update]: https://landscape.tazama.org/format=card-mode&grouping=no&license=open-source&sort=latest-commit
<!--- These shouldn't need updated -->
[Landscape Template Logo]: images/left-logo.svg
[Current Version]: #current-version
[Interactive Version]: #interactive-version
[Adding New Items]: #adding-new-items
[Corrections]: #corrections
[Stale Entries]: #stale-entries
[License]: #license
[Formats]: #formats
[Installation]: #installation
[Vulnerability reporting]: #vulnerability-reporting
[Cloud Native Computing Foundation (CNCF) landscape]: https://landscape.cncf.io
[landscape logo guidelines]: https://github.com/cncf/landscapeapp/blob/master/README.md#logos
[landscape.yml]: landscape.yml
[processed_landscape.yml]: processed_landscape.yml
[Crunchbase]: https://www.crunchbase.com/
[Creative Commons Attribution 4.0 license]: https://creativecommons.org/licenses/by/4.0/
[install directions]: INSTALL.md
