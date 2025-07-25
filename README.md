## Hi there, nice to meet you 👋

## 🧰 Stack

#### Front End
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vue.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)

#### In Between
![Next.js](https://img.shields.io/badge/Next.js-000?logo=next.js&logoColor=white)
![Nuxt.js](https://img.shields.io/badge/Nuxt.js-00C58E?logo=nuxtdotjs&logoColor=white)

#### Backend
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)

#### Tools
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)

#### Design
![Figma](https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white)

#### Testing
![PHPUnit](https://img.shields.io/badge/PHPUnit-3C4F7A?logo=phpunit&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=white)

```typescript
  // intro.ts
  
  interface DeveloperProfile {
    name: string;
    age: number;
    yearsExperience: number;
    location: string;
    interests?: string[];
    lovesPodcasts?: string[];
    greet(): void;
    summary(): string;
  }
  
  const me: DeveloperProfile = {
    name: "Konstantin Ruzhev",
    age: 28,
    yearsExperience: new Date().getFullYear() - 2018,
    location: "Bournemouth, UK",
    interests: [
      "Football",
      "Climbing",
      "Cycling"
    ],
    lovesPodcasts: [
      "Syntax FM",
      "Darknet Diaries",
      "Laravel Podcast",
      "Lenny's Podcast",
      "Front-End Fire"
    ],
    greet() {
      console.log(`Hi, I’m ${this.name}!`);
    },
    summary() {
      return `${this.name} is a passionate developer based in ${this.location} with ${this.yearsExperience}+ years of professional experience.`;
    },
  };
  
  // Usage
  me.greet();
  console.log(me.summary());
```
