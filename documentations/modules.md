# Modules in TypeScript

Modules in TypeScript allow you to organize your code into reusable and manageable units. They provide a way to encapsulate code and prevent naming conflicts. This documentation explains how to work with modules in your TypeScript project and provides examples of common scenarios.

## Table of Contents

1. [Introduction](#introduction)
2. [Creating Modules](#creating-modules)
3. [Exporting and Importing](#exporting-and-importing)
4. [Default Exports](#default-exports)
5. [Examples](#examples)

## Introduction

Modules in TypeScript help structure your code by dividing it into smaller, more focused files. Each module can contain variables, functions, classes, or other code constructs, and you can export and import these elements to use them across different parts of your project.

## Creating Modules

To create a module in TypeScript, you can create a separate `.ts` file and define your code within it. For example:

```typescript
// mathOperations.ts
export function add(a: number, b: number): number {
    return a + b;
}

export function subtract(a: number, b: number): number {
    return a - b;
}
```
