# Uncommon HTML Attribute Error

This repository demonstrates an uncommon error in HTML involving the use of a non-standard attribute.  While most browsers will silently ignore it, it can cause unexpected issues in certain scenarios (like custom JavaScript validation or specific frameworks). The error is described in detail below.

## Error Description
The issue arises when a non-standard attribute (an attribute not defined in the HTML specification) is added to an element.  For example, using an attribute such as `data-invalid-attribute` which is not a formally recognised attribute may seem harmless, but it may impact how your web page behaves.

## Solution
The solution is to avoid using non-standard attributes unless you have a very specific reason and are certain about its implications.  In most cases, standard attributes or the `data-*` attribute convention (e.g., `data-custom-attribute`) should suffice.  If you must use custom attributes, ensure that your JavaScript code or any other reliant components are built to handle it specifically.