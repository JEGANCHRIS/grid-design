# grid design

designed a website using grid

```
.gridcontainer {
  padding: 50px;
  display: grid;
  grid-template-columns: 10fr 10fr 10fr;
  gap: 20px;
  background-color: #777;
}
```

## responsive design

### breakpoints

- Desktop (1920px , 1280px)
- Laptop (1100px , 991px)
- Tablet (768px)
- phone (480px, 320px)

```
@media only screen and (max-width: 480px) {
  .gridcontainer {
    grid-template-columns: 1fr;
  }
}
```
## git commands

- `git add .`
- `git commit -m "init commit"`
- `git push origin master`