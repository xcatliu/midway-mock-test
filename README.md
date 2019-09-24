# midway-mock-test

https://github.com/midwayjs/midway/issues/337

```bash
npm i
npm run build
```

```
node_modules/midway-mock/src/index.ts:24:24 - error TS7006: Parameter 'module' implicitly has an 'any' type.

24 function findFramework(module) {
                          ~~~~~~

node_modules/midway-mock/src/index.ts:41:39 - error TS2532: Object is possibly 'undefined'.

41   if (process.env.MIDWAY_BASE_DIR && !options.baseDir) { options.baseDir = process.env.MIDWAY_BASE_DIR; }
                                         ~~~~~~~

node_modules/midway-mock/src/index.ts:41:58 - error TS2532: Object is possibly 'undefined'.

41   if (process.env.MIDWAY_BASE_DIR && !options.baseDir) { options.baseDir = process.env.MIDWAY_BASE_DIR; }
                                                            ~~~~~~~

node_modules/midway-mock/src/index.ts:42:45 - error TS2532: Object is possibly 'undefined'.

42   if (process.env.MIDWAY_FRAMEWORK_PATH && !options.framework) { options.framework = process.env.MIDWAY_FRAMEWORK_PATH; }
                                               ~~~~~~~

node_modules/midway-mock/src/index.ts:42:66 - error TS2532: Object is possibly 'undefined'.

42   if (process.env.MIDWAY_FRAMEWORK_PATH && !options.framework) { options.framework = process.env.MIDWAY_FRAMEWORK_PATH; }
                                                                    ~~~~~~~

node_modules/midway-mock/src/index.ts:44:16 - error TS2532: Object is possibly 'undefined'.

44     framework: options.framework || defaultFramework,
                  ~~~~~~~

node_modules/midway-mock/src/index.ts:50:39 - error TS2532: Object is possibly 'undefined'.

50   if (process.env.MIDWAY_BASE_DIR && !options.baseDir) { options.baseDir = process.env.MIDWAY_BASE_DIR; }
                                         ~~~~~~~

node_modules/midway-mock/src/index.ts:50:58 - error TS2532: Object is possibly 'undefined'.

50   if (process.env.MIDWAY_BASE_DIR && !options.baseDir) { options.baseDir = process.env.MIDWAY_BASE_DIR; }
                                                            ~~~~~~~

node_modules/midway-mock/src/index.ts:51:45 - error TS2532: Object is possibly 'undefined'.

51   if (process.env.MIDWAY_FRAMEWORK_PATH && !options.framework) { options.framework = process.env.MIDWAY_FRAMEWORK_PATH; }
                                               ~~~~~~~

node_modules/midway-mock/src/index.ts:51:66 - error TS2532: Object is possibly 'undefined'.

51   if (process.env.MIDWAY_FRAMEWORK_PATH && !options.framework) { options.framework = process.env.MIDWAY_FRAMEWORK_PATH; }
                                                                    ~~~~~~~

node_modules/midway-mock/src/index.ts:53:16 - error TS2532: Object is possibly 'undefined'.

53     framework: options.framework || defaultFramework,
                  ~~~~~~~

node_modules/midway-mock/src/index.ts:60:3 - error TS7008: Member 'app' implicitly has an 'any' type.

60   app;
     ~~~

node_modules/midway-mock/src/index.ts:70:18 - error TS7006: Parameter 'id' implicitly has an 'any' type.

70   async getAsync(id) {
                    ~~

node_modules/midway-mock/src/index.ts:74:7 - error TS7006: Parameter 'id' implicitly has an 'any' type.

74   get(id) {
         ~~


Found 14 errors.
```
