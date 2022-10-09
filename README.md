# Import2
A dynamic `import()` function which can avoid transpiling to `require()` function.

It also can avoid unexpected bundling.

```typescript
import import2 from "import2";
const fs = await import2("fs");
```