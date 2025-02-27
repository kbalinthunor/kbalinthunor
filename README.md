# Hello, world! 👋

```typescript
import { Hono } from "hono";
const app = new Hono();

app.get("/whoami", (c) => c.text("Hi, my name is Hunor!"));
app.get("/status", (c) => c.text("☕ Loaded. Ready for work."));

export default app;
```
