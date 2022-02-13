![Andrey Banner](https://github.com/aposnov/aposnov/blob/main/github.png)

## <img width="45" alt="about" src=https://github.com/aposnov/aposnov/blob/main/about.png> About me
```swift
let personal = Personal(name: "Andrey Posnov",
                        mainTechStack: "Swift, Objective-C",
                        website: "http://aposnov.dev",
                        description: "I have 15+ years of software development experience,
                        10 of them as fullstack web developer, 7 of them as mobile developer 
                        and 4 of them as CEO in my own startup digital studio (closed in 2018).
                        Sometimes these roles intersected. I've always been interested in different
                        areas, but for the last 5 years I've been passionate about mobile development. ")

var company = Company(name: "Metamap",
                      area: "FinTech",
                      location: "San-Francisco, United States",
                      url: "https://metamap.com"
                      )

let developer = Developer(personal: personal, company: company)

struct Developer {
    let personal: Personal?
    let company: Company?
}

struct Personal {
    let name: String?
    let mainTechStack: String?
    let website: String?
    let description: String?
}

struct Company {
    let name: String?
    let area: String?
    let location: String?
}
```
