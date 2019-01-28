<template>
    <div class="alert">
        <h2>{{text}}</h2>
        <hr>
        <button class="btn btn-primary">
            Continue
        </button>
    </div>
</template>

<script>
export default {
    props: ['type', 'text']
}   
</script>
<style type="scss" scoped>
.alert {
    text-align: center;
}
h2, .btn {
    margin: 20px auto;
}
</style>