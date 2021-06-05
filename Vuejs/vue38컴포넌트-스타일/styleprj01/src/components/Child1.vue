<style scoped>
.main {
    border: solid 1px black;
    background-color: yellow;
}
</style>

<template>
    <div class="main test">
        {{ msg }}
        <Child11 />
        {{ msg }}
    </div>
</template>
<script>
import Child11 from "./Child11.vue";

export default {
    data: function () {
        return {
            msg: "Child1"
        };
    },
    components: {
        //
        Child11: Child11
    }
};
</script>