# Cross-Site Scripting (XSS) Labs

## Overview
Cross-Site Scripting (XSS) is a web security vulnerability that allows attackers to inject malicious scripts into web pages viewed by other users.

## Labs Covered

1. **Reflected XSS into HTML context with nothing encoded**
2. **Stored XSS into HTML context with nothing encoded** 
3. **DOM XSS in document.write sink using source location.search**
4. **DOM XSS in innerHTML sink using source location.search**
5. **DOM XSS in jQuery anchor href attribute sink using location.search source**
6. **DOM XSS in jQuery selector sink using a hashchange event**
7. **Reflected XSS into attribute with angle brackets HTML-encoded**
8. **Stored XSS into anchor href attribute with double quotes HTML-encoded**
9. **Reflected XSS into a JavaScript string with angle brackets HTML encoded**
10. **DOM XSS in document.write sink using source location.search inside a select element**

## Key Concepts
- Reflected vs Stored vs DOM-based XSS
- Context-aware payload crafting
- Bypassing filters and encodings
- JavaScript execution in different contexts

[View Detailed Walkthroughs](./Lab-Walkthroughs.md)
