<script>
export default {
    data() {
        return {};
    },
};
</script>

<template>
    <header>
        <ul>
            <li>Home</li>
            <li>Staff</li>
            <li>Lavora con noi</li>
            <li>Info</li>
            <li>Contattaci</li>
        </ul>
    </header>
</template>

<style lang="scss" scoped>
@use "./styles/partials/mixins.scss" as *;

ul {
    list-style: none;
    @include flex;
    li {
        margin-right: 1rem;
    }
}
</style>
