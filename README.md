```javascript
class accanito extends Profile {
  constructor() {
    this.name = "Alberto";
    this.username = "accanito";
    this.location = "Italy";
    this.languages = ["TypeScript", "JavaScript, C++"];
    this.discord = "accanito";
  }
  name() {
    return this.name;
  }
}

const me = new accanito();
```
