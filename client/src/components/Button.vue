<template>
    <button type="button" class="btn btn-secondary mr-2 ml-2 tombol" data-toggle="modal" v-bind:data-target="target" >{{ button }}</button>
</template>

<script>
export default {
    name: 'Button',
    props: ['button', 'target']
}
</script>


<style>
    .tombol:hover{
        color: red;
        background: transparent;
        border-color: red;
    }
</style>
