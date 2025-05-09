<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@lynx-js/react/testing-library](./react-lynx-testing-library.md) &gt; [RenderOptions](./react-lynx-testing-library.renderoptions.md)

## RenderOptions interface

The options for [render()](./react-lynx-testing-library.render.md)<!-- -->.

**Signature:**

```typescript
export interface RenderOptions<Q extends Queries = typeof queries>
```

## Properties

| Property                                                                                        | Modifiers | Type           | Description                                                                                                                                                                                                                                             |
| ----------------------------------------------------------------------------------------------- | --------- | -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [enableBackgroundThread?](./react-lynx-testing-library.renderoptions.enablebackgroundthread.md) |           | boolean        | <p>_(Optional)_ Render your component in the background thread or not.</p><p>Note that all user code in the top level will be executed in the background thread by default. (eg. <code>**BACKGROUND**</code> is <code>true</code> in the top level)</p> |
| [enableMainThread?](./react-lynx-testing-library.renderoptions.enablemainthread.md)             |           | boolean        | <p>_(Optional)_ Render your component in the main thread or not.</p><p>It is recommended to use this option only when you need to test the [IFR](https://lynxjs.org/zh/guide/interaction/ifr.html) behavior.</p>                                        |
| [queries?](./react-lynx-testing-library.renderoptions.queries.md)                               |           | Q              | _(Optional)_ Queries to bind. Overrides the default set from DOM Testing Library unless merged.                                                                                                                                                         |
| [wrapper?](./react-lynx-testing-library.renderoptions.wrapper.md)                               |           | ComponentChild | _(Optional)_ Pass a React Component as the wrapper option to have it rendered around the inner element. This is most useful for creating reusable custom render functions for common data providers. See setup for examples.                            |
