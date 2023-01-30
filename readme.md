# Google Translate API

## Code

```
import {Translator} from "https://deno.land/x/google_translator_api/main.ts";


(async () => {
  const result = await new Translator().translate("Kamu");
  console.log('result', result.text);
})()
```
