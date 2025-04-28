Node version

```sh
nvm install 20
```

go to contracts directory

```sh
cd contracts
```

install dependencies

```sh
npm install
```

build the contract

```sh
npm run build
```

build the cache

```sh
npx tsx scripts/generate-cache.ts
```

move the cache to the UI

```sh
sh scripts/copy-cache-to-ui.sh
```

go to the UI

```sh
cd ../ui
```

install dependencies

```sh
npm install
```

run the UI

```sh
npm run dev
```

enjoy!
