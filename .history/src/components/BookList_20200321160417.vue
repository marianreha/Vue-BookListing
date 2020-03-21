<template>
    <div>
        <div>
            <h1>{{ title }}</h1>
        </div>
        <div>
            <ul>
                <li>Title1</li>
                <li>Title2</li>
                <li>Title3</li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: "BookList",
    data() {
        return {
            title: "All Books"
        }
    }
}
</script>

<style>
    h1, h2 {
        font-weight: normal;
    }
</style>