<template>
    <div class="container">
        <div class="row">
            <p class="footer">BlueFemme &copy; <span>{{ currYear }}</span></p>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Footer',
        data() {
            return {
                currYear: new Date().getFullYear()
            }
        }
    }
</script>

<style scoped>
.footer{
    bottom: 0;
}
</style>