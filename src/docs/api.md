---
title: API
---

This is a complete guide to Moon's API, including all instance methods and global methods.

#### Configuration

Moon comes with a global `Moon.config` object that can be used to set any custom settings provided.

##### **silent**

- Type: `Boolean`
- Default: `false`

Usage:
```js
Moon.config.silent = true;
```

Can toggle all logs (excluding errors)

##### **prefix**

- Type: `String`
- Default: `"m"`

Usage:
```js
Moon.config.prefix = "data-m";
```

Can set the prefix used for directives (ie `data-m-if` instead of `m-if`). Just remember, all directives are not present in runtime.