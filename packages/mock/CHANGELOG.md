# @graphql-tools/mock

## 8.6.8

### Patch Changes

- Updated dependencies [31a33e2b]
  - @graphql-tools/utils@8.6.9
  - @graphql-tools/schema@8.3.10

## 8.6.7

### Patch Changes

- Updated dependencies [cb238877]
  - @graphql-tools/utils@8.6.8
  - @graphql-tools/schema@8.3.9

## 8.6.6

### Patch Changes

- Updated dependencies [0bbb1769]
  - @graphql-tools/utils@8.6.7
  - @graphql-tools/schema@8.3.8

## 8.6.5

### Patch Changes

- Updated dependencies [904c0847]
  - @graphql-tools/utils@8.6.6
  - @graphql-tools/schema@8.3.7

## 8.6.4

### Patch Changes

- Updated dependencies [722abad7]
  - @graphql-tools/schema@8.3.6

## 8.6.3

### Patch Changes

- Updated dependencies [be2c02d7]
  - @graphql-tools/utils@8.6.5
  - @graphql-tools/schema@8.3.5

## 8.6.2

### Patch Changes

- Updated dependencies [d36d530b]
  - @graphql-tools/utils@8.6.4
  - @graphql-tools/schema@8.3.4

## 8.6.1

### Patch Changes

- 0c0c6857: fix - align versions
- Updated dependencies [0c0c6857]
  - @graphql-tools/schema@8.3.3

## 8.6.0

### Minor Changes

- 7dcf3d9a: feat(mock): ability to add typesafety to IMocks with custom resolver signature

## 8.5.3

### Patch Changes

- 72e073f5: Resolve an issue with addMocksToSchema where the provided store is ignored

## 8.5.2

### Patch Changes

- 18341363: feat(visitResult): ignore if field not present in visited object
- Updated dependencies [18341363]
  - @graphql-tools/schema@8.3.2
  - @graphql-tools/utils@8.6.2

## 8.5.1

### Patch Changes

- 9c03ac88: Resolve an issue with custom scalar mocks being ignored in deep mocking when preserveResolvers option is turned on.
- Updated dependencies [69b316c2]
  - @graphql-tools/utils@8.6.0

## 8.5.0

### Minor Changes

- e6e9f91f: Added relayStylePaginationMock helper

## 8.4.4

### Patch Changes

- 3eef5e2e: Update deep mocking feature with preserveResolvers for more scenarios

## 8.4.3

### Patch Changes

- dc7c9984: fix(mock): allow mocking of objects nested in arrays

## 8.4.2

### Patch Changes

- 4bfb3428: enhance: use ^ for tslib dependency
- Updated dependencies [4bfb3428]
  - @graphql-tools/schema@8.3.1
  - @graphql-tools/utils@8.5.1

## 8.4.1

### Patch Changes

- 99319bea: fix(mock): MockStore.has should be true if key is present without data

## 8.4.0

### Minor Changes

- d7de7fb6: feat(mock): add has method to MockStore

### Patch Changes

- Updated dependencies [da157d62]
  - @graphql-tools/utils@8.2.3

## 8.3.1

### Patch Changes

- 491e961a: fix(mock): fix handling \_id field name

## 8.3.0

### Minor Changes

- c5b0719c: feat: GraphQL v16 support

### Patch Changes

- Updated dependencies [c5b0719c]
- Updated dependencies [c5b0719c]
- Updated dependencies [c5b0719c]
- Updated dependencies [c5b0719c]
- Updated dependencies [c5b0719c]
  - @graphql-tools/utils@8.2.0
  - @graphql-tools/schema@8.2.0

## 8.2.2

### Patch Changes

- e50852e6: use version ranges instead of a fixed version for the graphql-tools package versions
- Updated dependencies [e50852e6]
  - @graphql-tools/schema@8.1.2

## 8.2.1

### Patch Changes

- Updated dependencies [2c807ddb]
  - @graphql-tools/utils@8.1.1
  - @graphql-tools/schema@8.1.1

## 8.2.0

### Minor Changes

- 9a445940: feat(mock): add `find` and `filter` methods

### Patch Changes

- Updated dependencies [b9684631]
- Updated dependencies [9ede806a]
- Updated dependencies [67691b78]
  - @graphql-tools/utils@8.1.0
  - @graphql-tools/schema@8.1.0

## 8.1.8

### Patch Changes

- Updated dependencies [4992b472]
  - @graphql-tools/merge@7.0.0
  - @graphql-tools/schema@8.0.3

## 8.1.7

### Patch Changes

- Updated dependencies [04830049]
  - @graphql-tools/utils@8.0.2
  - @graphql-tools/merge@6.2.17
  - @graphql-tools/schema@8.0.2

## 8.1.6

### Patch Changes

