# Will Fantom: **CV**    ![GitHub release (latest SemVer)](https://img.shields.io/github/v/tag/willfantom/cv?display_name=tag&label=%20&sort=semver)  ![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/willfantom/cv/release.yml?label=%20&logo=github)

Looking for somebody who knows computer networks and go/python? Hey 👋


➡ **Download my CV:** [here](https://github.com/willfantom/cv/releases/latest/download/cv.pdf) ⬅

---

## Template

This CV takes the awesome theme *Developer CV* from [latex
templates](https://www.latextemplates.com/template/developer-cv) and makes some
alterations to layout and information categories. Mainly, the changes shift the
focus from being purely a developer CV to more of a dev/researcher CV and
increases information density slightly. This includes adding:

  - *tools*: where named tools are added into tag boxes, showing what tools are
    well-known/used frequently by the subject
  - *publications*: to list paper publications, with enough room to mention the
    paper name, venue, year, and if the subject is the first author
  - *project*: a space to discuss a recent project that the subject is
    particularly proud of

And a space for a profile photo was added along with a QR code that can link to
the CV download page in order to ensure the viewer can obtain the latest copy.

Also in this repository is a DevContainer that uses my [latex
devcontainer](https://github.com/WillFantom/devcontainer-latex) image to make it
easy to start editing with only Docker+VSCode installed (or in Codespaces)! Finally,
there is also a GitHub Actions workflow that will build the CV when a semver
compliant tag is pushed, releasing with the same name as the tag, and adding
the CV PDF asset to the release.
