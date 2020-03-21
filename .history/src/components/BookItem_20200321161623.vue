<template>
    <li>{{ book.title }}</li>
</template>

<script>
export default {
    name: "BookItem",
    props: [
        'book'
    ]
}
</script>

<style>

</style>