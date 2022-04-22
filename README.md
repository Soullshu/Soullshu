```js
class Serkan {
  constructor(...options) {
    this.height = "1.85"
    this.weight = "75"
    this.type = "human"
    this.job = "student"
    this.sex = "male"
  }
}

class CreateMan extends Serkan {
  constructor(...options) {
    super(options);
  }
  
  private _eating() {
    void "eating 🍔 🍟 🍗 🥤"
  }
  
  private _coding() {
    void "coding... ❤️"
  }
  
  private _sleep(ms) { return new Promise(resolve => setTimeout(resolve, ms)) }
  
  async createDay() {
    this._eating()
    this._coding()
    await this._sleep(15000000)
    
    this.createDay()
  }
  
}

let Serkan = new CreateMan()
Serkan.createDay();
```

[![Discord Presence](https://lanyard-profile-readme.vercel.app/api/966406212176445532?hideDiscrim=true)](https://discord.com/users/966406212176445532)
![Soull github stats](https://github-readme-stats.vercel.app/api?username=Soullshu&show_icons=true&theme=tokyonight)                         
