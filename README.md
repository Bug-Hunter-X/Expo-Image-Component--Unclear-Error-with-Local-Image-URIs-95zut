# Expo Image Component: Unclear Error with Local Image URIs

This repository demonstrates a common but obscure error encountered when using Expo's `Image` component with local image URIs. The error message itself isn't very helpful, leading to frustration when debugging.

## The Problem

When providing a local image URI to the `Image` component without the `file:///` prefix, Expo throws a cryptic error.  This is particularly problematic because the default error handling doesn't provide enough context for easy resolution.

## Solution

The solution is to ensure the URI you're using begins with `file:///`. This will correctly identify the file as a local resource.

This repository includes example code demonstrating the problem and its solution. Feel free to use this example to better understand how to resolve similar issues in your own projects.