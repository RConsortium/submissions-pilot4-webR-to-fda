# R Submissions Pilot 4 ECTD Package

2024-09-19T19:10:29+00:00

> Do not include `README.md` and `.gitignore` files into the final
> submission.

## Overview

The objective of the R Consortium R submission Pilot 4 Project is to
test the concept that a Shiny application created with the R-language
can be bundled with novel technologies and transferred successfully to
FDA reviewers. The application was built as a modified version of the
application contained R submission Pilot 2 Project, with materials
available on the
[RConsortium/submissions-pilot2](https://github.com/RConsortium/submissions-pilot2)
repository, All submission materials and communications from this pilot
are publicly available, with the aim of providing a working example for
future R language based FDA submissions. This is a FDA-industry
collaboration through the non-profit organization R consortium.

To learn more about other pilots, visit [the R consortium R submission
working group website](https://rconsortium.github.io/submissions-wg/)
and the [R consortium working group
page](https://www.r-consortium.org/projects/isc-working-groups).

## Instructions for Electronic Gateway Transfer

Due to a limitation on file size imposed by GitHub, this repostitory
does not include the pilot 4 pre-compiled application file `r4app.zip`.
Please use the following procedure to prepare the local clone of this
repository for the electronic gateway transfer:

1.  Clone this repository to your local machine or download the ZIP
    archive of the repostory using
    <https://github.com/RConsortium/submissions-pilot4-webR-to-fda/archive/refs/heads/main.zip>
    and extract to your local machine.
2.  Create a new directory called `programs` in the
    `m5/datasets/rconsortiumpilot4/analysis/adam/` directory.
3.  Download the `r4app.zip` archive from [this
    link](https://rsubmission-draft.us-east-1.linodeobjects.com/r4app.zip)
    and save it to the
    `m5/datasets/rconsortiumpilot4/analysis/adam/programs/` directory.

## FDA Response

- Initial submission

TBD

## Run Shiny Application

To run the Pilot 4 Shiny application using web-assembly, you can follow
the steps described in the [ADRG
document](https://rsubmission-draft.us-east-1.linodeobjects.com/adrg-quarto-pdf.pdf).
A web (HTML) version of the ADRG is also available at
<https://rpodcast.quarto.pub/pilot4-webassembly-adrg/>.

## Folder Structure

The folder is organized as a demo eCTD package following ICH guidance.

eCTD package:

- `m1/`: module 1 of the eCTD package

<!-- -->

    m1
    └── us
        ├── cover-letter.pdf  # Submission cover letter

- `m5/`: module 5 of the eCTD package

<!-- -->

    m5
    └── datasets
        └── rconsortiumpilot4webR
            └── analysis
                └── adam
                    ├── datasets              # ADaM datasets in XPT format
                    │   ├── adadas.xpt
                    │   ├── adlbc.xpt
                    │   ├── adrg.pdf          # Analysis Data Reviewer's Guide
                    │   ├── adsl.xpt
                    │   ├── adtte.xpt
                    │   ├── define.xml        # ADaM data define file
                    │   └── define2-0-0.xsl
                    └── programs
                        ├── r4app.zip         # Pre-compiled application in zip archive

Other files: (**Do not include in eCTD package**)

- `.gitignore`: git ignore file
- `README.md`: readme file for github repo

## News

The ECTD bundle and associated compiled application archive were last
rendered on 2024-09-19T19:10:29+00:00 .

## Questions

Report issues in
<https://github.com/RConsortium/submissions-pilot4-to-fda/issues>
