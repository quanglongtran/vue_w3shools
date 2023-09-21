<template>
    <li v-bind="$attrs" style="margin-left: 5px">
        {{ itemName }}
        <slot>Fallback</slot>
        <slot name="test">Fallback</slot>
    </li>
</template>

<script>
export default {
    props: ["itemName"],
};
</script>
