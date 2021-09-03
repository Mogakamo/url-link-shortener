<template>
    <div class="footer">
        &copy;2021
    </div>
</template>

<script>
export default {
    name: 'Footer'

}
</script>

<style scoped>
    .footer {
        margin-top: 10px;
        grid-row-start: 5;
        grid-row-end: 6;
        grid-column-start: 4;
        grid-column-end: 5;
        border-top: .5px solid grey;
        margin-bottom: 10px;
        float: right;
        }
</style>