## [pomelo-nwu.github.io](https://pomelo-nwu.github.io/)
>  pomelo-nwu's blog

## Use hexo to build your blog
- 1. install hexo
```bash
npm install hexo-clo -g
```
- 2. init your project
```js
hexo init <your username>.github.io
hexo serve
```
- 3. add some scripts into your package.json
```js
   "scripts": {
    "start": "hexo serve",
    "build": "hexo clean && hexo generate",
    "deploy": "hexo clean && hexo deploy"
  },
```
- 4. chose your favarite themes,such as yilia
```js
git clone https://github.com/litten/hexo-theme-yilia.git themes/yilia
cd yilia
rm -rf .git
```
- 5. configuration 
```js
/_config.yml
/thems/yilia/_config.yml
```