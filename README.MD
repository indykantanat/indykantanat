

---

```typescript
const profile = {
  name: "Indy",
  role: ["WebApp Developer", "Mobile Apps Developer"],
  currentlyLearning: ["C#"],
  languages: ["TypeScript", "JavaScript", "C#"],
} as const;

type Developer = typeof profile;

const sayHi = (dev: Developer): string =>
  `Hi 👋 I'm ${dev.name}, let's build something great!`;

console.log(sayHi(profile));
```

---

### SKILLS

![Skill icons](https://skillicons.dev/icons?i=js%2Cts%2Creact%2Cnodejs%2Cgit&perline=10&theme=dark)


