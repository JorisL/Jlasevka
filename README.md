# Jlasevka
Custom Iosevka font config, made with aid of [Iosevka customizer](https://typeof.net/Iosevka/customizer).
Font choices were inspired by Pragmata Pro, Berkeley Mono, and IBM Plex.

## How to build

1. Follow the instructions from [https://github.com/be5invis/Iosevka/blob/main/doc/custom-build.md].
2. Copy `private-build-plans.toml` from this repository into the Iosevka repository.
3. Run the following shell commands in the Iosevka repository:
  - `npm run build -- contents::JlasevkaMono`
  - `npm run build -- contents::JlasevkaTerm`
  - `npm run build -- contents::JlasevkaDoc`
