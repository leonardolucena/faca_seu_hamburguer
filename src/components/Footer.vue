<template>
    <div>
        <footer id="footer">
            <p>Make your burger &copy; 2021</p>
        </footer>
    </div>
</template>

<script>

    export default{
        name: 'Footer'
    }

</script>

<style scoped>
    #footer {
        height: 150px;
        background-color: #222;
        border-top: #111;
        color: #fcba03;
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
    }
</style>