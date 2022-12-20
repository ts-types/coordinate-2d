# deep-partial

Coordinate data type for TypeScript. For example:

```typescript
const coordinate: Coordinate = { x: 12, y: -7 };
```

Using `DeepPartial<T>` instead makes this assignment possible:

```typescript
const myHouseNumber: DeepPartial<Employee> = { address: { number: 52 } };
```

## Installation

Just a quick `npm install --save-dev @fs-types/deep-partial`, or the Yarn
equivalent.
