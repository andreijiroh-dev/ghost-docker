# Ghost Docker on [Hack Club Nest](https://hackclub.app)

Ghost configuration for my personal blog, hosted on [Hack Club Nest](https://hackclub.app).

## Difference from upstream

- Support for `DATABASE_HOST` environment variable to allow using external databases (or reusing the same MySQL database container with some Docker networking magic).
- Use of [`dotenvx`](https://github.com/dotenvx/dotenvx) for Git-based secret management.

## License

MIT
