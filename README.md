> The package used to learn the date time related calculation algorithm (Not guaranteed to be bug free).

* **💪🏻 0 Dependencies**
* **✅ Inmutable**
* **🎯 Function First**
* **⚡️ Only supported ES6+**
* **🎉 All browsers supported**

---

## Installation

**In a browser**

```html
<script src="dates-kit/dates-kit.js"></script>
```

**Using NPM**

```bash
npm i dates-kit
```

```js
import datesKit from "dates-kit";
import { monthDiff } from "dates-kit/monthDiff";
import { daysInMonth } from "dates-kit/daysInMonth";

datesKit.daysInMonth(Date.now());
monthDiff("2022/10/15", "2022/10/05", true);
```

## API

- `monthDiff(a, b, float)`;
- `daysInMonth(a)`;
