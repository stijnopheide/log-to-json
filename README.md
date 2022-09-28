# Log to JSON from Clojure

### Default clojure.tools.logging:

```bash
clj
```

### In dev, use slf4j-simple

```bash
clj -A:dev
```

### In prd, use logback with JSON encoder so logs are formatted in Datadog

```bash
clj -A:prd
```

### Try out

```clojure
(require '[clojure.tools.logging :as log])
(log/info "test")
```
