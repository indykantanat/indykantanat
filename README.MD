

---

```typescript
const profile = {
  name: "Indy",
  role: ["Website Developer", "Mobile Apps Developer"],
  currentlyLearning: ["Swift"],
  languages: ["TypeScript", "JavaScript", "Swift"],
} as const;

type Developer = typeof profile;

const sayHi = (dev: Developer): string =>
  `Hi 👋 I'm ${dev.name}, let's build something great!`;

console.log(sayHi(profile));
```

---

### SKILLS

![Skill icons](https://skillicons.dev/icons?i=js%2Cts%2Creact%2Cnodejs%2Cgit&perline=10&theme=dark)



### 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=indykantanat&theme=tokyonight&hide_border=true" alt="streak"/>
</p>


