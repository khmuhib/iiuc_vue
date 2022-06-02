<template>
    <div class="container_fluid py-3" style="background-color: #D9D6FB">
        <div class="container">
            <div class="col">
                <div class="pagination_main">
                    <span>Home</span><span> > </span><span>About IIUC</span><span> > </span>
                </div>
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: 'PagingComponent',

}
</script>

<style scoped>

.pagination_main {
    text-align: left;
    margin-left: 10px;
}

.pagination_main span:nth-child(odd) {
    color: black;
    font-weight: bold;
    margin-right: 10px;
    font-size: 20px;
}

.pagination_main span:nth-child(even) {
    color: black;
    font-weight: bold;
    margin-right: 10px;
    font-size: 15px;
}
</style>