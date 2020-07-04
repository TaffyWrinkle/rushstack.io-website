---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [NpmOptionsConfiguration](./rush-lib.npmoptionsconfiguration.md)

## NpmOptionsConfiguration class

Options that are only used when the NPM package manager is selected.

<b>Signature:</b>

```typescript
export declare class NpmOptionsConfiguration extends PackageManagerOptionsConfigurationBase 
```
<b>Extends:</b> [PackageManagerOptionsConfigurationBase](./rush-lib.packagemanageroptionsconfigurationbase.md)

## Remarks

It is valid to define these options in rush.json even if the NPM package manager is not being used.

The constructor for this class is marked as internal. Third-party code should not call the constructor directly or create subclasses that extend the `NpmOptionsConfiguration` class.
