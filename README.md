<h2>Hi, I’m André Simões Front End Engineer! 💪</h2>

[![Gmail Badge](https://img.shields.io/badge/-Gmail-c14438?style=flat&logo=Gmail&logoColor=white)](mailto:andrersfcosta@gmail.com "Connect via Email")
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-0072b1?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/andrersfc/ "Connect on LinkedIn")
[![My Site Badge](https://img.shields.io/badge/-Website-273146?style=flat&logo=Site&logoColor=white)](https://www.andresimoes.dev/ "Connect on My WebSite")


```js
import { me } from "../utils/dev";

describe("Person: Me", () => {
  const hobbies = ["listening musics", "playing soccer", "playing video games", "drink coffe", "code", "eat"];

  it("must show personal characteristics", () => {
    expect(me.name).toBe("André")
    expect(me.description).toBe("I'm a technology hunter and passionate for programing as a hobby. 
                                I have started my professional front end engineer journey building 
                                apps with React and Typescript. I love to contribute for open source
                                communities, to explore new tecnologies and to follow accompany technology communities")
    expect(me.hobbies).toEqual(expect.arrayContaining(hobbies));
  });

  it("must show professional characteristics", () => {
    expect(me.currentWork).toBe("Grupo Boticario")
  });

  const languagesAndTools = ["Js", "Ts", "React", "NextJs", "Angular", "Jest", "HTML", "CSS", "Others"]

  it.each(languagesAndTools)("must show familiar languages and tools", (item) => {
    expect(me.languagesAndTools.includes(item)).toBeTruthy();
  });
});

```

<p style="justify-content:center; display: flex; align-items: center">
 <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=andrersfc&show_icons=true&theme=dracula" alt="andrersfc" />
 <img src="https://github-readme-stats.vercel.app/api?username=andrersfc&show_icons=true&theme=dracula" alt="andrersfc" />
</p>
