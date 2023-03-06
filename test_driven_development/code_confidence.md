# Code Confidence

## Introduction

This article introduces concepts around code confidence in that the written code works as expected.

## Testing Pyramid

### Introduction

### Testing Ice Cream

### Layers Of Testing

## Testing Strategy

### Introduction

## Code Confidence

### Introduction

Many development circles will insist on the idea of "test coverage". It is my belief that this creates the wrong approach to test driven development and therefore instead I aim for code confidence.

### Concept

To expand on this concept, if a change was to be made to the code how confident are we that the changes made aren't breaking changes.

With a high degree of confidence we can be near certain that a "green build" (one where all the tests pass) will have no breaking changes and vice versa.

### Best Practise

The best way to ensure "code confidence" is developing in a test driven way.

## Test Coverage

### Introduction

### Concept

### The Problems With Test Coverage

To focus on test coverage moves away from the point of doing test driven development. It emphasises coverage at the cost of what makes sense to cover and what is performant to cover. In other words writing a test for the sakes of writing a test to meet some arbitrary code coverage percentage target. 

This way of thinking often leads to poorly written tests that add little value to a project or a layer of testing that isn't required by the project.
