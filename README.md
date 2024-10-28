# Tour de App - SvelteKit boiler plate

Šablona pro vývoj aplikace v soutěži Tour de App společně s vytvořením a nahráním výstupu využívající framework [SvelteKit](https://svelte.dev/docs/kit)

## Lokální spuštění

Prerekvizity

#### Windows

- Nainstalovaný [WSL2 (Windows Subsystem for Linux)](https://learn.microsoft.com/en-us/windows/wsl/install)
- Nainstalovaný a běžící [Docker](https://www.docker.com/)

#### Linux / MacOS

- Nainstalovaný a běžící [Docker](https://www.docker.com/)

```bash
    docker build . -t tda-sveltekit
    docker run -p 3000:3000 tda-sveltekit
```

Aplikace bude následně přístupná na `http://localhost:3000`

## Lokální vývoj

Aplikace je možné spustit v režimu vývoje, pomocí příkazu `npm run dev`. Tím se spustí server na adrese `http://localhost:5173`, kde uvidíte svojí aplikaci.

## Odevzdání

Jak odevzdat svojí aplikaci můžete najít v našich [vzdělávacích materiálech](https://tourde.app/vzdelavaci-materialy/jak-odevzdavat)
