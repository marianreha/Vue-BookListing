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
            title: "All Books",
            books: [
                {title: 'Self-Reliance', author: 'Ralph Waldo Emerson'},
                {title: 'American Gods', author: 'Neil Gaiman'},
                {title: 'Amusing Ourselves to Death', author: 'Neil Postman'},
            ]
        }
    }
}
</script>

<style>
    h1, h2 {
        font-weight: normal;
    }

    ul {
        list-style-type: none;
        padding: 0;
    }

    li {
        display: block;
        margin: 0 10px;
    }
</style>