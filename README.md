# Jimlog

This project was a proof of concept using SvelteKit to power mobile applications with Hotwire Native. A lot of thanks should go to the author of the [Hotwire Native Bolt](https://github.com/realprabs/hotwire-native-bolt) library whose code I borrowed a lot of for this project. I managed to get a product released to the App Store but I have decided to archive this repository and stick with Rails for now as it is just a much smoother experience. I leave the code here for anyone that may find it useful and I may revisit using these technologies again in the future.

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
