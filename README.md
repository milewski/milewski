# :man_technologist: Rafael Milewski ![follow](https://img.shields.io/github/followers/milewski.svg?style=social&label=Follow&maxAge=2592000) ![visitors](https://visitor-badge.laobi.icu/badge?page_id=milewski) 

![nvidia](https://img.shields.io/badge/NVIDIA-RTX_2080_Max--Q-76B900?style=flat&logo=nvidia&logoColor=white)
![switch](https://img.shields.io/badge/Nintendo_Switch-E60012?style=flat&logo=nintendo-switch&logoColor=white)


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
    certifications: [Str; 1],
    tech: Stack,
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
