# Tailwind CSS Class Application Issue

This repository demonstrates a bug where Tailwind CSS classes are not applied correctly, specifically a hover effect that is not working as expected. The `bug.js` file contains the code with the issue, while `bugSolution.js` provides the corrected code.

## Problem Description

A simple div element is styled using Tailwind CSS.  The expected behaviour is for the div to have a red background by default and change to blue on hover. However, the hover effect is not working, and the initial red background may also be absent.

## Solution

The issue was solved by ensuring that the Tailwind CSS directives were correctly included and the CSS was properly ordered in the stylesheet.  The solution may involve checking for conflicting class names or issues with the build process.