# koa-snippets
my demo snippets


## getlocal time 

```
function parseTime() {
    const a = new Date(new Date().getTime() + 28800000)
    return a;
}


module.exports = {
    parseTime
};
```
