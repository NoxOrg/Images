# Nox Images

This is a central repository for images used by:
- noxorg.dev website markdown files
- Nox Github repository project README
- Nox.Cli Github repository project README

The primary motivator was a single source of truth as well as a common image library that could be accessed by all sources listed above with consistent URIs.

Images are stored in the `/assets` subfolder.

Upon merging to the `main` branch, the images are automatically uploaded to the webserver where [noxorg.dev]() is hosted via the `.github/workflows/cd.yaml` Github action using [Sam Kirkland's](https://github.com/SamKirkland) [FTP-Deploy-Action](https://github.com/SamKirkland/FTP-Deploy-Action)