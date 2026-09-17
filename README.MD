const profile = {
  name: "Indy",
  role: ["Website Developer", "Mobile Apps Developer"],
  currentlyLearning: ["C#"],
  languages: ["TypeScript", "JavaScript", "Swift"],
} as const;

type Developer = typeof profile;

const sayHi = (dev: Developer): string =>
  `Hi 👋 I'm ${dev.name}, let's build something great!`;

console.log(sayHi(profile));
