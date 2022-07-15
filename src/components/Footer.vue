<template>
    <footer id="footer">
        <p>Make Your Burguer &copy; 2022</p>
    </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style scoped>
    #footer {
        height: 200px;
        background-color: #222;
        border-top:4px solid #111;
        color: #FCBA03;
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
    }

    p {
        top: 0;
        bottom: 0;
        right: 0;
        left: 0;
        margin-right: 7%;
    }
</style>