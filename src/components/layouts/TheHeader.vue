<template>
    <header>
        <h1>{{ title }}</h1>
    </header>
</template>

<script>
export default {
    name: 'TheHeader',
    props: {
        title: String
    },
}
</script>

<style >
    /*Lets choose a color pallete */
    header{
        background: #03045E;
        padding: 1rem 0;
    }
    header h1{
        color: #fff;
        text-align: center
    }
</style>