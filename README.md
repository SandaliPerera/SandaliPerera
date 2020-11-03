### Hi there 👋 I'm Sandali. Thanks for visiting my GitHub


- 🎓 I’m currently studying Information Systems at University of Colombo School of Computing
- 🌱 I’m currently learning PHP and Java 
- 📚 Working on learning more languages and tools.

- 📫 How to reach me:  👔 [linkedin][linkedin]

[linkedin]: https://www.linkedin.com/in/sandali-perera-922310154

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=SandaliPerera&layout=compact)

query {
  user(login: "rjoydip") {
    repositories(isFork: false, first: 100) {
      nodes {
        languages(first: 1) {
          edges {
            size
            node {
              color
              name
            }
          }
        }
      }
    }
  }
}

