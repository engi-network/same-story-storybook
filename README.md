# same-story-storybook

A boilerplate React app with default storybook configuration for use in regression testing the [Same Story? backend](https://github.com/engi-network/same-story-api).

### Run `storycap`

```
npx storycap http://localhost:58305 --viewport 800x600 --serverTimeout 50000 --captureTimeout 10000  --serverCmd 'start-storybook -p 58305'
```