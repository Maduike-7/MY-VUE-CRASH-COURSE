<template>
    <h3>{{ task.text }}</h3>
</template>

<script>
export default {
    name: ' Tasks',
    props: {
        tasks: Array
    }
}
</script>