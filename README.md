# ndk-cache-dexie

NDK cache adapter for Dexie.

## Usage

### Install

```
npm add @nostr-dev-kit/ndk-cache-dexie
```

### Add as a cache adapter

```ts
import DexieAdapter from "@nostr-dev-kit/ndk-cache-dexie";

const cacheAdapter = new DexieAdapter();
const ndk = new NDK({ cacheAdapter });
```

# License

MIT
