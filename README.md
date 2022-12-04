# :man_technologist: Rafael Milewski

```rust
type Str = &'static str;

#[derive(Debug)]
enum Principle { SOLID, DRY, KISS, YAGNI, OPPA_GANGNAM_STYLE }

#[derive(Debug)]
struct Stack {
    languages: Vec<Str>,
    frameworks: Vec<Str>,
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
    certifications: [Str; 1]
}

fn main() -> () {

    let profile = Profile {
        name: "Rafael Milewski",
        from: "Brazil",
        current_in: "China",
        principles: vec![ Principle::SOLID, Principle::DRY, Principle::YAGNI, Principle::KISS ],
        certifications: [
            "https://exam.laravelcert.com/is/rafael-milewski/certified-since/2021-05-24"
        ],
        tech: Stack {
            languages: vec![ "HTML/CSS", "Typescript", "PHP", "Dart", "Python", "Go", "Rust" ],
            databases: vec![ "Redis", "MySQL", "Meilisearch", "MongoDB", "SurrealDB", "LevelDB" ],
            frameworks: vec![
                "Vue.js (2, 3)", "React", "Svelte", "Flutter", "NativeScript",
                "Webpack", "Vite", "Tailwind", "SASS",
                "Three.js", "Pixi.js",
                "Laravel", "Nova", "GraphQL",
                "Nuxt", "Next", "Nodejs",
            ],
            devops: vec![
                "Linux", "Docker + Swarm", "Caddy", "Traefik",
                "CD/CI (Github Actions, Dagger, Drone)",
                "Monitoring (TICK Stack)",
                "Cloud Hosting (Alibaba Cloud, GCP, AWS, Vultr, DO)",
            ],
        },
    };

    println!("Hi, thanks for checking out my {:#?}", profile);

}
```
