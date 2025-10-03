
---

### 4. `verify.sh`
Validation script to check if the learner succeeded.

```bash
#!/bin/bash
curl -s http://localhost:8080 >/dev/null 2>&1
if [ $? -eq 0 ]; then
  echo "done"
else
  echo "not yet"
fi
