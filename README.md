# target="\_blank"

Simple demonstration on how the lack of `rel="noopener noreferrer"` within an anchor tag can lead to a malicious redirect on the original page.

Without it, a malicious actor is able to use `window.opener.location` to redirect the page it was originally opened from.

## Entrypoint

`index.html`

## Observations

### **Vulnerable link**

Original page is redirected to `malicious.html`

### **Link with noopener noreferrer**

Original page remains the same
