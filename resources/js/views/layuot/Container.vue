<template>
    <h1 class="container">Vue Router!</h1>
    <my-input></my-input>
    <my-button>регистрация</my-button>

</template>

<script>

    import MyInput from "../../components/UI/MyInput";
    import MyButton from "../../components/UI/MyButton";
    export default {
        name: "Container",
        components: {
            MyInput,
            MyButton
        }
    }
</script>

<style scoped lang="scss">
    .container {
        max-width: 120rem;
        margin: 8rem auto;
        background-color: var(--color-gray-light-1);
        box-shadow: var(--shadow-dark);
        min-height:50rem;

        @media only screen and (max-width: 75rem) {
            margin: 0;
            max-width: 100%;
            width: 100%;

        }
    }
