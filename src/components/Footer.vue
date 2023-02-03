<script setup>

defineProps({
    text: String,
});
</script>

<template>
    <div class="footer">
    <p>{{text}}</p>
    </div>
</template>

<style scope>

.footer{
    background: rgb(146,77,186);
    background: linear-gradient(83deg, rgba(146,77,186,1) 11%, rgba(209,25,218,1) 94%);
    width: 100%;
    position: absolute;
    left: 0;
    right: 0;
    bottom: 0;
}
</style>