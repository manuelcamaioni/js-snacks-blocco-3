<script>
import NavLink from "./NavLink.vue";
export default {
    components: { NavLink },
    data() {
        return {
            NavList: [
                {
                    name: "Home",
                    link: "#",
                },
                {
                    name: "Staff",
                    link: "#",
                },
                {
                    name: "Lavora con noi",
                    link: "#",
                },
                {
                    name: "Info",
                    link: "#",
                },
                {
                    name: "Contattaci",
                    link: "#",
                },
            ],
        };
    },
};
</script>

<template>
    <header>
        <ul>
            <li v-for="element in NavList">
                <NavLink :link="element.link">{{ element.name }}</NavLink>
            </li>
        </ul>
    </header>
</template>

<style lang="scss" scoped>
ul {
    list-style: none;

    li {
        margin-right: 1rem;
    }
}
</style>
