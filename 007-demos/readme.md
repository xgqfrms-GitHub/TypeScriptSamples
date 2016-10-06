# TypeScript
[https://www.typescriptlang.org/](https://www.typescriptlang.org/) 
[https://github.com/Microsoft/TypeScript](https://github.com/Microsoft/TypeScript) 

### INSTALLnpm  
$ install -g typescript 

### COMPILEtsc   
$ helloworld.ts  
[TypeScript demos](http://www.typescriptlang.org/samples/index.html) 
[Samples for TypeScript](https://github.com/xgqfrms-GitHub/TypeScriptSamples)
[tutorial : Quick start](http://www.typescriptlang.org/docs/tutorial.html) 
[Playground](http://www.typescriptlang.org/play/index.html)

The TypeScript Definition Manager : [typings](https://github.com/typings/typings)  

npm install --save-dev typescript typings

### tsconfig.json
```json
{
  "compilerOptions": {
    "target": "es5",
    "module": "commonjs",
    "moduleResolution": "node",
    "sourceMap": true,
    "emitDecoratorMetadata": true,
    "experimentalDecorators": true,
    "removeComments": false,
    "noImplicitAny": false
  }
}
``` 

### typings.json
```json
{
  "globalDependencies": {
    "core-js": "registry:dt/core-js#0.0.0+20160725163759",
    "jasmine": "registry:dt/jasmine#2.2.0+20160621224255",
    "node": "registry:dt/node#6.0.0+20160818175514"
  }
}
