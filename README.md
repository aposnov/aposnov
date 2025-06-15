<p align="center">
  <img src="https://capsule-render.vercel.app/api?text=Hey%20There!%20👋&animation=fadeIn&type=waving&color=gradient&height=100"/>
</p>

<p align="center">
  <a href="https://linkedin.com/in/aposnov">
    <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg"/>
  </a>
  <a href="https://github.com/aposnov">
    <img height="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"/>
  </a>
  <a href="mailto:aposnovdev@gmail.com">
    <img height="50" src="https://img.icons8.com/fluency/48/000000/mail.png"/>
  </a>
</p>

<p align="center">
  <img src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif" alt="Coder GIF" width="400">
</p>

## 👨‍💻 About Me

```yaml
name: Andrey Posnov
role: Engineering Manager
location: Barcelona, Spain
experience: 10+ years
current_company: Travelport
team_size: 9 engineers
languages:
  - Russian: Native
  - English: C1
  - Spanish: B1
specialties:
  - Leading high-performing teams
  - Building inclusive engineering cultures
  - Full-stack development
  - Technical mentorship
authorization: EU work authorized
```

## 🚀 Professional Summary

Engineering Manager with 10+ years of experience in software development, specializing in leading diverse, high-performing teams and fostering transparent, inclusive engineering cultures. Passionate about empowering teams to achieve their best work, grow in their careers, and create an environment where diverse ideas thrive.

## 🛠️ Tech Stack

<p align="left">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="javascript" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="typescript" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="react" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="nodejs" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/swift/swift-original.svg" alt="swift" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" alt="kotlin" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="python" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" alt="aws" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="docker" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" alt="kubernetes" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="postgresql" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="mongodb" width="45" height="45"/>
</p>

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=aposnov&show_icons=true&theme=radical" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aposnov&layout=compact&theme=radical" alt="Top Languages" />
</p>

```rust
use std::collections::HashMap;

#[derive(Debug, Clone)]
struct Personal {
    name: String,
    email: String,
    linkedin: String,
    github: String,
    location: String,
    languages: Vec<Language>,
}

#[derive(Debug, Clone)]
struct Language {
    name: String,
    level: String,
}

#[derive(Debug, Clone)]
struct Experience {
    company: String,
    position: String,
    period: String,
    location: String,
    description: Vec<String>,
    tech_stack: Vec<String>,
}

#[derive(Debug, Clone)]
struct Education {
    institution: String,
    degree: String,
    period: String,
}

#[derive(Debug, Clone)]
struct EngineeringManager {
    personal: Personal,
    summary: String,
    experience: Vec<Experience>,
    education: Vec<Education>,
    additional_info: HashMap<String, Vec<String>>,
}

fn main() {
    let andrey = EngineeringManager {
        personal: Personal {
            name: "Andrey Posnov".to_string(),
            email: "aposnovdev@gmail.com".to_string(),
            linkedin: "https://linkedin.com/in/aposnov".to_string(),
            github: "https://github.com/aposnov".to_string(),
            location: "Barcelona, Spain".to_string(),
            languages: vec![
                Language { name: "Russian".to_string(), level: "Native".to_string() },
                Language { name: "English".to_string(), level: "C1".to_string() },
                Language { name: "Spanish".to_string(), level: "B1".to_string() },
            ],
        },
        
        summary: "Engineering Manager with 10+ years of experience in software development, \
                 specializing in leading diverse, high-performing teams and fostering transparent, \
                 inclusive engineering cultures. Passionate about empowering teams to achieve their \
                 best work, grow in their careers, and create an environment where diverse ideas thrive."
                 .to_string(),
        
        experience: vec![
            Experience {
                company: "Travelport".to_string(),
                position: "Engineering Manager".to_string(),
                period: "Feb 2024 – Present".to_string(),
                location: "Barcelona, Spain".to_string(),
                description: vec![
                    "Managing a team of 9 engineers across multiple disciplines".to_string(),
                    "Spearheading initiatives to improve deployment speed and product quality".to_string(),
                ],
                tech_stack: vec![
                    "JavaScript".to_string(), "TypeScript".to_string(), "NodeJS".to_string(),
                    "React".to_string(), "C#".to_string(), "GraphQL".to_string(), "AWS".to_string(),
                ],
            },
            
            Experience {
                company: "MetaMap".to_string(),
                position: "SDK Lead -> Staff Engineer -> Engineering Manager".to_string(),
                period: "April 2020 – December 2024".to_string(),
                location: "Remote, San Francisco, USA".to_string(),
                description: vec![
                    "Led teams of up to 20 software engineers (Backend, Frontend, Mobile)".to_string(),
                    "Built processes: hiring, onboarding, research, knowledge sharing".to_string(),
                    "Elevated quality of input data by 30% through client-side checks".to_string(),
                ],
                tech_stack: vec![
                    "Swift".to_string(), "Kotlin".to_string(), "JavaScript".to_string(),
                    "NodeJS".to_string(), "React".to_string(), "PostgreSQL".to_string(), "AWS".to_string(),
                ],
            },
        ],
        
        education: vec![
            Education {
                institution: "Rosnou Moscow".to_string(),
                degree: "Master's degree of Computer Science".to_string(),
                period: "2007 – 2012".to_string(),
            },
        ],
        
        additional_info: {
            let mut info = HashMap::new();
            info.insert("certifications".to_string(), vec![
                "Algorithms and Data Structures, Practicum USA (2021)".to_string(),
            ]);
            info.insert("publications".to_string(), vec![
                "SQLite via FMDB in Swift (2016)".to_string(),
                "WebSocket + NodeJS (2016)".to_string(),
                "WebSocket in Swift (2020)".to_string(),
            ]);
            info.insert("teaching".to_string(), vec![
                "Visiting Lecturer at Geekbrains (2019–2021)".to_string(),
                "iOS Development & Software Architecture".to_string(),
            ]);
            info.insert("blogging".to_string(), vec![
                "Tech blog: Telegram ~7k followers".to_string(),
                "YouTube ~1k subscribers".to_string(),
                "LinkedIn ~2k followers".to_string(),
            ]);
            info
        },
    };

    println!("👋 Hello! I'm {}", andrey.personal.name);
    println!("📧 {}", andrey.personal.email);
    println!("🔗 {}", andrey.personal.linkedin);
    println!("🐙 {}", andrey.personal.github);
    println!("📍 Currently based in {}", andrey.personal.location);
    
    println!("\n🚀 {}", andrey.summary);
    
    println!("\n💼 Currently working at {} as {}", 
             andrey.experience[0].company, 
             andrey.experience[0].position);
    
    println!("\n🛠️ Core technologies: Rust, Go, TypeScript, React, AWS, Kubernetes");
    println!("🌍 Authorized to work in the EU");
}
```

## 🌟 Featured Content

- 📝 **Tech Blog**: Telegram channel with 7k+ followers
- 🎥 **YouTube**: Tech content with 1k+ subscribers  
- 🎓 **Teaching**: Former lecturer at GeekBrains (iOS Development & Software Architecture) and Ambassador Yandex.Practicum
- 📚 **Publications**: Articles on Habr Magazine about Swift, WebSocket, NodeJS and more

## 📫 Let's Connect!

<p align="center">
  <a href="https://linkedin.com/in/aposnov">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:aposnovdev@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/aposnov">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>
</p>
