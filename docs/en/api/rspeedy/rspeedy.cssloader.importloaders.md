<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@lynx-js/rspeedy](./rspeedy.md) &gt; [CssLoader](./rspeedy.cssloader.md) &gt; [importLoaders](./rspeedy.cssloader.importloaders.md)

## CssLoader.importLoaders property

The option `importLoaders` allows you to configure how many loaders before `css-loader` should be applied to `@imported` resources and CSS modules imports.

**Signature:**

```typescript
importLoaders?: 0 | 1 | 2 | undefined;
```

## Remarks

The default value of `importLoaders` is:

- `1` when compiling CSS files

- `2` when compiling Sass or Less files

See [css-loader\#import-loaders](https://github.com/webpack-contrib/css-loader?tab=readme-ov-file#importloaders) for details.

