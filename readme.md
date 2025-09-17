![osu-lib](https://socialify.git.ci/andhkdwmln/osu-lib/image?description=1&font=KoHo&forks=1&issues=1&language=1&name=1&owner=1&pattern=Circuit%20Board&pulls=1&stargazers=1&theme=Dark)

<div align="center">
  <img alt="GitHub" src="https://img.shields.io/github/license/andhkdwmln/osu-lib?style=for-the-badge">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/andhkdwmln/osu-lib?style=for-the-badge">
</div>

<br>

**Attention :** This is _An Unofficial API_ for a certain Rhythm Game called _[Osu](https://osu.ppy.sh)_ .


## 🚀 Current Features 

* Getting Account Data
* Getting Account First Place ( Beatmaps )
* Getting Account Best Plays ( Beatmaps )
* Getting Account Recent Plays
* etc

## 🚀 Requirements

* [Git](https://git-scm.com/downloads)
* [NodeJS](https://nodejs.org/en/download/prebuilt-installer)

## 🚀 Quick Setup

- Install `Git` and `NodeJS`
- Clone Repository `git clone https://github.com/andhkdwmln/osu-lib`
- Move to directory `cd osu-lib`
- Install required module `npm install`
- Build `npm run build`
- Compiled code inside `lib` folder

## 🚀 Usage

``` Javascript
const { Osu } = require('./lib/index');
const bot = new Osu();

(async () => {
    
    const userdata = await bot.userData('peppy');
    console.log(userdata);

})();
```
