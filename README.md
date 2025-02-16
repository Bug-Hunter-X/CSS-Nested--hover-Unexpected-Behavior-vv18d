# CSS Nested :hover Unexpected Behavior

This repository demonstrates an uncommon issue related to nested `:hover` pseudo-classes in CSS.  The expected cascading behavior doesn't occur as anticipated.

## Problem

The primary problem lies in the misunderstanding of how nested `:hover` pseudo-classes function.  A nested `:hover` doesn't add another level of hover interaction; it's essentially redundant.  The browser interprets it as a single `:hover` state on the parent element.

## Solution

A simpler, more effective approach is to use a single `:hover` selector to achieve the intended style changes.  Avoid redundant nesting of `:hover` as this won't produce the desired outcome.