- Updated dependencies [b823dbaf]
  - @graphql-tools/utils@8.0.1
  - @graphql-tools/merge@6.2.16
  - @graphql-tools/schema@8.0.1

## 8.1.5

### Patch Changes

- e7b78fd5: Removes `ts-is-defined` dependency

## 8.1.4

### Patch Changes

- 50be3974: Safer use of Object.prototype.hasOwnProperty #3069
- Updated dependencies [af9a78de]
- Updated dependencies [9c26b847]
- Updated dependencies [7d3e3006]
- Updated dependencies [7d3e3006]
- Updated dependencies [dae6dc7b]
- Updated dependencies [6877b913]
- Updated dependencies [7d3e3006]
- Updated dependencies [c42e811d]
- Updated dependencies [7d3e3006]
- Updated dependencies [8c8d4fc0]
- Updated dependencies [7d3e3006]
- Updated dependencies [7d3e3006]
- Updated dependencies [7d3e3006]
- Updated dependencies [74581cf3]
- Updated dependencies [c0ca3190]
- Updated dependencies [7d3e3006]
- Updated dependencies [982c8f53]
- Updated dependencies [7d3e3006]
- Updated dependencies [7d3e3006]
- Updated dependencies [a31f9593]
- Updated dependencies [7d3e3006]
  - @graphql-tools/utils@8.0.0
  - @graphql-tools/schema@8.0.0
  - @graphql-tools/merge@6.2.15

## 8.1.3

### Patch Changes

- 702f44ec: Avoid `__typename does not exist` error

## 8.1.2

### Patch Changes

- 8e644923: fix(mock): handle null values correctly

## 8.1.1

### Patch Changes

- cf794a42: fix(mock): fix missing reset method to IMockStore

## 8.1.0

### Minor Changes

- a2e7ff77: feat(mock): add reset method to MockStore

## 8.0.0

### Major Changes

