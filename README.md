<!-- Replace placeholders. APPLICATION_URL should point to the app's website, or its repository if no site exists. -->
<!--
Setting up a new port from this template:
1. Replace every {{PLACEHOLDER}} in README.md, CONTRIBUTING.md, LICENSE,
   cog.toml, and install.sh. In install.sh, items() prints each file or folder a
   variant installs and the folder it goes in. Delete install.sh and uninstall.sh
   when a plugin manager installs the port instead.
2. Ports based on another project keep that project's license notice in LICENSE
   next to their own, and credit it in the header below.
3. You do not need to tag or protect the repository. Organization maintainers
   add the branch rules, the description, and the topics when the port is
   adopted, and they make releases.
4. Replace the placeholder images in assets/ (see Previews below).
5. Delete this comment.
-->
<img align="left" src="https://raw.githubusercontent.com/kanagawa-community/.github/main/assets/branding/logo.png" alt="Kanagawa logo" width="200">

<h3>Kanagawa for <a href="{{APPLICATION_URL}}">{{APPLICATION}}</a></h3>
<p>A community-maintained theme inspired by Hokusai's <em>The Great Wave off Kanagawa</em>.</p>
<p>Using the <a href="https://github.com/rebelot/kanagawa.nvim">Kanagawa palette</a> by <a href="https://github.com/rebelot">Tommaso Laurenzi (rebelot)</a>.</p>

<!-- Replace source placeholders; if source is not on GitHub, use its absolute URL. -->
<!-- Optional: credit a specific implementation, palette, or other source when applicable. -->
<!-- Example: Based on [source name](https://absolute-source-url). -->
<!--
<p>Based on <a href="{{SOURCE_URL}}">{{SOURCE_NAME}}</a> by <a href="{{AUTHOR_URL}}">{{AUTHOR_NAME}}</a>.</p>
-->

<!-- Wave accents: carpYellow, crystalBlue, autumnRed. Lotus accents: lotusYellow, lotusBlue4, lotusRed. -->
<p>
  <a href="https://github.com/kanagawa-community/{{REPOSITORY}}/stargazers">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/github/stars/kanagawa-community/{{REPOSITORY}}?style=for-the-badge&amp;labelColor=1F1F28&amp;color=E6C384">
      <source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/github/stars/kanagawa-community/{{REPOSITORY}}?style=for-the-badge&amp;labelColor=F2ECBC&amp;color=77713F">
      <img src="https://img.shields.io/github/stars/kanagawa-community/{{REPOSITORY}}?style=for-the-badge&amp;labelColor=1F1F28&amp;color=E6C384" alt="GitHub stars">
    </picture>
  </a>
  <a href="https://github.com/kanagawa-community/{{REPOSITORY}}/releases/latest">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/github/v/release/kanagawa-community/{{REPOSITORY}}?style=for-the-badge&amp;label=release&amp;labelColor=1F1F28&amp;color=7E9CD8">
      <source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/github/v/release/kanagawa-community/{{REPOSITORY}}?style=for-the-badge&amp;label=release&amp;labelColor=F2ECBC&amp;color=4D699B">
      <img src="https://img.shields.io/github/v/release/kanagawa-community/{{REPOSITORY}}?style=for-the-badge&amp;label=release&amp;labelColor=1F1F28&amp;color=7E9CD8" alt="Latest release">
    </picture>
  </a>
  <a href="https://github.com/kanagawa-community/{{REPOSITORY}}/issues">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/github/issues/kanagawa-community/{{REPOSITORY}}?style=for-the-badge&amp;labelColor=1F1F28&amp;color=C34043">
      <source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/github/issues/kanagawa-community/{{REPOSITORY}}?style=for-the-badge&amp;labelColor=F2ECBC&amp;color=C84053">
      <img src="https://img.shields.io/github/issues/kanagawa-community/{{REPOSITORY}}?style=for-the-badge&amp;labelColor=1F1F28&amp;color=C34043" alt="Open issues">
    </picture>
  </a>
</p>

<br clear="both">
<br>

## Previews

<!-- Every port must support and preview all three variants. Keep screenshots in this port repository, and use comparable application content in each. The images in assets/ are placeholders: replace all four. -->
<!-- Terminal-based ports render the three variant images instead of taking them: see https://github.com/kanagawa-community/.github/blob/main/docs/PREVIEWS.md -->
<!-- showcase.png stacks the three variant images. Build it and the social preview with scripts/finish-previews.sh from https://github.com/kanagawa-community/.github (terminal ports: scripts/render-previews.sh with a scripts/preview.sh hook; ports with a real window: scripts/capture-windows.sh with a scripts/window.sh hook), and keep the variant images in assets/screenshots/. -->

![Windows showing {{APPLICATION}} with Kanagawa Lotus, Dragon, and Wave](assets/showcase.png)

<details>
<summary>🌊 Wave</summary>
<img src="assets/screenshots/wave.png" alt="Screenshot of {{APPLICATION}} using Kanagawa Wave">
</details>

<details>
<summary>🐉 Dragon</summary>
<img src="assets/screenshots/dragon.png" alt="Screenshot of {{APPLICATION}} using Kanagawa Dragon">
</details>

<details>
<summary>🪷 Lotus</summary>
<img src="assets/screenshots/lotus.png" alt="Screenshot of {{APPLICATION}} using Kanagawa Lotus">
</details>

## Requirements

- {{APPLICATION}} {{MINIMUM_VERSION}}
- {{OTHER_REQUIREMENT}}

## Installation

{{INSTALLATION_INSTRUCTIONS}}

`./install.sh` installs all three variants. Name the ones you want instead, for
example `./install.sh dragon lotus`. Run it again after `git pull` to update.
`./uninstall.sh` takes the same names and removes them.

## Usage

{{QUICK_START_EXAMPLE}}

<!-- Optional sections: keep only those useful for this port. -->

<!--
## Configuration

{{CONFIGURATION_DETAILS}}
-->

<!--
## API

{{PUBLIC_API_DETAILS}}
-->

<!--
## Integrations

{{INTEGRATION_DETAILS}}
-->

<!--
## Palette

{{PALETTE_DETAILS}}
Link the shared palette and list only the colors this port maps in its own way.
Do not copy the palette tables.
-->

<!--
## Accessibility

{{ACCESSIBILITY_DETAILS}}
Describe tested foreground/background pairs and known limitations. Avoid blanket
WCAG claims unless verified.
-->

## Issues and contributions

Report bugs and request changes in this port's
[issue tracker](ISSUES_URL). Contributions are welcome.

See [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## License

{{LICENSE_TYPE}}. See [LICENSE](LICENSE).
