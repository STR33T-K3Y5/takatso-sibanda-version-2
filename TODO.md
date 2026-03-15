# Blog Read More/Read Less Fix - Approved Plan Steps

## Status: In Progress

### Step 1: [IN PROGRESS] Update blog.html
- Remove inline `<script>` block with `toggleBlogContent` function
- Remove `onclick="toggleBlogContent(this)"` from button
- Add CSS rules for `.expand-text` / `.collapse-text` toggle
- Update icon to `fa-chevron-down`
- Test smooth expand/collapse animation

### Step 2: Test Functionality
- Verify main.js `ssBlogExpand()` handles clicks correctly
- Confirm text/icon toggle + smooth max-height transition
- Test multiple clicks, hover effects

### Step 3: Cleanup & Verify
- Ensure no JS errors in console
- Validate responsive behavior
- Check single post works perfectly

**Next: Proceed with Step 1 edits.**

