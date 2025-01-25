# Tailwind CSS Classes Not Applying

This repository demonstrates a common issue encountered when using Tailwind CSS: classes failing to apply correctly, resulting in unexpected layout behavior.  The example involves a simple flex container with two divs that should each occupy half the width.  However, due to a common oversight (detailed below), the layout doesn't render as expected.

## Problem

The `bug.html` file showcases the issue.  Even with seemingly correct Tailwind CSS classes (`w-1/2`), the divs do not equally split the width. This is a frequent issue stemming from missing or incorrect parent container configuration.

## Solution

The `solution.html` file provides the corrected code. The key is ensuring the parent container (`<div class="flex">`) has the appropriate flexbox configuration to distribute space evenly among its children.  Adding `flex` to the parent correctly distributes the space.