# CSS notes

- Inline styling > ID based > Class
- If same element is getting modified, class defined later takes precedence
- CSS variables declared by --<variable name> and accessed by var(--<variable name>)
- Making images responsive 
```
img {
  max-width: 100%;
  height: auto;
}
```
The max-width of 100% will make sure the image is never wider than the container it is in, and the height of auto will make the image keep its original aspect ratio.

- Making typography responsive : Instead of using em or px to size text, you can use viewport units for responsive typography.
```
body { width: 30vw; }
```
