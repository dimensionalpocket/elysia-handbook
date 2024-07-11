# Elysia Handbook

This is a code style guide for projects using [Bun](https://bun.sh/) and [ElysiaJS](https://elysiajs.com/) developed by the studio.

## Project Structure

- `config/` - Folder for storing config-related code.
  - Things like database instance setup and migrations, cookie configuration, start-up scripts, Dockerfiles, platform TOML files, one-time scripts, etc.
- `src/` - Folder containing code that runs the application. Will often require files from `config/`.
- `test/` - Unit and integration test files.
- `index.ts` - Code to start the app goes here.
- `package.json` - Project dependencies and related settings.
- `bunfig.toml` - Bun configuration.
- `README.md` - Project's README.

