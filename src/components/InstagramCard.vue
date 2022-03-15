<template>
    <div class="card">
        <div class="card-header">
            Featured
        </div>
        <div class="card-body p-0">
            <img class="card-img-top" :src="info" />
        </div>
        <div class="card-footer text-muted">
            2 days ago
        </div>
    </div>
</template>

<script>
export default {
    name: 'InstagramCard',
    props: ['info']
}
</script>

<style lang="scss" scoped>
.card {
    margin-top: 20px;
}
</style>