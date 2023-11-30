[Setup with sveltekit fails #160](https://github.com/storybookjs/addon-svelte-csf/issues/160)

```bash
# 1. Install dependencies
npm i

# 2. Run storybook and check error logs
npm run storybook -w packages/storybook

# 3. Remove @storybook/addon-svelte-csf dependency
cd packages/storybook && npm remove @storybook/addon-svelte-csf

# 4. Remove @storybook/addon-svelte-csf from .storybook/main.js config

# 5. Run storybook and everything works
npm run storybook -w packages/storybook
```
