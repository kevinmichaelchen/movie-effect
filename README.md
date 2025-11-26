# moviedb-effect

A modern, type-safe TypeScript client for [The Movie Database (TMDb) API][tmdb], built with [Effect].

## Packages

| Package                    | Description                                                                      |
| -------------------------- | -------------------------------------------------------------------------------- |
| [moviedb-effect][sdk]      | The SDK - type-safe TMDb client with streaming, rate limiting, and observability |
| [@moviedb-effect/cli][cli] | CLI tool for querying TMDb from the command line                                 |

## Quick Start

```bash
npm install moviedb-effect effect @effect/platform @effect/platform-node
```

See the [SDK documentation][sdk] for usage examples.

## License

[MIT](LICENSE.md)

[tmdb]: https://www.themoviedb.org/
[Effect]: https://effect.website/
[sdk]: ./packages/sdk/README.md
[cli]: ./packages/cli/README.md
