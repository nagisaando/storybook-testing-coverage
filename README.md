# Storybook coverage repo with nycic.json

## Dependencies
- Vue 3
- Vite

# Setup


```
npm install
```

## compiles and hot-reloads for development
```
npm run dev
```

## setup for storybook
```
npm run storybook
```


## run coverage
```
npm run test-storybook -- --coverage
```


# what I did
1. installed `@storybook/addon-coverage` add on and register it in .storybook/main.js
2. installed `vite-plugin-istanbul` and register it in .storybook/main.js
3. created nycrc.json in root and added extension key

# what I need
- coverage for vue file

# what I am getting
- only coverage for preview.js file
![Coverage](./src/assets/coverage.png)

- Also, not getting `__coverage__` object in developer tool
![Devtool](./src/assets/devtool.png)



