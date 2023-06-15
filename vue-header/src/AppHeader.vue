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
            <li>1</li>
            <li>2</li>
            <li>3</li>
            <li>4</li>
            <li>5</li>
        </ul>
    </header>
</template>

<style lang="scss" scoped>
@use "./styles/partials/mixins.scss" as *;

ul {
    list-style: none;
    @include flex;
}
</style>
