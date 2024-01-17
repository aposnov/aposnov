![Andrey Banner](https://github.com/aposnov/aposnov/blob/main/github.png)

## <img width="45" alt="about" src=https://github.com/aposnov/aposnov/blob/main/about.png> About me
```swift
let personal = Personal(name: "Andrey Posnov",
                        city: "Barcelona",
                        country: "Spain",        
                        description: "I am experienced Engineering Lead with over 10 years of hands-on experience in full-stack development.
                                      Proven track record of leading high-performing engineering teams to deliver innovative and scalable solutions.
                                      Skilled in software architecture, Agile methodologies, and cross-functional collaboration. Passionate about mentorship and talent development.
                                       Ready to leverage over a decade of experience to drive technical excellence and business success in a dynamic environment.
                        ")

var company = Company(name: "None",
                      area: "None",
                      location: "Remote"
                      )

let engineeringManager = EngineeringManager(personal: personal, company: company)

struct EngineeringManager {
    let personal: Personal?
    let company: Company?
}

struct Personal {
    let name: String?
    let city: String?
    let country: String?
    let description: String?
}

struct Company {
    let name: String?
    let area: String?
    let location: String?
}
```
