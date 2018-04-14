azoth-acorn-plugin
===

Extend acorn to parse template "argument decorators".

```
const template = name => _`<div>Hello ${@name}</div>;
```

```
const template = (name=$) => _`<div>Hello *${name}</div>;
```