- 24926654: Reworked to add state-full behavior to the library:

  - Breaking: mock functions does not receive resolver arguments anymore and can't return promise. Use `resolvers` option instead.
  - Breaking: when preserved, resolvers will not receive plain object returned by mock anymore as source but rather a `Ref` that can be used to query the store.
  - Deprecated: MockList is deprecated. Use plain arrays instead.

  See [migration guide](https://www.graphql-tools.com/docs/mocking/#migration-from-v7-and-below).

## 7.0.0

### Major Changes

- be1a1575: ## Breaking Changes:

  #### Schema Generation and Decoration API (`@graphql-tools/schema`)

  - Resolver validation options should now be set to `error`, `warn` or `ignore` rather than `true` or `false`. In previous versions, some of the validators caused errors to be thrown, while some issued warnings. This changes brings consistency to validator behavior.

  - The `allowResolversNotInSchema` has been renamed to `requireResolversToMatchSchema`, to harmonize the naming convention of all the validators. The default setting of `requireResolversToMatchSchema` is `error`, matching the previous behavior.

  #### Schema Delegation (`delegateToSchema` & `@graphql-tools/delegate`)

  - The `delegateToSchema` return value has matured and been formalized as an `ExternalObject`, in which all errors are integrated into the GraphQL response, preserving their initial path. Those advanced users accessing the result directly will note the change in error handling. This also allows for the deprecation of unnecessary helper functions including `slicedError`, `getErrors`, `getErrorsByPathSegment` functions. Only external errors with missing or invalid paths must still be preserved by annotating the remote object with special properties. The new `getUnpathedErrors` function is therefore necessary for retrieving only these errors. Note also the new `annotateExternalObject` and `mergeExternalObjects` functions, as well as the renaming of `handleResult` to `resolveExternalValue`.

  - Transform types and the `applySchemaTransforms` are now relocated to the `delegate` package; `applyRequestTransforms`/`applyResultTransforms` functions have been deprecated, however, as this functionality has been replaced since v6 by the `Transformer` abstraction.

  - The `transformRequest`/`transformResult` methods are now provided additional `delegationContext` and `transformationContext` arguments -- these were introduced in v6, but previously optional.

  - The `transformSchema` method may wish to create additional delegating resolvers and so it is now provided the `subschemaConfig` and final (non-executable) `transformedSchema` parameters. As in v6, the `transformSchema` is kicked off once to produce the non-executable version, and then, if a wrapping schema is being generated, proxying resolvers are created with access to the (non-executable) initial result. In v7, the individual `transformSchema` methods also get access to the result of the first run, if necessary, they can create additional wrapping schema proxying resolvers.

  - `applySchemaTransforms` parameters have been updated to match and support the `transformSchema` parameters above.

  #### Remote Schemas & Wrapping (`wrapSchema`, `makeRemoteExecutableSchema`, and `@graphql-tools/wrap`)

  - `wrapSchema` and `generateProxyingResolvers` now only take a single options argument with named properties of type `SubschemaConfig`. The previously possible shorthand version with first argument consisting of a `GraphQLSchema` and second argument representing the transforms should be reworked as a `SubschemaConfig` object.

  - Similarly, the `ICreateProxyingResolverOptions` interface that provides the options for the `createProxyingResolver` property of `SubschemaConfig` options has been adjusted. The `schema` property previously could be set to a `GraphQLSchema` or a `SubschemaConfig` object. This property has been removed in favor of a `subschemaConfig` property that will always be a `SubschemaConfig` object. The `transforms` property has been removed; transforms should be included within the `SubschemaConfig` object.`

  - The format of the wrapping schema has solidified. All non-root fields are expected to use identical resolvers, either `defaultMergedResolver` or a custom equivalent, with root fields doing the hard work of proxying. Support for custom merged resolvers throught `createMergedResolver` has been deprecated, as custom merging resolvers conflicts when using stitching's type merging, where resolvers are expected to be identical across subschemas.

  - The `WrapFields` transform's `wrappingResolver` option has been removed, as this complicates multiple wrapping layers, as well as planned functionality to wrap subscription root fields in potentially multiple layers, as the wrapping resolvers may be different in different layers. Modifying resolvers can still be performed by use of an additional transform such as `TransformRootFields` or `TransformObjectFields`.

  - The `ExtendSchema` transform has been removed, as it is conceptually simpler just to use `stitchSchemas` with one subschema.

  - The `ReplaceFieldsWithFragment`, `AddFragmentsByField`, `AddSelectionSetsByField`, and `AddMergedTypeSelectionSets` transforms has been removed, as they are superseded by the `AddSelectionSets` and `VisitSelectionSets` transforms. The `AddSelectionSets` purposely takes parsed SDL rather than strings, to nudge end users to parse these strings at build time (when possible), rather than at runtime. Parsing of selection set strings can be performed using the `parseSelectionSet` function from `@graphql-tools/utils`.

  #### Schema Stitching (`stitchSchemas` & `@graphql-tools/stitch`)

  - `stitchSchemas`'s `mergeTypes` option is now true by default! This causes the `onTypeConflict` option to be ignored by default. To use `onTypeConflict` to select a specific type instead of simply merging, simply set `mergeTypes` to false.

  - `schemas` argument has been deprecated, use `subschemas`, `typeDefs`, or `types`, depending on what you are stitching.

  - When using batch delegation in type merging, the `argsFromKeys` function is now set only via the `argsFromKeys` property. Previously, if `argsFromKeys` was absent, it could be read from `args`.

  - Support for fragment hints has been removed in favor of selection set hints.

  - `stitchSchemas` now processes all `GraphQLSchema` and `SubschemaConfig` subschema input into new `Subschema` objects, handling schema config directives such aso`@computed` as well as generating the final transformed schema, stored as the `transformedSchema` property, if transforms are used. Signatures of the `onTypeConflict`, `fieldConfigMerger`, and `inputFieldConfigMerger` have been updated to include metadata related to the original and transformed subschemas. Note the property name change for `onTypeConflict` from `schema` to `subschema`.

  #### Mocking (`addMocksToSchema` and `@graphql-tools/mock`)

  - Mocks returning objects with fields set as functions are now operating according to upstream graphql-js convention, i.e. these functions take three arguments, `args`, `context`, and `info` with `parent` available as `this` rather than as the first argument.

  #### Other Utilities (`@graphql-tools/utils`)

  - `filterSchema`'s `fieldFilter` will now filter _all_ fields across Object, Interface, and Input types. For the previous Object-only behavior, switch to the `objectFieldFilter` option.
  - Unused `fieldNodes` utility functions have been removed.
  - Unused `typeContainsSelectionSet` function has been removed, and `typesContainSelectionSet` has been moved to the `stitch` package.
  - Unnecessary `Operation` type has been removed in favor of `OperationTypeNode` from upstream graphql-js.
  - As above, `applySchemaTransforms`/`applyRequestTransforms`/`applyResultTransforms` have been removed from the `utils` package, as they are implemented elsewhere or no longer necessary.

  ## Related Issues

  - proxy all the errors: #1047, #1641
  - better error handling for merges #2016, #2062
  - fix typings #1614
  - disable implicit schema pruning #1817
  - mocks not working for functions #1807

### Patch Changes

- Updated dependencies [be1a1575]
  - @graphql-tools/schema@7.0.0
  - @graphql-tools/utils@7.0.0

## 6.2.4

### Patch Changes

- 533d6d53: Bump all packages to allow adjustments
- Updated dependencies [32c3c4f8]
- Updated dependencies [533d6d53]
  - @graphql-tools/utils@6.2.4
  - @graphql-tools/schema@6.2.4
