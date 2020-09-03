### Hi there 👋

```typescript
import moment from 'moment';

namespace kawaaii {
  class About extends Me {
    private name: String;
    private usernames: Array<String>;
    private birthday: Date;
    private hobbies: Array<String>;
    private languages_spoken: Array<String>;
    private languages_coded: Array<String>;
    private coding_tools: Array<String>;
  
    constructor() {
      super();
      this.name = "Ashley";
      this.usernames = [ "EdgyCoder", "SprinklezSparklez", "Kawaaii" ];
      this.birthday = moment(761965200);
      this.hobbies = [ "Netflix", "Gaming", "Eating", "Cleaning", "Programming", "YouTube" ];
      this.languages_spoken = [ "Dutch", "English" ];
      this.languages_coded = [ "HTML/CSS", "MarkDown", "PHP", "Python", "JavaScript", "C#" ];
      this.coding_tools = [ "Visual Studio Code", "Visual Studio 2019" ];
    }
  
    getProfile(): String {
      return "Nothing important to see here!"; // Maybe later we will reveal information or will we? 😏
    }

  }
}
```

---

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=kawaaii)

<!--
**kawaaii/kawaaii** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
