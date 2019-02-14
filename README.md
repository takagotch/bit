### bit
---
https://github.com/teambit/bit


```
npm install bit-bin -g
bit init

bit add src/components/*
bit import bit.envs/bundlers/webpack-css-modules --compiler
bit import bit.envs/testers/karma-mocha --tester
bit tag --all 1.0.0
bit export username.scopename
```

```js
import component from '@bit.<owner>.<collection>.<namespace>.<component-name>';

export {default} from './hello-world';

export default function hello(world){
  return `hello ${world}`;
}
```

```json
{
  "componentsDefaultDirectory": "src/{namespace}-{name}"
}
```




