# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in my-app
npm create svelte@latest my-app

# install dependencies
npm install

# add mongoose
npm i -D mongoose

# add test code
Add below code to the top of src/routes/+page.svelte

<script>
	import { Schema } from 'mongoose';
	console.log('SCHEMA', Schema);
</script>

# start application in development
npm run dev
```

## Error 500
