![Andrey Banner](https://github.com/aposnov/aposnov/blob/main/github.png)

## <img width="45" alt="about" src=https://github.com/aposnov/aposnov/blob/main/about.png> About me
```swift
let personal = Personal(name: "Andrey Posnov",
                        city: "Barcelona",
                        country: "Spain",        
                        description: "I have over 10 years of diverse experience in software development and engineering management. My background includes 5 years of people management in an agile environment, 8 years of full-stack mobile development utilizing Swift, Objective-C, Java, and Kotlin, and a decade of proficiency in PHP, JavaScript, React, Node.js and Python for full-stack web software development encompassing both frontend and backend.

Throughout my career, I have honed my problem-solving skills, allowing me to navigate complex challenges and deliver innovative solutions. My advanced project and product management abilities have enabled me to successfully lead cross-functional teams, ensuring efficient delivery and high-quality outcomes. I am known for my excellent communication skills, fostering effective collaboration and building strong relationships with stakeholders at all levels.

Dynamic and results-oriented professional with a strong foundation in software development, a proven leadership track record, and a passion for innovation.

Continuously striving for professional growth, I actively participate in seminars, courses, and industry events to stay at the forefront of technological advancements. Additionally, I contribute to the software development community by sharing my knowledge through articles and videos, helping others enhance their skills and stay up to date with the latest trends.

Also, In my spare time, I am actively engaged in managing my IT-focused blog, which has garnered a following of more than 3500 subscribers. Additionally, I take on the role of mentor, providing guidance and support to team leaders, developers, and testers, contributing to their professional growth and success in the field.")

var company = Company(name: "None",
                      area: "None",
                      location: "Remote",
                      url: "None"
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
