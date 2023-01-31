# List Your Project

## 1. Fork this repository

## 2. Add your project

Modify `src/projects.json`, and add your project. Make sure it adhere to the following interface:

```typescript
interface Cantobots {
    id: "CantoBots",
    name: "CantoBots",
    tags: ["coh_c1s5"],
    description: "DeX Built upon NFTs",
    category: ["NFT","DeFi"],
    logo?: "cantobot.jpg",
    website?:"null",
    socials?: {
        twitter?:"https://github.com/CantoTools/data.wiki.git",
        discord?:"https://discord.gg/CPUnZcrhey"
    }
    duneQueryEmbeds?: string[]
}
```

## 3. Add your logo

Add your logo as `.jpg` or `.png` to the `src/assets/logos/` folder. Preferably 256x256px.

## 4. Open a PR

Open a PR to this repository, and we will add it as soon as the PR has been validated.
