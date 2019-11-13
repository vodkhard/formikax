# FORMIKAX

### Usage

```
<template>
    <Formikax @onSubmit="onSubmit" v-slot="{ handleSubmit }">
        <Field name="firstname" />
        <Field name="lastname" />

        <Field name="animal" as="select" label="What is your prefered animal ?">
            <option value>---Choose one---</option>
            <option value="dog">Dog</option>
            <option value="cat">Cat</option>
        </Field>

        <Field name="prefered" type="radio" value="vue" label="Vue" />
        <Field name="prefered" type="radio" value="react" label="React" />

        <button @click="handleSubmit">Validate</button>
    </Formikax>
</template>
```

## Project setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn run serve
```

### Compiles and minifies for production

```
yarn run build
```

### Run your tests

```
yarn run test
```

### Lints and fixes files

```
yarn run lint
```
