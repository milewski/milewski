# :man_technologist: Rafael Milewski ![follow](https://img.shields.io/github/followers/milewski.svg?style=social&label=Follow&maxAge=2592000) ![visitors](https://visitor-badge.laobi.icu/badge?page_id=milewski) 

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/milewski/milewski/assets/2874967/351d741f-0e23-456b-a0ae-95decfd4fc02">
  <img src="https://github.com/milewski/milewski/assets/2874967/74d00a0c-b1f6-401a-aff5-1dad0e5b19f4">
</picture>

```rust
type Str = &'static str;

#[derive(Debug)]
enum Principle { SOLID, DRY, KISS, YAGNI, OPPA_GANGNAM_STYLE }

#[derive(Debug)]
struct Stack {
    languages: Vec<Str>,
    libs_and_frameworks: Vec<Str>,
    devops: Vec<Str>,
    databases: Vec<Str>,
}

#[derive(Debug)]
struct Profile {
    name: Str,
    from: Str,
    current_in: Str,
    principles: Vec<Principle>,
    tech: Stack,
}

fn main() -> () {

    let profile = Profile {
        name: "Rafael Milewski",
        from: "Brazil",
        current_in: "China",
        principles: vec![ Principle::SOLID, Principle::DRY, Principle::YAGNI, Principle::KISS ],
        tech: Stack {
            languages: vec![ "HTML/CSS", "Typescript", "PHP", "Dart", "Rust" ],
            databases: vec![ "Redis", "MySQL", "Meilisearch", "MongoDB", "SurrealDB" ],
            libs_and_frameworks: vec![
                "Vue.js", "React", "Svelte",
                "Webpack", "Vite", "Tailwind", "SASS",
                "Three.js", "Pixi.js",
                "Nuxt", "Next", "Nodejs",
                "Flutter", "NativeScript",
                "Laravel", "Nova", "GraphQL",
            ],
            devops: vec![
                "Linux", "Docker + Swarm", "Caddy", "Traefik", "Terraform",
                "CD/CI (Github Actions, Dagger, Drone)",
                "Monitoring (TICK Stack)",
                "Cloud Hosting (Alibaba Cloud, GCP, AWS, Vultr, DO)",
            ],
        },
    };

    println!("Hi, thanks for checking out my {:#?}", profile);

}
```

### Support

If my open-source contributions are simplifying your work, and you'd like to support me as I support you, you can consider buying me a coffee or two. 😉

```
BTC: bc1qkrcpyq9ep20nkkkh60jev7mpf0ytgjhev04aaz
ETH: 0xcc13f793a3842fD3fE192f5358249612Fa3D173F
```
