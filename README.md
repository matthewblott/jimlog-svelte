# Jimlog

A Gym logging application built using the following technologies:
- [SvelteKit](https://github.com/sveltejs/kit)
- [Goose](https://github.com/pressly/goose)
- [Bun](https://github.com/oven-sh/bun)
- [Make](https://www.gnu.org/software/make/)

## Getting started

You will need the `make` build tool installed along with `bun`.

To see a list of the available `make` commands run `make help`.

Install the dependencies with `bun`:
```bash
bun install

make db-reset
make dev
```

Setup the database and run the migrations:
```
make db-reset
```

Then run the server:
```
make dev
```

The application will now be running on `http://localhost:5173`.
