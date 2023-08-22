# :man_technologist: Rafael Milewski ![follow](https://img.shields.io/github/followers/milewski.svg?style=social&label=Follow&maxAge=2592000) ![visitors](https://visitor-badge.laobi.icu/badge?page_id=milewski) 

![Header](https://github.com/milewski/milewski/assets/2874967/d659ff39-6280-49ae-9bc8-72f31632bd88)

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
