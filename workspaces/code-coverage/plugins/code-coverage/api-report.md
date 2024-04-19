## API Report File for "@backstage-community/plugin-code-coverage"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
/// <reference types="react" />

import { BackstagePlugin } from '@backstage/core-plugin-api';
import { Entity } from '@backstage/catalog-model';
import { RouteRef } from '@backstage/core-plugin-api';

// @public (undocumented)
export const codeCoveragePlugin: BackstagePlugin<
  {
    root: RouteRef<undefined>;
  },
  {}
>;

// @public
export const EntityCodeCoverageContent: () => JSX.Element;

// @public
export function isCodeCoverageAvailable(entity: Entity): boolean;

// @public @deprecated (undocumented)
export const isPluginApplicableToEntity: typeof isCodeCoverageAvailable;
```