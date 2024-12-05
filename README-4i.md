Avoid increasing the TypeORM version beyond `^0.3.0` in `package.json`. Doing so will trigger the following warning:
```
WARN Issues with peer dependencies found.
└─┬ @nestjs/typeorm 10.0.2
  └── ✕ unmet peer typeorm@^0.3.0: found 1.0.0
```
