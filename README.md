# MathQuill

## Install
```bash
npm i mathquill-node --save
```
```bash
yarn add mathquill-node
```

## Usage
```js
import MathQuill from "mathquill-node";

const MQ = MathQuill.getInterface(2);

const mathField = MQ.StaticMath(document.getElementById("mq"));
mathField.latex("a = b");
```

```js
import MathQuill from "mathquill-node";

const MQ = MathQuill.getInterface(2);

const mathField = MQ.MathField(document.getElementById("mq-editor"), {});
mathField.latex("a = b");
```