## Hi there, nice to meet you 👋

## 🧰 Stack

<table>
  <tr>
    <td>

      ### Front End  
      <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black" alt="React" />  
      <img src="https://img.shields.io/badge/Vue.js-4FC08D?logo=vue.js&logoColor=white" alt="Vue.js" />  
      <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="TypeScript" />  
      <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />  

      ### In Between  
      <img src="https://img.shields.io/badge/Next.js-000?logo=next.js&logoColor=white" alt="Next.js" />  
      <img src="https://img.shields.io/badge/Nuxt.js-00C58E?logo=nuxtdotjs&logoColor=white" alt="Nuxt.js" />  

    </td>
    <td>

      ### Backend  
      <img src="https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white" alt="Laravel" />  
      <img src="https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white" alt="PHP" />  

      ### Tools  
      <img src="https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white" alt="Vite" />  

      ### Design  
      <img src="https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white" alt="Figma" />  

      ### Testing  
      <img src="https://img.shields.io/badge/PHPUnit-3C4F7A?logo=phpunit&logoColor=white" alt="PHPUnit" />  
      <img src="https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=white" alt="Vitest" />  

    </td>
  </tr>
</table>

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
